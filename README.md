## git init
inicializar repo git

## git status
status atual projeto no git

## git add [nomeArquivo]
adiciona o arquivo para o proximo commit

## git add .
adiciona o conjunto de arquivos modificados desde o ultimo commit.

## git commit [nomeArquivo] -m "mensagem do commit"
armazenar no repositorio local o arquivo especificado

## git commit -m "msg do commit"
armazena o conjunto de arquivos modificados desde o ultimo commit.

## git branch -M [nomeBranch]
cria a branch solicitada localmente

## git remote add origin https://github.com/repicco/curso_github.git
vincular nosso repo local com o github

## git push -u origin main
enviando a branch local para o remoto do git

## git pull
receber os dados do remoto do git para a branch local

## git clone [caminhoRepo]
executa a copia do repositorio remoto para a maquina local com uma pasta principal representando o diretorio.

## git clone [caminhoRepo] .
executa a copia do repo remoto para local, desestruturando os arquivos no caminho solicitado, sem criar uma pasta raiz

## git log
exibe os commits em ordem cronologica, para sair aperte a tecla Q

## git checkout [nomeArquivo]
volta a versao do arquivo remoto

## arquivo .gitignore
podemos adicionar os arquivos que não devem ser mapeados pelo git.
padrão: pasta [/pasta] arquivo [nomeArquivo] ou [/caminho/nomeArquivo]

## git reset --hard origin/main
resgatar todos os arquivos da branch remota removendo as mudanças locais.

## git branch
exibe as branchs do projeto

## git branch [nomeBranch]
criar branch

## git checkout [nomeBranch]
acessar outras branchs

## git checkout -b [nomeBranch]
cria uma nova branch e já acessa a branch criada.

## git branch -d [nomeBranch]
deletar uma branch

## git stash
armazena as mudanças feitas em uma posição x retornando [id]

## git stash list
retorna as stashs criadas na branch em questão

## git stash show -p [id]
exibe as mudanças em determinada stash

## git stash apply [id]
retorna os dados da stash selecionada.