# Comandos Git

## Inicialização

### git init

Inicializa um repositório Git.

Exemplo 1:
```bash
git init
```

Exemplo 2:
```bash
git init projeto
```

---

### git clone

Clona um repositório remoto.

Exemplo 1:
```bash
git clone https://github.com/user/repositorio.git
```

Exemplo 2:
```bash
git clone URL_DO_REPOSITORIO
```

---

## Status e Histórico

### git status

Mostra o estado atual do repositório.

Exemplo 1:
```bash
git status
```

Exemplo 2:
```bash
git status -s
```

---

### git log

Mostra histórico de commits.

Exemplo 1:
```bash
git log
```

Exemplo 2:
```bash
git log --oneline
```

---

### git diff

Mostra diferenças entre arquivos.

Exemplo 1:
```bash
git diff
```

Exemplo 2:
```bash
git diff main develop
```

---

## Versionamento

### git add

Adiciona arquivos para commit.

Exemplo 1:
```bash
git add .
```

Exemplo 2:
```bash
git add README.md
```

---

### git commit

Cria um commit.

Exemplo 1:
```bash
git commit -m "feat: adiciona login"
```

Exemplo 2:
```bash
git commit -m "fix: corrige bug"
```

---

### git restore

Restaura alterações.

Exemplo 1:
```bash
git restore arquivo.txt
```

Exemplo 2:
```bash
git restore .
```

---

### git rm

Remove arquivos.

Exemplo 1:
```bash
git rm arquivo.txt
```

Exemplo 2:
```bash
git rm -r pasta
```

---

## Branches

### git branch

Gerencia branches.

Exemplo 1:
```bash
git branch
```

Exemplo 2:
```bash
git branch develop
```

---

### git checkout

Troca de branch.

Exemplo 1:
```bash
git checkout develop
```

Exemplo 2:
```bash
git checkout -b feature/login
```

---

### git switch

Alternativa moderna ao checkout.

Exemplo 1:
```bash
git switch develop
```

Exemplo 2:
```bash
git switch -c feature/login
```

---

### git merge

Realiza merge entre branches.

Exemplo 1:
```bash
git merge develop
```

Exemplo 2:
```bash
git merge feature/login
```

---

## Repositório Remoto

### git remote

Gerencia repositórios remotos.

Exemplo 1:
```bash
git remote -v
```

Exemplo 2:
```bash
git remote add origin URL
```

---

### git push

Envia commits ao remoto.

Exemplo 1:
```bash
git push origin main
```

Exemplo 2:
```bash
git push -u origin develop
```

---

### git pull

Baixa alterações remotas.

Exemplo 1:
```bash
git pull origin main
```

Exemplo 2:
```bash
git pull origin develop
```

---

### git fetch

Busca atualizações remotas.

Exemplo 1:
```bash
git fetch
```

Exemplo 2:
```bash
git fetch origin
```

---

## GitFlow

### git rebase

Reorganiza commits.

Exemplo 1:
```bash
git rebase develop
```

Exemplo 2:
```bash
git rebase main
```

---

### git tag

Cria tags de versão.

Exemplo 1:
```bash
git tag v1.0.0
```

Exemplo 2:
```bash
git tag -a v1.0.1 -m "Hotfix"
```

---

### git stash

Salva alterações temporariamente.

Exemplo 1:
```bash
git stash
```

Exemplo 2:
```bash
git stash pop
```