*Git course is a text repository*

comandos chave:
#add--commit--git clone
#remote add--git push--fork--pull request

git commit -m "comentário"- envia mudanças para o repositorio local
hash: número do commit

git branch -D NomeDoBranch --> Deleta o Branch

git log:
varias informações podem ser buscadas pelo git log
--> git log --decorate
--> git log --author
-->git shortlog
--> git shortlog -sn
-->git log --graph

------------------
git diff :)
serve para ver as ultimas atualizações de código antes do commit.

git show :o
mostra as mudanças após o commit.

git push: 
envia os arquivos comitados para o diretorio remoto

git checkout NomeDoArquivo: apaga as últimas mudanças do arquivo no estado modified
git checkout NomeDaBranch: muda de branch

git checkout -b NomeBranch: cria nova branch

git pull:  incorpora mudanças de um repositório remoto para o branch local;

git remote add qualquernome URL:
adiciona um repositório remoto no servidor

git push -u qualquernome master
(adiciona os arquivos ao repositório remoto)

git reset HEAD NomeDoAquivo: volta o arquivo pro estado anterior;