# Portfólio HTML5 e CSS3 - Dropdown

Este projeto apresenta um portfólio construído com HTML5 e CSS3, explorando conceitos fundamentais como semântica, responsividade e estilização avançada. Cada seção está organizada para aprendizado prático e modular.

---

## Tópicos de Estudo

### HTML5

#### 1. Estrutura Básica do HTML
<details>
  <summary>Clique para ver o exemplo</summary>
  
  - **Elementos e Estrutura**: A base do HTML, incluindo `<!DOCTYPE html>`, `<html>`, `<head>` e `<body>`.
  - **Exemplo no Código**:
    - `<!DOCTYPE html>` define o tipo de documento.
    - `<head>` contém metadados, como título e links para arquivos CSS.
    - A estrutura completa de um documento HTML pode ser vista abaixo:
    ```html
    <!DOCTYPE html>
    <html lang="pt-BR">
      <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Portfólio</title>
        <link rel="stylesheet" href="styles.css">
      </head>
      <body>
        <header>
          <h1>Meu Portfólio</h1>
          <nav>
            <ul>
              <li><a href="#about">Sobre</a></li>
              <li><a href="#projects">Projetos</a></li>
              <li><a href="#contact">Contato</a></li>
            </ul>
          </nav>
        </header>
        <main>
          <section id="about">
            <h2>Sobre Mim</h2>
            <p>Detalhes sobre minha experiência.</p>
          </section>
          <section id="projects">
            <h2>Meus Projetos</h2>
            <p>Descrição dos projetos desenvolvidos.</p>
          </section>
        </main>
        <footer>
          <p>© 2024 Meu Portfólio</p>
        </footer>
      </body>
    </html>
    ```

</details>

---

#### 2. Semântica no HTML
<details>
  <summary>Clique para ver o exemplo</summary>
  
  - **Elementos Estruturais**: Como `<header>`, `<main>` e `<footer>`, que organizam o conteúdo de forma mais acessível e clara.
  - **Exemplo no Código**:
    - `<header>`: Utilizado para a navegação principal.
    - `<main>`: Para conteúdo principal da página.
    - `<footer>`: Contém informações de rodapé, como copyright.
    - A semântica de um código HTML permite uma melhor organização do conteúdo para SEO e acessibilidade.
    ```html
    <header>
      <h1>Portfólio de João</h1>
      <nav>
        <ul>
          <li><a href="#home">Home</a></li>
          <li><a href="#services">Serviços</a></li>
          <li><a href="#contact">Contato</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <section id="home">
        <h2>Bem-vindo ao meu portfólio</h2>
        <p>Este é um exemplo de como usar semântica em HTML.</p>
      </section>
      <section id="services">
        <h2>Meus Serviços</h2>
        <p>Desenvolvimento web, design e consultoria.</p>
      </section>
    </main>
    <footer>
      <p>© 2024 João Developer</p>
    </footer>
    ```

</details>

---

#### 3. Elementos HTML (Formulários e Tabelas)
<details>
  <summary>Clique para ver o exemplo</summary>
  
  - **Formulários**: Campos de entrada como `<input>`, `<select>`, e botões de envio.
  - **Tabelas**: Organize dados tabulares utilizando `<table>`, `<tr>`, `<th>`, e `<td>`.
  - **Exemplo no Código**:
    - Formulário simples para entrada de dados:
    ```html
    <form action="/submit" method="POST">
      <label for="name">Nome:</label>
      <input type="text" id="name" name="name" required>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      <button type="submit">Enviar</button>
    </form>
    ```
    - Tabela para exibição de dados:
    ```html
    <table>
      <thead>
        <tr>
          <th>Nome</th>
          <th>Idade</th>
          <th>Cidade</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>João</td>
          <td>30</td>
          <td>São Paulo</td>
        </tr>
        <tr>
          <td>Maria</td>
          <td>25</td>
          <td>Rio de Janeiro</td>
        </tr>
      </tbody>
    </table>
    ```

</details>

---

### CSS3

#### 1. Conceitos Básicos de CSS3
<details>
  <summary>Clique para ver o exemplo</summary>
  
  - **Regras de Estilo**: Definir regras usando seletores, propriedades e valores.
  - **Organização Modular**: Separação do código CSS em diferentes arquivos para modularidade.
  - **Exemplo no Código**:
    - Utilizando `@import` para modularizar o código:
    ```css
    @import url('reset.css');
    @import url('header.css');
    @import url('footer.css');
    ```

</details>

---

#### 2. Posicionamento de Elementos
<details>
  <summary>Clique para ver o exemplo</summary>
  
  - **Flexbox**: Para layouts flexíveis e alinhamento de itens.
  - **Grid**: Organize o conteúdo em linhas e colunas.
  - **Exemplo no Código**:
    - Flexbox para alinhamento de itens:
      ```css
      .container {
        display: flex;
        justify-content: space-between;
        align-items: center;
      }
      ```
    - Grid para layout responsivo:
      ```css
      body {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
      }
      ```

</details>

---

#### 3. Responsividade
<details>
  <summary>Clique para ver o exemplo</summary>
  
  - **Media Queries**: Ajustes de estilo dependendo da largura da tela do dispositivo.
  - **Exemplo no Código**:
    - Ajuste para dispositivos menores com media queries:
    ```css
    @media (max-width: 768px) {
      body {
        font-size: 14px;
      }
    }
    ```

</details>

---

#### 4. Estilização Avançada
<details>
  <summary>Clique para ver o exemplo</summary>
  
  - **Transições e Transformações**: Criando animações e efeitos visuais dinâmicos.
  - **Uso de Variáveis CSS**: Defina cores e fontes reutilizáveis.
  - **Exemplo no Código**:
    - Transição para o botão:
      ```css
      .button {
        transition: background-color 0.3s ease;
      }
      .button:hover {
        background-color: #ff5733;
      }
      ```
    - Variáveis CSS:
      ```css
      :root {
        --primary-color: #3498db;
        --font-family: "Arial", sans-serif;
      }
      ```

</details>

---

#### 5. Uso de Fontes e Cores
<details>
  <summary>Clique para ver o exemplo</summary>
  
  - **Importação de Fontes Externas**: Usando Google Fonts para fontes personalizadas.
  - **Exemplo no Código**:
    - Importação de fonte:
      ```css
      @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
      body {
        font-family: 'Roboto', sans-serif;
      }
      ```

</details>

---

#### 6. Animações e Efeitos
<details>
  <summary>Clique para ver o exemplo</summary>
  
  - **Animações CSS**: Definindo animações com `@keyframes`.
  - **Exemplo no Código**:
    - Animação de um botão:
      ```css
      @keyframes pulse {
        0% { transform: scale(1); }
        50% { transform: scale(1.1); }
        100% { transform: scale(1); }
      }
      .button {
        animation: pulse 1s infinite;
      }
      ```

</details>

---

#### 7. Design Responsivo
<details>
  <summary>Clique para ver o exemplo</summary>
  
  - **Layouts Responsivos**: Alteração de layout conforme a largura da tela.
  - **Exemplo no Código**:
    - Ajustes de layout para telas menores:
      ```css
      @media (max-width: 480px) {
        .container {
          flex-direction: column;
        }
      }
      ```

</details>

---

Este projeto demonstra boas práticas de design responsivo e organização modular, tornando o portfólio funcional e atrativo em diversos dispositivos.
