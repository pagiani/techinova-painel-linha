# Respostas do LAB 01

Nome:
Matricula:
Dupla (M2 em diante):

---

## M2 - Quem quebrou o painel

**Hash curto do commit que introduziu o erro:01ef93b

**Autor:Tarcisio Melo

**Data:15/06/2026

**Linha alterada (antes e depois):

```
antes:return (leitura - 32) * 5 / 9;
depois:return leitura * 9 / 5 + 32;
```

---

## M3 - O segredo vazado

**O que voce esperava ver no `git status` e o que apareceu:
esperava que o .gitignore resolvesse, mas o arquivo continua rastreado normalmente

**Depois do push, alguem que clonar o repositorio ainda consegue ler a chave?
Responda em duas linhas, explicando o motivo:
sim, alguém que clonar o repositório ainda consegue ler a chave. O git rm --cached
só impede que o arquivo apareça nos commits futuros, mas ele continua existindo
no histórico de commits antigos, acessível por qualquer pessoa que rodar
"git log" e "git show" nesses commits.

---

## M4 - Colisao

**O que significavam os marcadores que apareceram dentro do arquivo:**

- `<<<<<<<` :
- `=======` :
- `>>>>>>>` :

**Qual pedaco veio de quem, e qual titulo voces decidiram manter:**

---

## Casa - Incidente na linha 3

**Hash do commit que quebrou o painel:**

**Hash do commit de revert:**

**Por que `git revert` e nao `git reset` neste caso:**
