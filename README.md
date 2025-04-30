
# CSS: Flexbox e layouts responsivos

Página inicial da Alura Play.

## 🔨 Funcionalidades do Projeto

A página possui um cabeçalho, um menu lateral, uma lista de vídeos, e um rodapé.

## ✔️ Técnicas e Tecnologias Utilizadas

As principais técnicas e tecnologias utilizadas neste projeto são:

- **`HTML`**: Linguagem de marcação utilizada para estruturar o conteúdo das páginas web.
- **`CSS`**: Utilizado para estilizar a apresentação da página web.
  - **`CSS Flexbox`**: Utilizado para organizar elementos de forma flexível e responsiva, garantindo um layout moderno e adaptável. Abaixo estão os principais atributos utilizados do Flexbox:
    - **`display: flex`**: Define um elemento como um container flexível, ativando as propriedades Flexbox para os elementos filhos.
    - **`flex-direction`**: Define a direção principal do layout dos itens flexíveis.
    - **`justify-content`**: Alinha os itens ao longo do eixo principal (horizontal por padrão).
    - **`align-items`**: Alinha os itens ao longo do eixo transversal (vertical por padrão).
    - **`align-content`**: Alinha várias linhas de itens flexíveis quando há espaço extra no eixo transversal. Funciona quando há múltiplas linhas (com `flex-wrap`).
    - **`flex-wrap`**: Define se os itens devem ou não quebrar para a próxima linha.
    - **`flex-flow`**: Combina `flex-direction` e `flex-wrap` em uma única propriedade.
    - **`order`**: Define a ordem dos itens dentro do container flexível.
    - **`flex-grow`**: Define a capacidade de um item flexível de crescer, ocupando o espaço disponível.
    - **`flex-shrink`**: Define a capacidade de um item de encolher caso necessário.
    - **`flex-basis`**: Define o tamanho inicial do item antes de o espaço disponível ser distribuído.
    - **`flex`**: Combina `flex-grow`, `flex-shrink` e `flex-basis` em uma única propriedade para maior simplicidade.
    - **`align-self`**: Permite modificar o alinhamento de um item específico, substituindo o valor definido em `align-items` para aquele item.
  - **`CSS Grid`**: Utilizado para organizar elementos de forma flexível e responsiva, garantindo um layout moderno e adaptável. Abaixo estão os principais atributos utilizados do Grid:
    - **`grid-template-columns`**: Define o número de colunas e suas larguras.
    - **`grid-area`**: Nomeação de áreas específicas do grid para layout personalizado.

Esses atributos são essenciais para criar um layout flexível, garantindo que a página seja responsiva e adaptável a diferentes tamanhos de tela e dispositivos.

## 📁 Acesso ao Projeto

Você pode [acessar o código-fonte do projeto inicial](https://github.com/nana-ferreira/aluraplay/tree/main).

## 🛠️ Como Abrir e Rodar o Projeto

Após baixar o projeto, você pode abri-lo no Visual Studio Code. Para isso, siga os passos abaixo:

1. No menu superior do VS Code, clique em:
   * **File > Open Folder** (ou uma opção similar).
2. Procure o local onde o projeto foi salvo e selecione a pasta (se o projeto foi baixado como um arquivo ZIP, será necessário extraí-lo antes).
3. Clique em **OK**.

Após finalizar esses passos, você pode executar a aplicação usando a extensão **Live Server** 🏆. Isso facilitará a visualização do projeto em seu navegador e garantirá que as alterações sejam refletidas automaticamente.
