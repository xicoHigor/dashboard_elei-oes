# Eleições gerais 2026 — painel

Painel estático e interativo com resultados da Presidência, governos estaduais, Senado e deputados. Não requer instalação de dependências nem etapa de compilação.

## Arquivos

- `index.html` — página principal, pronta para GitHub Pages.
- `widget_eleicoes_2026_fragmento.html` — versão para incorporação em plataformas que permitem HTML, CSS e JavaScript inline.

## Como visualizar

Abra `index.html` em um navegador. As fotos oficiais são carregadas dos servidores do TSE, então precisam de conexão com a internet. O restante do painel e os dados eleitorais estão embutidos no HTML.

## Publicar com GitHub Pages

Envie os arquivos desta pasta para a raiz de um repositório GitHub e configure o GitHub Pages para servir a raiz do branch escolhido. Como o arquivo inicial se chama `index.html`, não é necessário criar uma página de entrada adicional.

## Dados e fontes

Os resultados legislativos foram consultados em 02/11/2026. As fotos e os dados de candidaturas vêm das publicações oficiais do TSE.

- [Resultados oficiais do TSE](https://resultados.tse.jus.br/oficial/app/index.html)
- [Dados abertos do TSE — resultados 2026](https://dadosabertos.tse.jus.br/dataset/resultados-2026)
- [Dados de candidaturas e fotos — TSE](https://dadosabertos.tse.jus.br/dataset/candidatos-2026)

O painel apresenta 54 senadores, 513 deputados federais e 1.059 deputados estaduais/distritais eleitos.