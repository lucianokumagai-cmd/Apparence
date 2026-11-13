# Apparence Odontologia: site

Landing page da clínica Apparence Odontologia (Rua Clélia, 2208, conjunto 602, Lapa, São Paulo – SP).
Site estático: HTML e CSS, sem framework e sem build. Não precisa de servidor.

## Estrutura

- `index.html`: a página inteira (HTML e CSS)
- `images/`: logo e fotos já redimensionadas
- `favicon.svg`: ícone da aba do navegador
- `CNAME`: domínio `apparenceodonto.com.br` (usado pelo GitHub Pages)
- `.nojekyll`: diz ao GitHub Pages para publicar os arquivos como estão
- `robots.txt` e `sitemap.xml`: para o Google

## Publicar com GitHub Pages

1. No repositório, abra **Settings → Pages**.
2. Em **Build and deployment → Source**, escolha **Deploy from a branch**.
3. Em **Branch**, escolha `main` e a pasta `/ (root)`. Clique em **Save**.
4. Em **Custom domain**, confirme `apparenceodonto.com.br` e clique em **Save**.
5. Quando o DNS estiver apontado e o GitHub validar o domínio, marque **Enforce HTTPS**.
   O certificado pode levar de alguns minutos a algumas horas para aparecer.

## Apontar o domínio (no Registro.br ou onde o domínio estiver)

Crie estes registros DNS:

| Tipo  | Nome  | Valor                        |
|-------|-------|------------------------------|
| A     | @     | 185.199.108.153              |
| A     | @     | 185.199.109.153              |
| A     | @     | 185.199.110.153              |
| A     | @     | 185.199.111.153              |
| CNAME | www   | `lucianokumagai-cmd.github.io` |

A propagação pode levar de alguns minutos a algumas horas.
Para conferir, use `dig apparenceodonto.com.br +short` ou o site dnschecker.org.

## Como editar

- Telefone e link do WhatsApp: procure por `wa.me/5511960717526` em `index.html`.
- Instagram: procure por `aparence_odontologia`.
- Horários e endereço: seções da faixa de informações, "Como chegar" e rodapé.
- Fotos: troque os arquivos em `images/` mantendo o mesmo nome (máximo de 960 px de largura; logo, 700 px).

## Observações

- Os textos seguem as regras de publicidade odontológica do CFO: sem preços, sem promessa de resultado, sem antes e depois.
- O CEP e as coordenadas não foram incluídos nos dados estruturados porque não foram informados.
