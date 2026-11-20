# Cardoso Pré-Moldados — site

Site institucional de uma página da Cardoso Pré-Moldados (Park Way, Brasília - DF).

- `index.html`: página completa (HTML, CSS e JS no mesmo arquivo, sem build).
- `imagens/`: fotos em WebP otimizadas, `favicon.svg` e `og-cardoso.jpg` (prévia ao compartilhar o link).
- `robots.txt` e `sitemap.xml`: SEO básico.

Publicado na Vercel a partir da branch `main`.

## Fotos

As fotos de produtos e do pátio são da própria Cardoso Pré-Moldados, enviadas pelo cliente, e foram tratadas (cor, contraste, nitidez e enquadramento) sem alterar os produtos:

- `capa-obra`: foto de prédio em alvenaria de blocos de concreto vista de baixo (enviada pelo cliente), usada ao fundo da capa: espelhada, ampliada 4x com Real-ESRGAN, céu suavizado para combinar com o bege e com recortes próprios para computador e celular (`capa-obra-mobile`).
- `catalogo-*`: blocos e canaletas (14 cm e 9 cm; as de 9 cm com resolução aumentada por Real-ESRGAN), bloquetes e cobogó (isolado da foto do pátio, com manchas de ferrugem e sujeira removidas) recortados e montados sobre fundo de estúdio.
- `foto-*`: fotos do pátio usadas na seção da empresa e na galeria.
- `og-cardoso.jpg`: imagem de compartilhamento montada com os recortes.

Duas fotos da galeria vêm do [Unsplash](https://unsplash.com) (Licença Unsplash: uso comercial gratuito, sem necessidade de atribuição):

| Arquivo | Foto original |
| --- | --- |
| g-maquinas | photo-1647735282077-c12699af40be |
| g-concretagem | photo-1651195297119-afc97f14a40d |

As imagens ficam em `https://images.unsplash.com/<id>`.
