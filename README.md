**Desenvolvido em pair com [Daniel](https://github.com/DS1lva).**

As informações usadas no projeto foram retiradas deste site: https://www.es.gov.br/governo/palacio-anchieta

## Github Pages

https://paulo14simoes.github.io

## O que é git?

Git é um sistema de controle de versões distribuído criado por Linus Torvalds. É usado principalmente para desenvolvimento de software, mas pode ser usado para versionar qualquer tipo de arquivo.


## O que é GitHub?

É um serviço baseado na nuvem onde você pode gerenciar seus repositórios git, disponibiliza várias funções que facilitam o trabalho, como Pull Requests, Boards, Issues e Github Actions. É importante se atentar que é possível criar um repositório git na máquina ou em um servidor local, e que há outras opções disponíveis no mercado além Github, por exemplo, Azure DevOps e Gitlab.


## Passo a passo

* Abrir o terminal

```bash
Ctrl + Alt + T (Linux Mint)
```

* Ir para a pasta do projeto

```bash
cd ~/projeto-integrador
```

* Iniciar um repositório:

```bash
git init
```

* Podemos criar uma branch para fazer cada feature usando o seguinte comando:

```bash
git switch -c nomeDaBranch
```

* E depois que as alterações estiverem prontas podemos abrir uma PR no Github e mergear na interface gráfica ou pela cli da seguinte forma:

```bash
git switch master #mudamos para a branch master/main
git merge nomeDaBranch #mergeamos alterações
```

* Fazer commits durante o desenvolvimento:

```bash
git add -A (para colocar arquivos como staged)
git commit -m "mensagem de commit" para "commitar" alterações
```

* Ao finalizar o projeto precisamos subir o repositório que está local para o GitHub (ou qualquer outro).
Para isso, é só ir na conta e criar um repositório, depois adicionamos o remote no repositório local
com o seguinte comando:

```bash
git remote add origin https://github.com/paulo14simoes/projeto-integrador-iv-a.git
```

* Agora podemos concluir subindo o código com o seguinte comando:

```bash
git push origin master
```
