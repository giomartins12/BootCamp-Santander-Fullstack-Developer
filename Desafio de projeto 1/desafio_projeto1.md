# Desafio de projeto 01:
> ##### Criando seu Primeiro Repositório no GitHub Para Compartilhar Seu Progresso

O seguinte desafio propõe a criação de um repositório no GitHub para fixação do aprendizado da aula sobreGit/GitHub.

Criação do repositório de GitHub: '<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>

![](C:\Users\giovanni.martins\git\BootCamp Santander fullstack Developer\Desafio de projeto 1\repositorio.png)

## Passo a passo: 

*Obs. O Git já está configurado com o email / usuário  e arquivo README.md criado.*

Inicializando o Git (na pasta de trabalho): 

```sh
$ git init
```

Adicionando arquivos do unmodified  para o staged:

*Obs. O asterisco informa que todo conteúdo da pasta será enviado para o staged.*

```sh
$ git add *
```

Realizando o commit dos arquivos e pastas (commit p/ unmodified): 

```sh
$ git commit -m  "<descrição_para identificação do commit>"
```

Cadastrando o link do repositório:

*origin = "Alias/apelido do link do repositório remoto"*

```sh
$ git remote add origin <endereço_do_repositório_no_github>
```

Listando os endereços dos repositórios remotos cadastrados (origin):

```sh
$ git remote -v
```

"Empurrando" os arquivos para o repositório remoto (gitHub):

```sh
$ git push origin master
```



