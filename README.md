# Para a Bibi — pronto para Vercel

Este é um site estático em HTML, CSS e JavaScript, preparado para publicação na Vercel.

## Como publicar
1. Extraia este ZIP no computador.
2. Entre em https://vercel.com/ e faça login.
3. No painel da Vercel, escolha **Add New → Project**. Se for solicitado um repositório Git, você também pode importar esta pasta para um repositório GitHub primeiro.
4. Para implantação por CLI, instale o Node.js e execute:
   ```bash
   npm install -g vercel
   vercel
   ```
   Responda às perguntas da CLI e, para publicar em produção, execute `vercel --prod`.
5. Como o site é estático, não precisa de build command nem de framework. A pasta publicada é `public`.

## Estrutura
- `public/index.html` — página inicial do site.
- `vercel.json` — configuração de saída estática.
- `README.md` — instruções.

Observação: o site usa fontes do Google Fonts; a página continua funcionando se elas não carregarem, com fontes alternativas.
