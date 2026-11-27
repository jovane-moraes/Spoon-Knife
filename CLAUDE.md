# CLAUDE.md

Este arquivo orienta o Claude Code (claude.ai/code) ao trabalhar com o código deste repositório.

## O que é este repositório

Este é o **Spoon-Knife**, o repositório de exemplo oficial do GitHub usado para ensinar fork e pull request. É intencionalmente simples: uma única página HTML estática com uma folha de estilos. Não há sistema de build, gerenciador de pacotes, testes nem código de servidor.

## Comandos

Não há comandos de build, lint ou teste — o site é HTML/CSS estático, sem nenhuma ferramenta. Para visualizar, basta abrir `index.html` direto no navegador (ou servir a pasta com qualquer servidor de arquivos estáticos).

## Estrutura

- `index.html` — a única página. Carrega `styles.css` e exibe uma imagem referenciada como `forkit.gif` (esse arquivo de imagem não está presente no repositório) e um pequeno trecho de texto editável (`Fork me? Fork you, @octocat!`) que o README convida a mudar como prática.
- `styles.css` — estilos para a imagem `#octocat` e o texto `<p>` em `index.html`.
- `README.md` — explica o propósito do repositório: um espaço para praticar fork e pull request no GitHub, com link para o guia de forking do GitHub.

Como o projeto todo são dois arquivos ligados por uma tag `<link>`, não há mais nenhuma nota de arquitetura necessária além dessa.

## Regras

- Responda sempre em português simples.
- Antes de mudar algo, explique o plano.
- Não apague arquivos sem perguntar.
- Não faça commit nem push, o usuário faz.
- Mudanças pequenas, um assunto por vez.
