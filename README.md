# 📘 Documentação de Comandos do Git no Console

Uma referência rápida e prática dos principais comandos Git utilizados no terminal. Ideal para iniciantes e para consulta diária. 🚀

---

## 🛠️ Inicialização

```bash
git init
```
> Inicializa um repositório Git na máquina local.

---

## 📦 Adicionando e Versionando

```bash
git add .
```
> Adiciona todos os arquivos para o controle de versionamento.

```bash
git commit -m "first commit"
```
> Cria um ponto na linha do tempo do repositório (um *commit* ou "versão").

---

## 🔍 Visualização de Histórico e Alterações

```bash
git log
```
> Exibe os *commits* anteriores com detalhes (autor, hash, mensagem, etc).

```bash
git diff
```
> Mostra as diferenças entre os arquivos modificados e os últimos *commits*.

---

## 🌿 Ramificações (Branches)

```bash
git branch
```
> Lista todas as branches disponíveis no repositório.

```bash
git checkout nome-da-branch
```
> Alterna para a branch desejada.

```bash
git checkout -b nova-branch
```
> Cria e já muda para a nova branch criada.

---

## 🌐 Repositório Remoto

```bash
git remote add origin https://github.com/arthurvitorads/gitFunctions.git
```
> Adiciona um repositório remoto com o nome padrão `origin`.

---

## 🚀 Enviando para o GitHub

```bash
git push -u origin master
```
> Envia a branch local `master` para o repositório remoto (primeiro push).

```bash
git push origin nome-da-branch
```
> Envia as alterações para a branch desejada no repositório remoto.

---

## 📥 Recebendo do Repositório Remoto

```bash
git pull origin master
```
> Baixa e aplica as alterações do repositório remoto na branch local atual.

```bash
git fetch
```
> Atualiza o repositório local com as referências do remoto (sem aplicar mudanças diretamente).

---

## 🧠 Dica

> Use `git status` com frequência para verificar o estado atual dos arquivos e do repositório.

---

## 📎 Referência Rápida

- `git status`: Verifica o status do repositório.
- `git reset --hard HEAD`: Descarta alterações locais.
- `git merge nome-da-branch`: Une alterações de outra branch na atual.

---

Feito com 💻 por [Arthur Vitor](https://github.com/arthurvitorads)  
📂 Repositório: [gitFunctions](https://github.com/arthurvitorads/gitFunctions)
