<details>
  <summary>Conceitos básicos de CSS3</summary>

  <details>
    <summary>Regras de utilização</summary>
    <p>O CSS (Cascading Style Sheets) é utilizado para definir o estilo visual de uma página web. Ele permite que você modifique o layout, as cores, o tamanho e outros aspectos visuais do conteúdo HTML.</p>
    <p><strong>Exemplo de código:</strong></p>
    ```css
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f0f0f0;
    }
    ```
  </details>

  <details>
    <summary>Aplicação ao HTML</summary>
    <p>CSS é aplicado ao HTML de diversas maneiras: por meio de estilos embutidos, internos ou externos.</p>
    <p><strong>Exemplo de código:</strong></p>
    ```html
    <link rel="stylesheet" href="styles.css">
    <div class="container">Conteúdo aqui</div>
    ```
  </details>

  <details>
    <summary>Criação de estilos</summary>
    <p>Você pode criar estilos para selecionar elementos HTML com base em suas tags, classes ou IDs.</p>
    <p><strong>Exemplo de código:</strong></p>
    ```css
    .container {
      padding: 20px;
      background-color: #fff;
    }
    ```
  </details>

</details>

<details>
  <summary>Regras de Utilização</summary>

  <details>
    <summary>Histórico</summary>
    <p>O CSS foi criado para melhorar a apresentação visual de páginas HTML, separando o conteúdo da aparência.</p>
  </details>

  <details>
    <summary>Conceitos</summary>
    <p>CSS é uma linguagem de estilo que permite personalizar a apresentação de documentos HTML ou XML.</p>
  </details>

</details>

<details>
  <summary>Aplicação do CSS ao HTML</summary>

  <details>
    <summary>Modelo de caixa</summary>
    <p>Todo elemento HTML é representado como uma caixa retangular que pode ter margens, bordas, preenchimento e conteúdo.</p>
    <p><strong>Exemplo de código:</strong></p>
    ```css
    div {
      margin: 10px;
      padding: 20px;
      border: 1px solid #000;
    }
    ```
  </details>

  <details>
    <summary>Dimensionamento</summary>
    <p>Você pode controlar o tamanho dos elementos usando as propriedades width e height.</p>
    <p><strong>Exemplo de código:</strong></p>
    ```css
    div {
      width: 200px;
      height: 100px;
    }
    ```
  </details>

  <details>
    <summary>Preenchimento</summary>
    <p>O preenchimento (padding) adiciona espaço entre o conteúdo do elemento e suas bordas.</p>
    <p><strong>Exemplo de código:</strong></p>
    ```css
    .container {
      padding: 15px;
    }
    ```
  </details>

  <details>
    <summary>Bordas</summary>
    <p>Você pode adicionar bordas aos elementos para destacar suas divisões.</p>
    <p><strong>Exemplo de código:</strong></p>
    ```css
    .box {
      border: 2px solid #000;
    }
    ```
  </details>

  <details>
    <summary>Margens</summary>
    <p>Margens são usadas para criar espaço fora de um elemento, afastando-o de outros elementos ao redor.</p>
    <p><strong>Exemplo de código:</strong></p>
    ```css
    .box {
      margin: 20px;
    }
    ```
  </details>

  <details>
    <summary>Display</summary>
    <p>A propriedade display controla como os elementos são exibidos (inline, block, flex, grid, etc.).</p>
    <p><strong>Exemplo de código:</strong></p>
    ```css
    .box {
      display: flex;
    }
    ```
  </details>

  <details>
    <summary>Cores</summary>
    <p>Você pode definir cores de fundo e de texto usando o nome da cor, valores hexadecimais ou RGB.</p>
    <p><strong>Exemplo de código:</strong></p>
    ```css
    body {
      background-color: #333;
      color: #fff;
    }
    ```
  </details>

</details>

<details>
  <summary>Posicionando elementos com CSS</summary>

  <details>
    <summary>Float</summary>
    <p>A propriedade float é usada para posicionar um elemento à esquerda ou à direita dentro de seu contêiner.</p>
    <p><strong>Exemplo de código:</strong></p>
    ```css
    .float-left {
      float: left;
    }
    ```
  </details>

  <details>
    <summary>Flexbox</summary>
    <p>Flexbox é um modelo de layout que facilita a distribuição do espaço entre os itens em um contêiner, permitindo layouts flexíveis.</p>
    <p><strong>Exemplo de código:</strong></p>
    ```css
    .container {
      display: flex;
      justify-content: space-between;
    }
    ```
  </details>

</details>

<details>
  <summary>Posicionando elementos do CSS3 (parte 2)</summary>

  <details>
    <summary>Position</summary>
    <p>A propriedade position controla o posicionamento de um elemento (static, relative, absolute, fixed).</p>
    <p><strong>Exemplo de código:</strong></p>
    ```css
    .box {
      position: relative;
      top: 20px;
    }
    ```
  </details>

  <details>
    <summary>Grid</summary>
    <p>CSS Grid Layout é um sistema de layout que permite criar grids (grades) para organizar o conteúdo de forma eficiente.</p>
    <p><strong>Exemplo de código:</strong></p>
    ```css
    .container {
      display: grid;
      grid-template-columns: 1fr 1fr 1fr;
    }
    ```
  </details>

</details>

<details>
  <summary>Responsividade com CSS</summary>

  <details>
    <summary>Media queries</summary>
    <p>Media queries permitem alterar o estilo de uma página com base no tamanho da tela do dispositivo.</p>
    <p><strong>Exemplo de código:</strong></p>
    ```css
    @media (max-width: 768px) {
      .container {
        display: block;
      }
    }
    ```
  </details>

  <details>
    <summary>Breakpoints</summary>
    <p>Breakpoints definem os pontos de interrupção para aplicar estilos diferentes em diferentes larguras de tela.</p>
  </details>

  <details>
    <summary>Projetando responsivamente</summary>
    <p>O design responsivo utiliza media queries e técnicas como flexbox e grid para garantir que o layout se adapte bem a diferentes dispositivos.</p>
  </details>

</details>

<details>
  <summary>Avançando no CSS</summary>

  <details>
    <summary>Transições</summary>
    <p>As transições permitem que você defina animações suaves entre estados de estilo.</p>
    <p><strong>Exemplo de código:</strong></p>
    ```css
    .box {
      transition: transform 0.3s;
    }
    .box:hover {
      transform: scale(1.1);
    }
    ```
  </details>

  <details>
    <summary>Transformações</summary>
    <p>As transformações permitem aplicar efeitos de transformação, como rotação, escalonamento e translação.</p>
    <p><strong>Exemplo de código:</strong></p>
    ```css
    .box {
      transform: rotate(45deg);
    }
    ```
  </details>

  <details>
    <summary>Propriedades personalizadas</summary>
    <p>As propriedades personalizadas (variáveis) permitem reutilizar valores ao longo do CSS.</p>
    <p><strong>Exemplo de código:</strong></p>
    ```css
    :root {
      --primary-color: #3498db;
    }
    .box {
      background-color: var(--primary-color);
    }
    ```
  </details>

  <details>
    <summary>Limpeza de estilos</summary>
    <p>A limpeza de estilos pode ser feita utilizando o arquivo Normalize.css, que ajusta a renderização padrão entre navegadores.</p>
  </details>

  <details>
    <summary>Importação de fontes externas</summary>
    <p>Você pode importar fontes externas, como do Google Fonts, para customizar a tipografia do seu site.</p>
    <p><strong>Exemplo de código:</strong></p>
    ```css
    @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
    body {
      font-family: 'Roboto', sans-serif;
    }
    ```
  </details>

</details>
