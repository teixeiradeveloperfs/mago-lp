MAGO — Página de captura (Telegram)

Arquivos:
- index.html: página principal, pronta para upload
- assets/mago-logo-transparent.png: arte da marca com fundo transparente, usada na página
- assets/mago-logo.png: arquivo original da marca

INTEGRAÇÃO TELETOOLS:
- O script embed.js usa o projeto cap-2a98 e o endpoint https://api.teletoolsbr.com/embed.
- Os dois botões usam data-tg-track e data-tg-utm="origem-1".
- O link do Telegram é gerado pelo TeleTools ao clicar. Confirme no painel do projeto
  que o destino do canal está configurado antes de publicar.

COMO HOSPEDAR NO CPANEL:
1. Acesse Gerenciador de Arquivos.
2. Entre na pasta public_html do domínio (ou pasta do subdomínio).
3. Envie index.html e a pasta assets mantendo a mesma estrutura.
4. Para publicar num slug (ex.: /mago), crie uma pasta mago dentro de public_html e envie os arquivos nessa pasta.
5. Acesse o endereço publicado. Se desejar, configure SSL/HTTPS.

Página estática responsiva. O script externo do TeleTools faz rastreamento
e gera o link de convite do canal.
Ajuste as regras legais e promocionais ao país de destino antes da publicação.
