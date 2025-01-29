# **VsCode e Git**

Ctrl + / comenta a linha

## **Para iniciar um repositório:**
nvm i && nvm use (dps da primeira inicialização, rode apenas "nvm use" neste passo)

npm i

## **Para fazer commit/pull request:**
git stage .

npx git-cz

git push origin {nome-branch}

git fetch && git checkout master -f && git pull origin master --rebase

Fazer o pull request

Pedir review no slack

Colocar o link do pr nos comentários do card

Marcar devbox

Mover o card para a próxima coluna no FluxControl

## **Para executar:**
npm run dev

## **Para editar um commit:**
git stage .

git commit --amend

git push origin master [nome-branch] -f

git fetch && git checkout master -f && git pull origin master --rebase
