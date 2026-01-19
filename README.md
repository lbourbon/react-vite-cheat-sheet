# react-vite-cheat-sheet
react-vite-cheat-sheet

## INICIAR PROJETO

NO TERMINAL:
<code>
npm create vite@latest
 > project name: <escolher nome>
 > framework: <react>
 > variant: <JS>

cd <nome do projeto>
npm install
npm run dev
</code>
<code>
firebase init

<h3>CUIDADO!! AO INICIAR, O FIREBASE PODE JOGAR PARA UM PROJETO JÁ EXISTENTE!!!</h3>he>
<code>firebase use --clear
firebase use --add
</code> 
PARA ESCOLHER UM NOVO PROJETO

</code>
public: dist !!!!!!!
adicionar ao index.html na pasta dist:
<code>
<script src="/main.jsx" type="module"></script>
</code>

commit:
<code>
git add .
git commit -m "<message>"
git push
</code>
* projeto recibo já configurado para fazer deploy no firebase automatico
deploy:

DEPLOY BETA:
<code>
npm run build:beta
firebase deploy --only hosting:beta
</code>

DEPLOY NORMAL:
<code>
npm run build
firebase deploy
</code>
