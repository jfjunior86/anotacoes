# Tutorial Básico do GIT
[Link para o site do GIT ](git-scm.com "site GIT")

## Cadastro Inicial

**Cadastrar e-mail:** depois de instalar o git devemos cadastrar o e-mail que vamos usar, com o seguinte comando:

```
git config --global user.email "seuemail@email.com"
```

**Cadastrar Usuário:** também é necessário o cadastro de um usuário, para realizar digite o seguinte comando:

```
git config --global user.name "Nome de usuário"
```

## Criando nosso primeiro projeto
+ A pasta para o nosso projeto terá o nome de : *projeto-piloto*
    
+ Crie uma arquivo com as definições do projeto: informações do projeto.txt

+ Vamos começar a monitorar todas as alterações realizadas na pasta no nosso projeto, para isso digite o comando:

` git init` (monitora as pastas de um projeto)

`git add` (vai 'congelar' o estado do seu projeto) esse comando possue variações:

1. 'Congela' apenas o arquivo especificado pelo nome e a extensão.

```
git add nomeDoArquivo.Extensão 
```
2. 'Congela' apenas os arquivos com uma determinada extensão.
```
git add *.extensão
```
3. 'Congela'todos os arquivos da pasta
```
git add .
```
Depois de 'Congela' o arquivo temos que salva-lo para preservar seu estado, para isso vamos usar:

`git commit` vai salvar o arquivo que foi congelado e atrbuir uma identificação, para que seja melhor identificado.
```
git commit -m "informações do que esta sendo salvo"
```
+ No git também podemos monitorar o estado atual dos nossos arquivos com o comando:

`git status` ( verifica qual a situação atual do repositório local, o que tem para comitar, arquivos novos, deletados, etc).

```
git status
```




