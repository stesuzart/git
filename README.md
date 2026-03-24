# Exercício Prático — Fluxo Básico com Git e GitHub
## 🧪Objetivo

Neste exercício, você irá praticar o fluxo básico de trabalho com Git e GitHub, realizando:

- clone de repositório
- criação de branch
- edição de arquivo
- commit
- push
- abertura de Pull Request (PR)
---
## 📌 Tarefa

### Cada aluno deverá:

1. Fazer o clone deste repositório para sua máquina.
2. Criar uma nova branch com o seguinte padrão:
`feature/seu-nome`

Exemplo:
`feature/stephannie-suzart`

3. Editar este arquivo `alunos.md`.
4. Adicionar seu nome e cidade.

Formato obrigatório:

`- Nome Sobrenome — Cidade/Estado`

Exemplo: 

`- Stephannie Suzart — São Paulo/SP`

5. Fazer commit da alteração.

Mensagem sugerida: `docs: adição de um novo nome na lista de alunos`

6. Fazer push da branch criada para o GitHub.
7. Abrir um Pull Request (PR) para a branch main.
---
## ✅ Critérios de aprovação

### Seu Pull Request será aprovado se:

- a branch seguir o padrão correto
- o nome estiver no formato solicitado
- não houver conflito com o arquivo
- o PR estiver direcionado para main
---
## 🚀 Dicas importantes

Antes de começar, verifique:
```git branch```

Para criar a branch:
```git checkout -b feature/seu-nome```

Para enviar alterações:
```
git add .
git commit -m "adição de um novo nome na lista de alunos"
git push origin feature/seu-nome
```

Depois disso, abra o Pull Request no GitHub.
