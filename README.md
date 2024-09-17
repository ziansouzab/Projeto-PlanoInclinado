# Projeto-PlanoInclinado
Projeto de plano inclinado construído para matéria de Fenômenos de Transporte


O software descrito no código é uma simulação interativa que utiliza o **GeoGebra**, uma plataforma matemática para explorar geometria, álgebra e cálculo. O objetivo da simulação é modelar um plano inclinado com variáveis ajustáveis, como o ângulo da rampa e a espessura de um fluido, provavelmente óleo, utilizado para simular a viscosidade.

### Estrutura do Código:
1. **HTML**:
   - O código HTML define uma página simples com uma estrutura básica (`<div>`) onde o aplicativo GeoGebra será exibido.
   - Através do script GeoGebra, o conteúdo interativo é carregado e apresentado no navegador.

2. **GeoGebra Applet**:
   - Utiliza o script `https://cdn.geogebra.org/apps/deployggb.js` para carregar o aplicativo GeoGebra no formato de applet.
   - O applet é configurado com parâmetros, como o tamanho (800x600 pixels), barras de ferramentas visíveis, e a definição do idioma em português (`language: "pt"`).

3. **Simulação**:
   - Um segmento chamado "rampa" é desenhado no plano, representando um plano inclinado de -5 a 5 no eixo x.
   - Um controle deslizante é adicionado para ajustar o ângulo da rampa (`α`), variando de 0° a 90°. Quando o ângulo é alterado, a rampa gira em torno do ponto (0,0).
   - Outro controle deslizante, `Δn`, controla a espessura de uma linha que representa a espessura de um fluido (óleo), que pode variar de 0.01 a 10.

4. **Funções interativas**:
   - O código permite ajustar dinamicamente o ângulo da rampa e a espessura do fluido (óleo), oferecendo uma visualização interativa de como esses parâmetros afetam o comportamento da simulação.
   - O zoom é ajustado para centralizar a visualização entre as coordenadas -5 e 5 no eixo x, e entre -1 e 10 no eixo y.

### Propósito:
Esse tipo de simulação pode ser utilizado para visualizar e explorar conceitos de **física mecânica**, como a **inclinação de rampas** e o **efeito da viscosidade em superfícies inclinadas**. Alunos e professores podem interagir com a simulação para ver como diferentes variáveis afetam os resultados, o que facilita a compreensão visual desses conceitos físicos.

### Possíveis Melhorias:
1. **Controle da Unidade**: Certificar que as unidades usadas para o ângulo (`α`) sejam consistentes entre graus e radianos, conforme necessário pelo GeoGebra.
2. **Animação**: Adicionar mais funcionalidades, como animação de objetos deslizando pela rampa, para ilustrar melhor a influência do ângulo e da viscosidade. 

O software proporciona uma maneira prática de ensinar ou aprender física de maneira interativa.

