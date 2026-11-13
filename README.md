# Laminário de Mama

Visualizador web de lâminas de histologia e patologia mamária, publicado com GitHub Pages: mama normal, lesões benignas, carcinomas in situ e invasivos, imuno-histoquímica (RE, Ki-67, HER2, E-caderina) e FISH HER2/CEP17, com roteiros guiados, explicações, casos clínicos, quiz e anotações.

O app é uma página HTML única (`index.html`). O visualizador usa [OpenSeadragon](https://openseadragon.github.io/) (carregado do cdnjs) e as lâminas desta versão são geradas por computador no próprio navegador, só para demonstração.

## Como publicar

Settings → Pages → *Build and deployment*: **Deploy from a branch**, branch `main`, pasta `/ (root)`.

## Observações

- As anotações ficam salvas apenas no navegador de quem as fez (localStorage).
- Os textos seguem a OMS (5ª ed.) e as diretrizes ASCO/CAP e devem ser revisados pela docente responsável.
