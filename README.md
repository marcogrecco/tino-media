# tino-media

Imagens públicas dos posts do Tino (@tinodobrasil), geradas pelo
[tino-pipeline](https://github.com/marcogrecco/tino-pipeline).

Este repositório é público só porque a Graph API do Instagram exige uma URL
pública pra buscar a imagem na hora de criar o post (`image_url` em
`POST /{ig-user-id}/media`). O conteúdo aqui é sempre o mesmo que já está
publicado publicamente no Instagram — nada secreto fica aqui.

Estrutura: `posts/<data>/<arquivo>.jpg`. As URLs raw do GitHub
(`raw.githubusercontent.com/marcogrecco/tino-media/<branch>/posts/...`) são
o que o publisher passa pra API.
