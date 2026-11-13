# Apparence Odontologia: site

Landing page da clínica Apparence Odontologia (Rua Clélia, 2208, cj 602, Lapa, São Paulo – SP).
Site estático: não precisa de build nem de servidor.

## Estrutura

- `index.html`: a página inteira (HTML e CSS)
- `images/`: fotos e logo
- `CNAME`: domínio `apparenceodonto.com.br` (usado pelo GitHub Pages)
- `robots.txt` e `sitemap.xml`: para o Google

## Publicar com GitHub Pages

1. No repositório, abra **Settings → Pages**.
2. Em **Build and deployment**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. Em **Custom domain**, confirme `apparenceodonto.com.br` e ative **Enforce HTTPS** quando liberar.

## Apontar o domínio (no Registro.br ou onde o domínio estiver)

Crie estes registros DNS:

| Tipo  | Nome | Valor |
|-------|------|-------|
| A     | @    | 185.199.108.153 |
| A     | @    | 185.199.109.153 |
| A     | @    | 185.199.110.153 |
| A     | @    | 185.199.111.153 |
| CNAME | www  | `SEU-USUARIO.github.io` |

A propagação do DNS pode levar de alguns minutos a algumas horas.

## Como editar

- Telefone e link do WhatsApp: procure por `wa.me/5511960717526` em `index.html`.
- Instagram: procure por `aparence_odontologia`.
- Horários e endereço: seções "Onde fica", "Como chegar" e rodapé.
