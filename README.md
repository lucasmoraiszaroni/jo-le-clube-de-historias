# Jô-Lê — Clube de histórias

Base inicial de um site estático em português, com página de apresentação provisória e layout responsivo.

## Estrutura
- public/index.html: página inicial, estilos e favicon.
- wrangler.jsonc: configuração de publicação na Cloudflare Workers com Static Assets.

## Desenvolvimento
Abra public/index.html no navegador para visualizar a página.
Com Node.js instalado, execute `npx wrangler dev` para iniciar o servidor local.
Para publicar na conta autenticada da Cloudflare, execute `npx wrangler deploy`.
Documentação: https://developers.cloudflare.com/workers/static-assets/

## Configuração externa pendente
- Criar o repositório GitHub jo-le-clube-de-historias na conta do proprietário.
- Vincular o repositório local ao remoto e enviar o primeiro commit.
- Criar e publicar o projeto na Cloudflare; configurar publicação automática pelo GitHub se disponível.
- Definir conteúdo final e domínio com o proprietário.

Nenhuma credencial deve ser incluída no repositório.
