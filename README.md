# Aprendendo GIT

Rrepositório criado para expor os principais comandos para quem quiser usar a ferramenta de versionamento GIT.

###  Comandos :
####  git-config : 
    Obtém e define os repositórios ou as opções globais.

#### git config --global user.name "seuNome" :
    Para configurar nome de usuario
#### git config --global user.email "seuEmail" :
    Para configurar email do usuario
#### git config --global user.name/user.email :
    Para exibir informação de usuario


#### git init :
    Cria um repositório vazio para o Git ou reinicializa um repositório já existente.

#### git status :
    Exiba a condição atual da árvore de trabalho.
#### git add <nomeArquivo> :
    Adiciona o conteúdo do arquivo ao índice.
#### git add . :
    Adiciona o conteúdo de todos os arquivos modificados ou criados ao índice.
#### git -rm
    Remove os arquivos da árvore de trabalho e do índice.
#### git -rm --cached <nomeArquivo> :
    Utilize esta opção para desestabilizar e remover os caminhos do índice apenas.
    Os arquivos da árvore de trabalho, modificados ou não, serão deixados em paz.
#### git commit :
    Grava as alterações feitas no repositório.
#### git commit -m "msg" :
    Usa a <msg> como a mensagem de commit. Caso múltiplas opções -m sejam usadas,
    o seu conteúdo será disposto em parágrafos separados.
#### git clone :
    Clona um repositório em um novo diretório.
#### git remote -v :
    Exibe o origin.
#### git push :
    Atualiza as refs remotas junto com os objetos associados a el.

# Gerenciamento de Branchs
#### git branch :
    Lista, cria ou exclui ramificações.
    Exibesua branch atual.
#### git branch <nomeBranch> :
    Cria nova branch.
#### git checkout <nomeBranch> :
    Permite navegar entre as branchs.
#### git checkout -b <nomeBranch> :
    Alem de crear uma nova branch,realiza o checkout diretamente.
#### git merge <nomeBranch> :
    Une dois ou mais históricos de desenvolvimento.
    É feito a partir da branch de destino.

# Outras funcionalidades :
#### git stash (salva alterações sem commit)
#### git stash pop (restaura alterações salvas)
#### git stash list (list stashes)
#### git stash pop stash@{1} (aplica stash especifico)
## Autores
- Giuliano García: [@gdg89](https://github.com/gdg89) 
