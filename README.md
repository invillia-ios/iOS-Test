# Invillia - iOS Test
Crie um app iOS que liste os próximos filmes que serão lançados, com poster, nome do filme e data de lançamento, além da opção para favoritar o filme. Ao clicar em um filme, deverá exibir mais detalhes do filme, como sinopse, atores, tempo de filme, se esta favoritado ou não... use sua criatividade.

## Regras
* Você deve utilizar um botão na NavigationBar na tela inicial, assim você deverá trocar a forma que os filmes são listados entre lista de uma linha e grid de dois itens por linha.
* Faça as requests assincronas.
* Experiência de usuário e design são diferencias, não mandatórios.
* Arquitetura: MVVM.
* Use design patterns.

### Dicas
* Você pode usar a API do IMDB (http://www.omdbapi.com) para pegar os dados dos filmes.
* Ao favoritar um filme, salve apenas localmente essa informação.
* Tratar os status de loading, error, success.
* Unit Test pelo menos da camada de negócio.
