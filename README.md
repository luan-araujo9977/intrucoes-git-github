# intrucoes-git-github

Apos baixar o projeto, mudar para branch **develop**.

```
git checkout develop
```
Atualizar o repositorio local em relação ao remoto utilizando o comando:

```
git pull
```
## Ações em uma branch

### Padrão de nome

O nome de uma branch deve conter as seguintes informações:
- Iniciais do nome do criador
- Numero da tarefa.
- Nome da tarefa em ingles.
  
**Exemplo:**
```
la-10-add-colors-to-variables
``` 
### Criado uma branch

```
git checkout -b *nome-da-branch*
```
### Commit

Após efutar as modificações necessarias.

```
git add .
```
```
git commit -m "mensagem de commit em ingles"
```
Para o primeiro commit da branch, use:
```
git push --set-upstream origin (*nome-da-branch*)
```

## Pull request

Após enviar o commit para o github, crie um pull request.

- Adicione um titulo conciso com suas ações no commit.
- Altere a branch de comparação para a branch **develop**.
- Adicione o Arlisson como reviewer.
- Adicione os labels correspondentes.
- Adicione o project correspondente.
- Adicione um descrição para o PR, dezendo o que ele faz.

**Exemplo:**`
```
## O que esse PR faz?

Tarefa # + o numero da issue/tarefa

- "Coisas que foram feitas".
- Ex: Adiciona novo favicon.
- Altera o path...
```
Crie o pull request.

