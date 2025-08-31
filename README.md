# Trilha Javascript - Pokedex

Uma Pokedex interativa que lista os primeiros 151 Pokémons, permitindo carregar mais Pokémons em blocos de 10. Este projeto é construído com HTML, CSS e JavaScript puro, consumindo dados da PokéAPI.

## Funcionalidades

- Listagem dos 151 primeiros Pokémons.
- Carregamento incremental com o botão Load More.
- Exibição do número, nome, tipos e imagem de cada Pokémon.
- Layout responsivo e estilizado com CSS moderno.

## Tecnologias Utilizadas

- HTML5
- CSS3 (com Normalize e fonte Roboto)
- JavaScript (ES6+)
- API: PokéAPI

## Como Executar

1. Clone o repositório:

 ```bash
    git clone <URL_DO_REPOSITORIO>
```
2. Abra o arquivo index.html em seu navegador.

Pronto! Você verá a lista de Pokémons e poderá carregar mais usando o botão Load More.

## Estrutura do Projeto
```bash
├── assets
│   ├── css
│   │   ├── global.css
│   │   └── pokedex.css
│   └── js
│       ├── main.js
│       ├── poke-api.js
│       └── pokemon-model.js
├── index.html
└── README.md
```
## Layout

O layout exibe cada Pokémon em um card com:

- Número e nome
- Tipos
- Imagem

O estilo utiliza cores diferentes baseadas no tipo do Pokémon.

📝 Observações

- O botão Load More desaparece automaticamente quando todos os 151 Pokémons são carregados.
- O projeto é totalmente estático e não necessita de backend.
