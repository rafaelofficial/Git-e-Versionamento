# Curso Digital: Git e Versionamento

## Lista de Comandos do Git

### Gravando mudanças no repositório:

| Comandos | Descrição |
| -------- | -------- |
| ```git status``` | Verificar em que estado atual que está os arquivos. |
| ```git add <file-name>``` | Adicionar um novo arquivo e/ou novas mudificações e move essas alterações ou arquivos para a àrea de 'Staged Changes'. |
| ```git add .``` e/ou ```git add *``` | Adicionar todas as modificações. |
|

### Salvando modificações no Git:

| Comandos | Descrição |
| -------- | -------- |
| ```git diff``` | Verificar as linhas que foram modificadas. |
| ```git diff --staged``` | Verificar as linhas que foram modificadas, após serem adicionadas na àrea de 'Staged Chandes'. |
| ```git commit -m "<mensagem-do-commit"``` | Salvar o estado/modificações, para poder recuperá-las em um processo futuro ou compartilhar com a equipe. |
|

### Verificando logs e desfazendo alterações:

| Camandos | Descrição |
| -------- | --------- |
| ```git log``` | Verificar o histórico de todos commits. |
| ```git log --oneline``` | Verificar o histórico de todos commits feitos, com apenas a primeira linha do log. [Dev Hints - git log cheatsheet: Mais opções para usar o comando 'git log'](https://devhints.io/git-log) |
| ```git restore``` | Discartar/Remover as alterações adicionadas. |
|```git restore --staged``` | Discartar/Remover as alterações adicionadas, retornando essas modificações e/ou arquivos para a àrea de 'Staged Chandes'. |
| 