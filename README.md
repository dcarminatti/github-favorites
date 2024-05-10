# GitHub Favorites

Bem-vindo ao GitHub Favorites SPA, uma Single Page Application (SPA) simples desenvolvida com HTML, CSS e JavaScript. Esta aplicação permite que você crie uma lista de perfis do GitHub, comsumindo a API, como seus favoritos e armazena essa lista localmente usando o `localStorage`.

![image](https://github.com/dcarminatti/github-favorites/assets/68664365/8b02a77f-12f9-4db2-b090-dc6e47addd0a)

## Recursos

### Adicionar Perfil Github à lista

-   Na seção "Adicionar Perfil", insira o nome de usuário do GitHub que você deseja adicionar à sua lista de favoritos.
-   Clique no botão "Adicionar" para incluir o perfil na tabela de favoritos.

### Remover Perfil GitHub da lista

-   Na tabela de favoritos, cada perfil do GitHub adicionado terá um botão "Remover".
-   Clique no botão "Remover" para excluir o perfil da lista de favoritos.

### Armazenamento Local

-   A lista de favoritos é armazenada localmente no seu navegador usando `localStorage`.
-   Mesmo ao fechar o navegador e abrir novamente, a lista de favoritos será mantida.

## Estrutura do Projeto

-   **index.html:** O arquivo HTML principal que contém a estrutura da página.
-   **style.css:** O arquivo CSS para estilizar a página.
-   **main.js:** O arquivo JavaScript que inicia a lógica por trás da página.
-   **Favorites.js:** O arquivo JavaScript que armazena a classe Favorites e a subclasse FavoritesView, que contenham as funções e propriedades que permitem o funcionamento da página
-   **GithubUser.js:** O arquivo JavaScript que armazena a classe GithubUser que por sua vez possuí um método estático chamado `search`, que é usado para buscar as informações do usuário desejado na API do Github
