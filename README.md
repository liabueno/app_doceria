# app
TCC do grupo: Chaiane, Júlia, Vicktória e Yasmin. 
Aplicativo para manutenção do cardápio digital.
Onde os produtos são adicionados, excluídos, editados e pesquisados.

Requer node.js

PARA USAR O APP PELO CÓDIGO FONTE:
No terminal faça um cd app
Já dentro da pasta app, fora da pasta src
Digite no terminal:
npm i -> para instalar as dependências do projeto
npm start -> para rodar

PARA CRIAR O SETUP:
Já na pasta app
Digite no terminal:
npm install electron-builder --save-dev -> para instalar a biblioteca que construirá o app
npx electron-builder --win -> para construir o app
Com a pasta dist criada, acesse pelo explorador de arquivos 
Localize o arquivo nomeado "app Setup 1.0.0" e o execute