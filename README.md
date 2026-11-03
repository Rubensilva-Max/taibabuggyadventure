# TaibaBuggyAdventure — site cinematográfico

Site institucional estático em português, com HTML, CSS e JavaScript puro.

## Como visualizar
Abra `index.html` no navegador. As fontes e fotografias são carregadas da internet, portanto precisam de conexão.

## Como publicar
1. Extraia o ZIP.
2. Envie os arquivos e a pasta `assets` (reservada para suas imagens) para a raiz do repositório GitHub.
3. Na Vercel, importe o repositório.
4. Para este projeto estático, use:
   - Framework Preset: Other
   - Build Command: deixe vazio
   - Output Directory: `.`
5. Faça o deploy.

## Personalização
- O botão do WhatsApp já está configurado para o contato informado anteriormente.
- As três fotografias enviadas foram recortadas da imagem de referência e salvas localmente em `assets/`. O site usa esses arquivos locais. Para obter qualidade máxima, envie também os arquivos originais das fotos, se disponíveis.
- As fontes são Knewave, Cormorant Garamond e Montserrat, carregadas pelo Google Fonts.
- O projeto é responsivo e inclui menu mobile, animações de entrada, parallax e respeito à preferência de movimento reduzido do dispositivo.

## Estrutura
- `index.html` — conteúdo e estrutura
- `style.css` — identidade visual e responsividade
- `script.js` — menu, animações e parallax
- `assets/` — pasta para adicionar fotos próprias
