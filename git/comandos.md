# Comandos básicos

### Baixar repositório remoto
`git clone <endereco-repositorio>`

### Checar branch ativa
`git branch`

### Checar status do projeto (modificações realizadas)
`git status`

### Adicionar modificações
`git add .`   - adiciona todas as modigicações

`git add /<nome arquivo>`  - adicionar modigicação específica

### Commit das modificações
`git commit -m "descricao das modificacoes"`

### Enviar modificações
`git push origin <nome da branch>`

### Atualizar repositorio local
`git pull origin <nome da branch>`

### Criar branch
`git branch <nome da branch>`

### Mudar de branch
`git checkout <nome da branch>`

### Merge
`git merge <nome da branch>`

### Buscar lista de branch do repositorio remoto
`git ls-remote origin`

### Trazer branch remota para repositorio local
`git branch <local-branch> <remote-repository>/<remote-branch>`


### Quando precisa iniciar um repositório local
`git pull origin master --allow-unrelated-histories`
