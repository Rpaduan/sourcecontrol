git init = inicia o Git no projeto atual 
git status = mostra o status atual dos arquivos
git add . = adiciona todos os arquivos para a área de preparação (staging)
git add nome-do-arquivo = adiciona apenas um arquivo específico
git commit -m "" = cria um commit com uma descrição das alterações
git push -u origin main = enviar os artquivos para o main do github a primeira vez
git push = enviar os arquivos nas demais vezes
git pull = baixa as alterações do GitHub para a máquina local
git clone URL_DO_REPOSITORIO = Faz uma cópia de um repositório existente para o computador
.gitignore = arquivo para ignorar arquivos que não desejo enviar no momento 
git rm -r --cached . = reseta o cash dos arquivos, para poder add um arquivo, ou pasta já comitado no arquivo .gitignore
git log = mostra o histórico dos commits
git diff = mostra alterações feitas antes do commit
git remote -v = mostra repositórios remotos configurados
git branch = mostra em qual branch você está

git status
git add .
git commit -m "mensagem"
git push

# primeira vez
git init
git remote add origin URL
git push -u origin main

# baixar projeto
git clone URL

# atualizar projeto
git pull

# ignorar arquivos
.gitignore

# aplicar alterações do .gitignore
git rm -r --cached .
git add .
git commit -m "Atualiza .gitignore"
git push