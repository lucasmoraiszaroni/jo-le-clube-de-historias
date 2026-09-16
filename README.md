# Jô-Lê — Clube de histórias

Base inicial de um site estático em português, com página provisória e layout responsivo.

## Estrutura
- public/index.html: página inicial, estilos e favicon.
- wrangler.jsonc: configuração de publicação na Cloudflare Workers com Static Assets.

## Desenvolvimento
Abra public/index.html no navegador para visualizar a página.
Com Node.js instalado, execute `npx wrangler dev` para iniciar o servidor local.
Para publicar na conta autenticada da Cloudflare, execute `npx wrangler deploy`.
Documentação: https://developers.cloudflare.com/workers/static-assets/

## Repositório
https://github.com/lucasmoraiszaroni/jo-le-clube-de-historias

Repositório privado, com branch principal main.

## Próximas etapas
- Concluir a publicação na Cloudflare e conectar a publicação automática ao GitHub.
- Definir conteúdo final e domínio com o proprietário.

Nenhuma credencial deve ser incluída no repositório.
