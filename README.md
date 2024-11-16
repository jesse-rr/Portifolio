# Portfólio HTML5 e CSS3

Este projeto apresenta um portfólio construído com HTML5 e CSS3, explorando conceitos fundamentais como semântica, responsividade e estilização avançada. Cada seção está organizada para aprendizado prático e modular.

---

## Tópicos de Estudo

### HTML5

<details>
  <summary>1. Estrutura Básica do HTML</summary>
  ![Estrutura básica de um documento HTML5](/home/jrr/Imagens/1.png)

  - **Elementos e Estrutura**: A base do HTML, incluindo `<!DOCTYPE html>`, `<html>`, `<head>` e `<body>`.
  - **Exemplo no Código**:
    - `<!DOCTYPE html>` define o tipo de documento.
    - `<head>` contém metadados, como título e links para arquivos CSS.
</details>

---

<details>
  <summary>2. Semântica no HTML</summary>
  ![Exemplo de semântica no HTML5](images/html-semantica.png)

  - **Elementos Estruturais**: Como `<header>`, `<main>` e `<footer>`, que organizam o conteúdo.
  - **Exemplo no Código**:
    - `<header>`: Inclui logo, navegação e links.
    - `<main>` e `<section>`: Para conteúdo principal e subseções.
</details>

---

<details>
  <summary>3. Elementos HTML (Formulários e Tabelas)</summary>
  ![Formulários e tabelas em HTML](images/html-formularios-tabelas.png)

  - **Formulários**: Campos de entrada como `<input>` e botões.
  - **Tabelas**: Estruturação de dados tabulares.
  - **Exemplo no Código**:
    - `<form>` com campos interativos.
    - `<table>` para exibição de dados estruturados.
</details>

---

### CSS3

<details>
  <summary>1. Conceitos Básicos de CSS3</summary>
  ![Conceitos básicos de CSS](images/css-conceitos.png)

  - **Regras de Estilo**: Seletores, propriedades e valores.
  - **Organização Modular**: Uso de `@import` para consolidar arquivos CSS.
  - **Exemplo no Código**:
    - Consolidando arquivos com `@import`:
      ```css
      @import url('header.css');
      @import url('footer.css');
      ```
</details>

---

<details>
  <summary>2. Posicionamento de Elementos</summary>
  ![Posicionamento de elementos com CSS](images/css-posicionamento.png)

  - **Flexbox**: Alinhamento flexível.
  - **Grid**: Layouts responsivos em grades.
  - **Exemplo no Código**:
    - `flexbox` para organização de conteúdo.
    - `grid` para layouts responsivos:
      ```css
      body {
        display: grid;
        grid-template-rows: auto 1fr auto;
      }
      ```
</details>

---

<details>
  <summary>3. Responsividade</summary>
  ![Responsividade com CSS](images/css-responsividade.png)

  - **Media Queries**: Estilos para diferentes dispositivos.
  - **Exemplo no Código**:
    - Ajustes para telas menores:
      ```css
      @media (max-width: 767px) {
        .tools-list {
          grid-template-columns: repeat(4, 1fr);
        }
      }
      ```
</details>

---

<details>
  <summary>4. Estilização Avançada</summary>
  ![Efeitos avançados com CSS](images/css-avancado.png)

  - **Transições e Transformações**: Efeitos visuais dinâmicos.
  - **Uso de Variáveis CSS**: Consistência na estilização.
  - **Exemplo no Código**:
    - Transição para botões:
      ```css
      .dropdown-button {
        transition: background-color 0.3s;
      }
      ```
</details>

---

Este projeto demonstra boas práticas de design responsivo e organização modular, tornando o portfólio funcional e atrativo em diversos dispositivos.

# README: Portfólio Responsivo com CSS3

Este projeto é um portfólio responsivo criado com HTML e CSS3. Ele ilustra conceitos fundamentais e avançados de CSS, como Flexbox, Grid, responsividade e estilização dinâmica, organizados em uma estrutura modular.

---

## Tópicos de Estudo

<details>
  <summary>1. Conceitos Básicos de CSS3</summary>
  ![Ilustração de conceitos básicos de CSS3](images/conceitos-basicos.png)

  - **Regras de Utilização**:
    - Sintaxe: Seletores, propriedades e valores.
    - Organização: Uso de arquivos separados e imports.
  - **Criação de Estilos**:
    - Definição de estilos para elementos HTML.
  - **Exemplo no Código**:
    - Uso de `@import` no arquivo `styles.css` para consolidar múltiplos arquivos CSS:
      ```css
      @import url('header.css');
      @import url('footer.css');
      @import url('dropdown.css');
      ```
</details>

---

<details>
  <summary>2. Regras de Utilização</summary>
  ![Exemplo de variáveis CSS](images/regras-utilizacao.png)

  - **Histórico e Conceitos**:
    - CSS como ferramenta para separar estilo de estrutura.
    - Reutilização de regras com seletores e classes.
  - **Exemplo no Código**:
    - Definição de variáveis CSS no `:root`:
      ```css
      :root {
        --title-font: "League Spartan", sans-serif;
        --first-color: #20201e;
      }
      ```
</details>

---

<details>
  <summary>3. Aplicação do CSS ao HTML</summary>
  ![Modelo de caixa em CSS](images/modelo-caixa.png)

  - **Modelo de Caixa**:
    - Controle de dimensionamento, margens, preenchimentos e bordas.
  - **Display e Cores**:
    - Configuração de exibição e personalização de cores.
  - **Exemplo no Código**:
    - Modelo de caixa aplicado no `.project`:
      ```css
      .project {
        border: 1px solid black;
        padding: 10px;
        margin: 0 0 6px 0;
        background-color: rgba(0, 0, 0, 0.138);
      }
      ```
    - Uso de cores:
      ```css
      body {
        background-color: var(--third-color);
      }
      ```
</details>

---

<details>
  <summary>4. Posicionando Elementos com CSS</summary>
  ![Posicionamento com Flexbox](images/flexbox.png)

  - **Float**: Ausente no código.
  - **Flexbox**:
    - Alinhamento e posicionamento flexíveis.
  - **Exemplo no Código**:
    - Uso de `flexbox` em `.project`:
      ```css
      .project {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
      }
      ```
</details>

---

<details>
  <summary>5. Posicionando Elementos com CSS3 (Parte 2)</summary>
  ![Posicionamento com Grid](images/grid-positioning.png)

  - **Position**:
    - Configuração relativa/absoluta para posicionamento.
  - **Grid**:
    - Organização em grades para layouts responsivos.
  - **Exemplo no Código**:
    - `position` usado em `.dropdown-content`:
      ```css
      .dropdown-content {
        position: absolute;
        left: 0;
      }
      ```
    - `grid` aplicado no corpo:
      ```css
      body {
        display: grid;
        grid-template-rows: auto 1fr auto;
      }
      ```
</details>

---

<details>
  <summary>6. Responsividade com CSS</summary>
  ![Responsividade com Media Queries](images/responsividade.png)

  - **Media Queries e Breakpoints**:
    - Ajustes de estilos para diferentes tamanhos de tela.
  - **Exemplo no Código**:
    - Responsividade configurada com `@media`:
      ```css
      @media (max-width: 767px) {
        .tools-list {
          grid-template-columns: repeat(4, 1fr);
        }
      }
      ```
</details>

---

<details>
  <summary>7. Avançando no CSS</summary>
  ![Transições e efeitos avançados](images/avancado.png)

  - **Transições e Transformações**:
    - Efeitos visuais dinâmicos.
  - **Propriedades Personalizadas**:
    - Uso de variáveis CSS para consistência.
  - **Importação de Fontes Externas**:
    - Uso do `@import` para fontes como `Inter` e `Montserrat`.
  - **Exemplo no
