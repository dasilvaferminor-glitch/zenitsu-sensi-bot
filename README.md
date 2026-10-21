# Zenitsu Sensi — loja com tickets

No Replit, envie os arquivos, configure `DISCORD_TOKEN` em Secrets e opcionalmente `PIX_KEY`, `PIX_NAME` e `STAFF_ROLE_ID`. Rode `npm install` e `npm start`.

Ative Message Content Intent no Discord Developer Portal. Dê ao bot permissões de ver canais, enviar mensagens, ler histórico e gerenciar canais.

Comandos:
- `!ajuda`
- `!addproduto nome | preço | descrição` (admin)
- `!produtos` (lista IDs)
- `!apagarproduto ID` (admin)
- `!painel` (publica painel com botões de compra)
- `!fecharticket` (equipe)

O cliente clica no produto e ganha um ticket privado com instruções Pix e botões para a equipe marcar pagamento confirmado ou pendente. Produtos ficam salvos em `produtos.json`.

Não compartilhe o token do bot. Se já compartilhou um token antigo, redefina-o no Discord Developer Portal e use o novo nos Secrets.
