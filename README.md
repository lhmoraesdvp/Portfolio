# Site — Luis Morais (Estúdio web)

Site de uma página, HTML/CSS/JS puro. Sem build, sem dependências. Só subir.

## Subir na Vercel
1. Crie uma conta em vercel.com (se ainda não tiver).
2. Coloque estes arquivos numa pasta / repositório do GitHub:
   - index.html
   - robots.txt
   - sitemap.xml
   - llms.txt
3. Na Vercel: "Add New Project" → importe o repositório (ou arraste a pasta).
   Framework Preset: **Other**. Não precisa de comando de build.
4. Deploy. Pronto — o site fica num endereço `algumacoisa.vercel.app`.

## O que trocar antes (placeholders)
- **Instagram**: procure `seu_instagram_aqui` no index.html e no llms.txt e troque pelo seu @.
- **E-mail**: procure `seuemail@exemplo.com` no index.html e troque.
- **Domínio**: quando tiver um domínio próprio, troque `https://luismorais.vercel.app/`
  no index.html (canonical, og:url, schema), no robots.txt e no sitemap.xml.
- **Texto do "Sobre"**: ajuste a frase pra ficar com a sua voz.
- **Foto da Lúcia**: hoje o card dela usa um fundo colorido com o nome. Se tiver
  uma imagem boa, troque o `<div class="thumb placeholder">` por um `<img>` como
  está no card da Stop Car.
- **Imagem de compartilhamento (og:image)**: opcional. Crie uma imagem 1200x630
  chamada `og.jpg` na mesma pasta pra aparecer bonito quando o link for compartilhado.

## WhatsApp
Já está configurado com o número (19) 99703-4272. Os botões abrem o WhatsApp com
uma mensagem pronta. Pra mudar o texto, edite a parte depois de `?text=` nos links.

## Por que ele já nasce "encontrável pela IA"
- HTML semântico e limpo, rápido (sem frameworks pesados).
- Dados estruturados (schema.org): ProfessionalService + FAQPage.
- Meta tags completas (SEO + Open Graph + geo).
- robots.txt liberando os crawlers de IA + llms.txt descrevendo o negócio.
É o seu próprio serviço de GEO aplicado em você. Use isso como argumento de venda.
