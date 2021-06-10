# Sequencia de comandos e verificações no dia a dia

### Veriricar branch ativa
`git branch`

### Verificar com equipe se enviaram modificações na branch que vai trabalhar ou na branc principal (main, master)
### Se sim, atualizar repositorio local
`git pull origin <nome branch ativa>` - atualizar branch ativa com branch do repositorio remota

`git pull origin <main ou master>`  - atualizar branch ativa local com a principal remota

## Começar os trabalhos
### Verificar se vai trabalhar em uma branch já existente ou precisa criar uma nova (nova área de modificação no projeto)
`git branch`  - lista branchs locais e verifica branch ativa

`git checkout <nome branch>` - ativa branch desejada

`git checkout -b <nome nova branch>` - cria nova branch e ativa

### Finalizar os trabalhos
`git status` - verificar arquivos modificados

`git add .` ou `git add /<nome arquivo>`  -  adicionar arquivos modificados

`git commit -m "mensagem com descricao das informacoes"` - commit das modificações com mensagem descritiva

`git push origin <nome da branch>`
