## INFORMAÇÕES -> STATUS
``` bash
git status  # Exibe as informações do repositório (commits pendentes, pushs, branch tual, etc)
```

## HISTÓRICO -> LOG
``` bash
git log  # Exibe o histórico das modificações
git reflog  # Exibe o histórico das modificações mais brevemente e compactado
```

## ADICIONAR -> ADD
``` bash
git add [arquivo1] [arquivo2]  # Adiciona apenas arquivos especificos
git add .  # Adiciona todos os arquivos modificados
```

## CLONAR -> CLONE
``` bash
git clone [https://github.com/username/repository.git]  # Clona um repositório
```

## COMMITAR -> COMMIT
``` bash
git commit -m "Mensagem"  # Envia um commit, um contexto da feature
```

## ENVIO -> PUSH
``` bash
git push  # Envia as modificações para o GitHub
git push origin --set-upstream [nome da branch]  # Envia modificações quando a branch não existe
```

## RAMIFICAÇÕES -> BRANCHES
``` bash
git branch  # Exibe as branches
git checkout [nome da branch]  # Troca de branch
git branch -D [nome da branch]  # Remove a branch localmente
```

## UNIÃO/MESCLAGEM -> MERGE
``` bash
git merge (nome da branch)  # Mescka duas branchs; Nota: Não pode mesclar uma branch que você já está
```

## PUXAR -> PULL
``` bash
git pull  # Coleta todos os arquivos e pastas que o repositório local não possui
```


---
# OUTROS

## IGNORAR -> .gitignore
``` .gitignore
*.txt
database
node_modules
```
