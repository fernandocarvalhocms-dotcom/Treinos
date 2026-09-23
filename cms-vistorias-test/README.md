# CMS Vistorias — teste web

Protótipo de inspeção visual para galpões e áreas externas.

## Vercel
Ao importar o repositório **Treinos** no Vercel, configure:

- **Project Name:** cms-vistorias-test
- **Root Directory:** `cms-vistorias-test`

Para análise por IA, adicione a variável de ambiente `OPENAI_API_KEY`.
Opcionalmente, defina `CMS_ACCESS_TOKEN` para exigir um código de acesso.

O sistema:
- importa ZIP de fotos;
- ignora arquivos auxiliares do macOS;
- agrupa fotos em blocos de até 4 imagens;
- analisa patologias/condições visualmente;
- permite revisar e editar;
- gera relatório A4 com 6 fotos por página.
