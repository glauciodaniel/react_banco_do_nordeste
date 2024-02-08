#Introdução sobre GIT

GIT - é um controle de versionamento

Outros antigos, CVS, SVN ou subversion. Em programação sempre existiu controle de versão.

Linus Torvald - criador do Linux, criou o projeto GIT.

300 programadores voluntário trabalhando no Kernel do Linux. Um sobrescrever outro, um quebrar uma versão do outro.


2005 - 2009 - FTP upload dos arquivos do site.

Github - é um site. Rede Social para programadores. Também é um repositório público/privado. É uma grande biblioteca. 

Gitlab
Bitbucket

-------------------------------------------------------

git init - primeiro comando.
   .git - pasta oculta
   .gitignore - arquivo oculto, que diz quais pastas e arquivos eu não devo me preocupar. Ex. node_modules

git config local user.name = 'Glaucio Daniel'
git config local user.email = 'glauciodaniel@gmail.com'
-------------------------------------------------------

terminou um trabalho. Add, Commit. O git add é como um carrinho de compras no supermercado.
git add grid.html grid.css

git add --all
git add .

git add -A
-------------------------------------------------------

git commit -m"Trabalhando com grid layout criamos o grid.css e o grid.html"
-------------------------------------------------------
git add --all e git commit -m""
-------------------------------------------------------
Ligando o meu repositório(pasta de trabalho) local(na minha máquina) com o remoto(gitlab ou github ou bitbucket)

Listar se eu já estou conectado a algum lugar
git remote 

Quero saber detalhes sobre esse local
git remote -v

git remote add origin https://gitlab.com/glauciodaniel/react232104.git

git remote remove origin 

git remote
 origin

git remote -v
 origin https://gitlab.com/glauciodaniel/react232104.git

-------------------------------------------------------
Baixe ou faça o download de tudo que eu não tenho no repositório remoto para minha máquina.

git pull origin master
 * already up to date. - Não tem nada pra alterar. Você já está atualizado.

git add --all
git commit -m"Mensagem descritiva"

Estou enviando para o servidor.
git push origin master
-------------------------------------------------------
branch - versões de um mesmo repositório - master ou main é o principal. Mas eu posso ter outros branch.

integracao - é o nome de um branch.


index.html 30 linhas - local
index.html 60 linhas - remoto

U - untracked - não está usando o git. Não rastreado.
A - new file. File add. Git add.
M - Modify. novas linhas gera a barrinha verde. Linhas que podem gerar conflito barrinha azul.
! - vermelha. Tem que abrir o arquivo, 
 >> ENTRADA - Aceitar entrada  | Rejeitar ou manter atual
  git add --all
  git commit -m"Resolvi o conflito do arquivo tal"
-------------------------------------------------------

Clonar um repositório já existente numa nova pasta local
git clone https://gitlab.com/glauciodaniel/react232104.git

Eu já tenho algo localmente e quero fazer uma ligação com uma pasta ou repositório remoto.
git remote add azure-dev-mode https://....

AWS
www.njsharingnetwork.org

Créditos no Azure da Microsoft. MVP
ip 29.000.000.999


git remote -v

aws-production
azure-dev-mode

-------------------------------------------------------