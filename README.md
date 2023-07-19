# fullcycle-rocks

desafio golang curso Dev Full Cycle 3.0

imagem gerada e disponibilizada no dockerhub.
[leocansil/fullcycle-rocks](https://hub.docker.com/r/leocansil/fullcycle-rocks)

Dentro da pasta main temos o

### Dockerfile 

Elaborado em dois stages para reduzir a imagem no final.

### fullcycle-rocks.go

Um arquivo simples de hello world implementado para gerar a frase ao final

## Comando para realizar o build com o docker e gerar a imagem

```
docker build -t leocansil/fullcycle-rocks .
```

a ser executado dentro da pasta main.