### ABRIR EDITOR DO GIT CONFIG

```
git config --global --edit
```

### Configurar o editor para o git config

```
git config --global core.editor code
```

###

```
git config --global init.defaultBranch main
```

### Inicializa o git em uma pasta local

```
git init
```

### Prepara as alterações para próximo commit

```
git add [options]
```

### Salva um snapshot das alterações preparadas no repositório Git, criando um ponto de verificação no histórico do projeto

```
git commit [options]
```

#### Estrutura de como fazer o commit semântico

**<type>[optional scope]: <description>**

### Envia as alterações salvas no commit

```
git push [options]
```

### Semantic Commit

**feat**: Uma nova funcionalidade.
**fix**: Uma correção de bug.
**docs**: Alterações na documentação.
**style**: Formatação, correção de ponto e vírgulas ausentes, etc.; sem alterações no código.
**refactor**: Uma alteração no código que não corrige um bug nem adiciona uma nova funcionalidade.
**perf**: Uma alteração no código que melhora o desempenho.
**test**: Adição de testes ausentes ou correção de testes existentes.
**chore**: Alterações no processo de compilação ou em ferramentas e bibliotecas auxiliares, como a geração de documentação.

### Busca os arquivos do repositório remoto para a máquina local

```
git pull [options]
```

### Cria um clone do repositório remoto na sua máquina local

```
git clone [link repositório]
```

### CASO NAO TENHO REPOSITORIO GIT LOCAL

```
echo "# <nome-projeto>" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin <link-projeto-github>
git push -u origin main
```

### CASO JÁ TENHAREPOSITÓRIO GIT LOCAL

```
git remote add origin <link-projeto-github>
git branch -M main
git push -u origin main
```
