# pokedex-dio

Pokedex criada no Bootcamp Potência Tech Angular Developer;

Atualmente ela só mostra os pokemons da primera geração.

##Como mostrar mais pokemons?

Baixe o projeto e vá no arquivo main.js, nele você encontrará uma variável com o nome maxRecords que terá o valor padrão de 151.

const maxRecords = 151;

Com isso, Você pode manipular esse número, fazendo com que você possa pesquisar mais ou menos pokemons, 
lembre que se tem que um limite de pokemons existentes na PokeAPI.

Falando em limite as variaveis limit e offset, são respectivamente o número de pokemons que aparece 
por pesquisa e o ponto de onde iniciará a sua pesquisa, por exemplo, a partir de qual pokemon você começará pesquisar

const limit = 10;
let offset = 0;
