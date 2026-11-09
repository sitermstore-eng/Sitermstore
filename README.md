# RM Store · Catálogo

Site estático (um `index.html`) com catálogo de tênis e pedido finalizado no WhatsApp.

## Editar produtos
Abra `index.html` e procure **CONFIGURAÇÃO DA LOJA**. Cada produto tem:
- `nome`, `marca`, `cor`, `preco`
- `sizes`: numerações vendidas · `off`: numerações esgotadas
- `foto`: caminho da imagem, ex. `"fotos/nb530.jpg"` (vazio = ilustração)
- `novo: true` mostra a etiqueta "Novidade"

O número do WhatsApp fica em `WHATSAPP` (só dígitos, com 55 + DDD).

## Fotos
Coloque as imagens na pasta `fotos/` (de preferência quadradas, ~1000px, .jpg ou .webp) e preencha o campo `foto` do produto.

## Publicar
1. Suba esta pasta para um repositório no GitHub.
2. Na hospedagem (Vercel, Netlify ou Cloudflare Pages), importe o repositório. Não precisa de build: framework "Other", pasta de saída `/`.
3. Todo `git push` publica a nova versão.
4. Domínio: registre o `.com.br` no Registro.br e aponte o DNS conforme a hospedagem indicar.
