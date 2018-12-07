# Invillia - Avaliação iOS

## Sobre o teste
Gostaríamos de um aplicativo onde fosse possível:
* Visualizar os filmes que serão lançados;
* Buscar filmes por um termo: Ex.: buscar por `the lord of` e trazer os filmes com esse termo;
* Ver os detalhes de um filme selecionado;
* Visualizar os filmes favoritados;

## Fluxo do App
* Você deve utilizar um botão na NavigationBar na tela inicial, assim você deverá trocar a forma que os filmes são listados entre lista de uma linha e grid de dois itens por linha;
* O usuário pode querer favoritar um filme na listagem, nos detalhes;
* Tratar os status de loading, error, success;
* Na tela de listagem: Nome, poster, data de lançamento e opção de favoritar;
* Na tela de detalhe: Trailer (pode abrir em app externo, eg. Youtube), nome, plot, atores, tempo de duração, opção de favoritar;
* Na tela de favoritos: Listagem dos filmes favoritados.

## Avaliação
* Arquitetura: use pelo menos uma camada a mais de MVC (eg. MVVM).
* Fica a seu critério a organização de código e o uso de bibliotecas;
* Gostamos de testes, mas aplicá-los no seu app fica a seu critério;
* Experiência de usuário e design são diferencias, não mandatórios;

### Entrega
* Crie um repositório público no GitHub;
* Crie um branch para o desenvolvimento e não commit nada no master;
* Adicione no `readme.md` pelo menos DOIS `screenshots` da sua app, e explique porque você desenvolveu sua app da maneira que foi desenvolvida;
* Adicione também no `readme.md` as instruções para rodar o seu app;
* Abra um PR do desenvolvimento para o master e envie o link para um dos entrevistadores;
* Prazo de 1 semana a partir do envio do link do desafio.

### Dicas
* Utilize a API do TMDB (https://developers.themoviedb.org/3/getting-started/introduction) para pegar os dados dos filmes.
* Ao favoritar um filme, salve apenas localmente essa informação.
