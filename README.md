# avaliacao-jp
Avaliação Jovem Programador

# git init
Inicia um novo diretorio git aonde vai salvar todos os arquivos de forma compactada com o hash SHA-1.

# git status
Mostra o estado atual do diretorio. Todos os arquivos modificados, nocos arquivos e arquivos prontos para commit.

# git add nome-do-arquivo ou .
Prepara os arquivos selecionados para o commit. 

# git rm --cached nome-arquivo
Remove os aquivos preparados para commit.

# git branch
Mostra todas as branchs locais, se colocar git branch -r mostra só as remotas, e se for git branch -a mostra tanto as locais quanto as remotas

# git checkout branch-name
Muda para a branch selecionada. Caso for colocado git checkout -b branch-name além de criar ela muda pra ela também. E caso for usado o git branch -D branch-name para excluir a branch selecionada

# git commit -m "descição"
Faz o commit das mudanças e acresenta uma descrição das mudanças. Caso precise desfazer o último commit git reset --soft HEAD~1

# git merge branch-name
Faz o merge da branch atual na branch selecionada

# git push
Envia os commits realizados no diretorio local para o remoto.

# git revert hash-do-commit
cria um novo commit que desfaz as mudanças do git especificado.

# git fetch
Atualiza no diretorio local as alterações realizadas no diretorios remoto sem mesclar.

# git pull
Atualiza o diretorio local e mescla com a branch atual.

# git reset --hard hash-do-commit
Reverte a branch local para o estado anterior ao git pull

# Está é a minha garantia que esté codigo foi feito por mim
01010100 01101000 01101011 01101100 00100000 01101001 01100110 00100000 01010000 01101000 01110101