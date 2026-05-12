# Ethnos Pokémon 🔴


Demo jogável de um jogo de cartas baseado no Ethnos, com temática Pokémon. Desenvolvido como trabalho da disciplina de Gerência de Projetos e Manutenção de Software.

## Sobre o projeto

O Ethnos Pokémon é uma versão simplificada do jogo de tabuleiro Ethnos, onde os jogadores formam bandos de Pokémon por Tipo ou Região para conquistar influência nas 6 regiões do tabuleiro. Esta demo implementa o fluxo completo de um turno em modo hotseat para 2 a 4 jogadores.

## Funcionalidades implementadas

- Deck de 144 cartas gerado automaticamente (12 tipos × 6 regiões × 2)
- Integração com a [PokéAPI](https://pokeapi.co/) para buscar nomes e sprites dos Pokémon
- Fallback offline com pool de Pokémon hardcoded
- Compra de carta (1 ação por turno, regra Ethnos)
- Formação de bando por Tipo ou por Região
- Escolha de líder do bando e aplicação de influência na região correspondente
- Tabuleiro com 6 regiões e controle de influência por jogador
- Suporte hotseat para 2–4 jogadores

## Como executar

Não é necessário instalar nada. Basta abrir o arquivo `src/index.html` diretamente no navegador.

> A primeira execução pode demorar alguns segundos enquanto os dados dos Pokémon são carregados da PokéAPI. As execuções seguintes usam cache local.

## Estrutura do repositório

```
ethnos-pokemon/
├── README.md
├── docs/
│   ├── documento-1a-apresentacao.pdf
│   ├── slides-1a-apresentacao.pdf
└── src/
    └── index.html
```

## Tecnologias utilizadas

- HTML5, CSS3 e JavaScript puro (sem frameworks)
- [PokéAPI](https://pokeapi.co/) — dados e sprites dos Pokémon

## Equipe

| Membro | Responsabilidades |
|--------|-------------------|
| Igor Gama | Documentação, planejamento, EAP, Gantt, análise de riscos |
| Daniel Nery | Desenvolvimento da demo, integração com PokéAPI, criação dos slides |
