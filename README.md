# Site-de-vendas-# SkinShop CS — Site de demonstração

Site estático para vender skins de Counter-Strike. Feito com HTML/CSS/JavaScript (front-end) — pronto para publicar no GitHub Pages.

## Como usar

1. Crie um repositório no GitHub (por exemplo: `minha-loja-skins`).
2. Faça upload dos arquivos: `index.html`, `style.css`, `script.js`, `products.json`, `README.md`.
3. No GitHub, vá em **Settings > Pages** e publique a branch `main` (ou `master`) na pasta `/ (root)`.
4. O site ficará disponível em `https://<seu-usuario>.github.io/<nome-do-repo>/`.

## Como adicionar/editar produtos
Edite `products.json` e atualize o campo `image` com a URL da imagem de cada skin (preferencialmente imagens hospedadas em um servidor próprio ou CDN).

Formato:
```json
{
  "id": "ak-redline",
  "name": "AK-47 | Redline",
  "rarity": "Classified",
  "price": 72.5,
  "image": "https://meusite.com/imgs/ak-redline.jpg",
  "desc": "Descrição"
}
