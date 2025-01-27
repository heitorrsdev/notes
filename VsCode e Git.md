# **VsCode e Git**

Ctrl + / comenta a linha

## **Para iniciar um repositório:**
nvm i && nvm use (dps da primeira inicialização, rode apenas "nvm use" neste passo)

npm i

npm run dev

## **Para fazer commit/pull request:**
npx git-cz

git push origin {nome-branch}

Fazer o pull request

Pedir review no slack

Colocar o link do pr nos comentários do card

Marcar devbox

Mover o card para a próxima coluna no FluxControl

## **Para executar:**
npm run dev

## **Para editar um commit:**
#### Meu modo:
Undo last commit

git stage .

npx git-cz

git push origin [nome-branch] -f

#### Modo do Jorge:
git stage .

git commit --amend

git push origin master [nome-branch] -f
