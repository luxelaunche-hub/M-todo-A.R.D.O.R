# A.R.D.O.R. — site estático para Vercel

Esta pasta contém o site completo: `index.html`, `styles.css`, fontes locais, logo, capa do ebook e PDF da amostra. Não usa backend nem dependências de build; a raiz do projeto é esta pasta.

## Publicação

Envie/importa esta pasta no Vercel como site estático. O arquivo de entrada é `index.html`. O botão de compra já aponta ao checkout Cakto informado pelo autor.

## Depois de publicar

Como o domínio final ainda não foi definido, os metadados de imagem social e a URL canônica foram deixados de fora, em vez de apontarem para um endereço temporário. Depois de escolher o domínio final, você pode adicionar ao `<head>` do `index.html`:

```html
<link rel="canonical" href="https://SEU-DOMINIO/">
<meta property="og:url" content="https://SEU-DOMINIO/">
<meta property="og:image" content="https://SEU-DOMINIO/assets/capa-ardor.png">
<meta name="twitter:image" content="https://SEU-DOMINIO/assets/capa-ardor.png">
```
