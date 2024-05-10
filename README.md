# Buscador de Cartas de Magic: the Gathering

Este projeto permite buscar cartas de Magic: the Gathering a partir de uma descrição em linguagem natural da arte da carta.

O projeto foi desenvolvido a partir da [imersão Alura+Google](https://cursos.alura.com.br/imersao) sobre o AI Studio e Gemini. A API do Gemini é utilizada para fazer o processamento da entrada e gerar uma consulta adequadamente traduzida à API do Scryfall. O Gemini também foi utilizado para auxiliar no webscraping dos termos válidos para a busca.

## Tecnologias Utilizadas

- Python
- Google Colab
- [Google Gemini API](https://ai.google.dev/gemini-api/docs)
- [Scryfall API](https://scryfall.com/docs/api "Base de dados de cartas de Magic: the Gathering")
- [Tagger Project](https://tagger.scryfall.com/ "Catálogo de tags definido por usuários do site Scryfall")

## Versão 0.1 - Atual

Permite realizar a consulta por texto e apresenta a lista de cartas, com seu link no Scryfall e link da arte.

## TODO

- Busca por imagem
- Interface web
