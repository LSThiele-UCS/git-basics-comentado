# 02. Configure a ferramenta

> Configure informações de usuário para todos os repositórios locais.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Instale o Git](01-instale-o-git.md) · [Índice](../README.md) · [Crie repositórios ➡](03-crie-repositorios.md)

---

## Comandos desta seção (2)

### 1. `git config --global user.name "[nome]"`

```bash
git config --global user.name "[nome]"
```

**O que faz:**

Define um nome de usuário que será assinado em todas os projetos gits da sua máquina.
Então todo repositório criado e todo commit feito terá essa informação por padrão.

**Quando usar / observação:**

Logo quando estiver configurando o git pela primeira vez.
Assim evita ter que fazer o git config para cada repositório.
Apesar dessa ainda ser uma opção caso queira alterar esse dado.

---

### 2. `git config --global user.email "[endereco-de-email]"`

```bash
git config --global user.email "[endereco-de-email]"
```

**O que faz:**

Define um email que será assinado em todas os projetos gits da sua máquina.
Então todo repositório criado e todo commit feito terá essa informação por padrão.

**Quando usar / observação:**

Logo quando estiver configurando o git pela primeira vez.
Assim evita ter que fazer o git config para cada repositório.
Apesar dessa ainda ser uma opção caso queira alterar esse dado.

---

## Checklist deste arquivo

- [x] 1. `git config --global user.name "[nome]"`
- [x] 2. `git config --global user.email "[endereco-de-email]"`

---

[⬅ Instale o Git](01-instale-o-git.md) · [Índice](../README.md) · [Crie repositórios ➡](03-crie-repositorios.md)
