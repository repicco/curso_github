### -= Comandos Terminal =-

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

## git push -u origin [branch]
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

## git merge [branch]
mescla a branch em checkout com a solicitada

## git stash
armazena as mudanças feitas em uma posição x retornando [id]

## git stash list
retorna as stashs criadas na branch em questão

## git stash show -p [id]
exibe as mudanças em determinada stash

## git stash apply [id]
retorna os dados da stash selecionada.

## git tag -a [nomeTag] -m "comentario"
cria uma nova tag

## git tag
verifica tags existentes

## git show [nomeTag]
mostra as mudanças da tag

## git checkout [nomeTag]
acessa a tag

## git push origin [nomeTag]
envia a tag solicitada

## git push origin --tags
envia todas as tags

## git fetch -a
busca as branchs localizadas em projetos paralelos do git no ambiente remoto

## git gc
Efetua uma limpeza de temporarios do Git para aumentar a performance entre pull e push

## git shortlog
Log dos commits

## git diff
Valida a branch atual com o que existe na origem do git

## git diff [branch]
Efetua o diff em uma branch especifica

## git diff HEAD: [nomeArquivo] ou [/pasta/arquivo]
efetua o diff em um arquivo especifico

## git reflog
exibe log completo dos commits de forma comprimida com padrão de até 30 dias


### -= Website Git =-

## Issue
Abrir tarefa para novas funcionalidades ou bugs:
No git em new issues > criar a issue com nome e descrição > marcar um dev e informar a label > executar a correção e pontuar as mudanças > fechar issue.

Podemos gerar labels especificas para cada tipo de issue:
Em issues > labels > Edit ou New label

Podemos gerar os Pull Requests em branchs paralelas a Main/Master e após autorizados por alguem irá se mergear automaticamente.