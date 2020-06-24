## O que é o git e github
Git é um sistema de `controle de versão de arquivos.` Através deles podemos `desenvolver projetos na qual diversas pessoas podem contribuir simultaneamente no mesmo`, editando e criando novos arquivos e permitindo que os mesmos possam existir sem o risco de suas alterações serem sobrescritas.

O Github é um serviço web que oferece diversas funcionalidades extras aplicadas ao git. Resumindo, `você poderá usar gratuitamente o github para hospedar seus projetos pessoais`. Além disso, quase todos os projetos/frameworks/bibliotecas sobre desenvolvimento open source estão no github, e você pode acompanhá-los através de novas versões, contribuir informando bugs ou até mesmo enviando código e correções

* https://tableless.com.br/tudo-que-voce-queria-saber-sobre-git-e-github-mas-tinha-vergonha-de-perguntar/

## O que é um commit?
Um Commit é `um pacote de alterações feitas no repositório`. Cada commit possui arquivos alterados, autor e uma mensagem de resumo. Agora o arquivo está pronto para ser empacotado em um commit. Escreva o comando de commit incluindo uma mensagem que explique o que sua alteração faz no repositório<br/>
<img src="commits-001.jpg" width="500"/>
<br/><br/>

## O que é uma branch?
`Uma ramificação` no git é um ponteiro para as alterações feitas nos arquivos do projeto. É útil em situações nas quais você deseja adicionar um novo recurso ou corrigir um erro, gerando uma nova ramificação garantindo que o código instável não seja mesclado nos arquivos do projeto principal. Depois de concluir a atualização dos códigos da ramificação, você pode mesclar a ramificação com a principal, geralmente chamada de master.<br/>
<img src="branches-001.jpg" width="500"/>

## Instalando o git

Windows <br />
> http://msysgit.github.io/


Distribuicoes baseadas no Debian<br />
> sudo apt-get install git

## Configurando o git
> $ git config --global user.name "Fulano da Silva"<br />
> $ git config --global user.email fulanodasilva.git@gmail.com

## Iniciando um repositorio git
> $ git init

## Primeiro Commmit
#### Rastrear uma alteração
> $ git add file<br />
> $ git add .

#### Commit
> $ git commit -m "meu primeiro commit"<br/>
> $ git commit -am "add e commit com mensagem"

## Áreas de versionamento

<img src="repository-001.png" width="500"/>

#### Revertendo alterações
> $ git restore file<br>
> $ git restore --staged file<br>
> $ git checkout file<br>
> $ git checkout .<br>

#### Ver status e logs
> $ git status<br/>
> $ git log --pretty<br/>
> $ git log --graph

## Navegando entre os ramos
> $ git checkout -b feature<br/>
> $ git checkout master<br/>
> $ git checkout 951d3de<br/>
> $ git branch
