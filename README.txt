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

PUBLICAÇÃO:
- A LP está hospedada no Dokploy em https://cap.omagocas.online/.
- O Dokploy usa este repositório e a branch main como fonte.
- Um push na main aciona automaticamente o deploy pelo webhook do GitHub.
- Confira o resultado na aba Deployments da aplicação mago-lp no Dokploy.

Página estática responsiva. O script externo do TeleTools faz rastreamento
e gera o link de convite do canal.
Ajuste as regras legais e promocionais ao país de destino antes da publicação.
