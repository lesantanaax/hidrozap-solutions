#hidrozap-solutions
git init
- iniciar um novo projeto com git

git add <nome-arquivo>/.
- add os arquivos que estão prontos para serem comitados

git commit -m"mensagem commit"
- commit os arquivos no histórico

git log 
- mostra os ultimos commits, log de alterações 

git status
- mostra como está o estado da nossas ramificações

git diff 
- mostra o que foi alterado
- o que tem de alteração na ramificação

git merge
- merge de ramificações, mescla ramificações

git branch
- mostra a branch atual

git branch -b <nome-da-branch>
- cria uma branch a partir do histórico da branch atual que estamos

git checkout <nome-da-branch>
- muda para essa branch

git checkout -b <nome-da-branch>
- crua uma nova branch a partir da branch atual que estamos

git remote add <nome> <url>
- add um novo repositorio remoto

git push <nome> <nome-da-branch>
-  manda as alterações locais para repositorio remoto, para cada branch

git pull <nome> <nome-da-branch>
- pega as alterações do repositorio remoto e joga para nossa maquina

git fetch
- atualiza nosso historico local de acordo com historico salvo no repositorio remoto
- sincronização do local com remoto
