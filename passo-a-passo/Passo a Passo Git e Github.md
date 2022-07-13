# Passo a passo para criar Pasta pelo Git e empurrar com o comando “git commit” para o Repository no Github

### Esse tutorial é para iniciantes em Git e Github 

**Objetivo**

Que você aprenda a criar a pasta/diretório pelo Git, criar arquivo em Markdown e empurrar o commit para o Repository no github pela primeira vez.

Bônus: Para fazer alteração do arquivo ou em caso de conflito, seguir o passo a passo no final.

### Está dividido em 3 partes:

* 1 - Criar pasta pelo Git

* 2 - Criar arquivo READ.ME

* 3 - Empurrar commit para o **Repository** no Github



#### Comandos importantes para a navegação pelo git:

**dir**: Para listar o que tem dentro do diretório e te situar.

**cd ‘dig o nome do diretório’/**: Para você escolher em qual diretório vai criar.

**Ctrl+l**: atalho para limpar tudo.

**mv**: para mover um arquivo para outra pasta.

**cd ..**: Para voltar para a pasta anterior.

**mkdir**: Para criar uma pasta. 

**echo + nome do arquivo**: Para criar arquivo dentro da pasta.

**del + nome da pasta**: Para deletar os arquivos dentro da pasta.

**rmdir + nome da pasta**: Para deletar a pasta.

*Obs*: todos os comando entram pressionando o **“enter”**.

 

### Vamos para o passo a passo!

#### Parte 1

* Digitar **dir** para listar.

* Digitar **cd + nome do diretório + /** para escolher onde quer criar a pasta.

* **Dica**: o TAB completa o nome.

* Digitar **mkdir** + o nome da pasta que quer criar (sem espaços).

* Pronto, pasta criada!

#### Parte 2

Criar arquivo READ.ME para a "capa" do seu conteúdo no Repository.

* Acessar: https://typora.io/

* Escrever com a linguagem Markdown.

* Salvar na pasta que foi criada.

* Criar o arquivo com o programa em si. Aqui nesse tutorial foi criado com Markdown mesmo.

* Criar uma pasta dentro da que foi criada e salvar o arquivo do programa dentro dela.

 #### Parte 3 

* Acessar o seu perfil no Github.
* Entrar em **Repositories** e clicar **new repository**.
* Nomear o Repository.
* Copiar o endereço http que foi gerado.
* Iniciar o comando **git init** no Git.
* Digitar o comando **"git add *" ** 
* Digitar **commit -m " commit inicial"** (entre as aspas você pode escolher o nome que quer dar ao commit).
* Digitar o comando **git remote origin** e colar o endereço que foi gerado e que você copiou em New Repository.
* Digitar o comando **git push origin master**.
* Pronto! Atualize o seu perfil e lá estará o seu Repository.



#### Agora, caso precise alterar ou aconteça algum confilto, segue o passo a passo a seguir:

* Digitar o comando **git status** e identificar o conflito.

* Digitar o comando **"git add *"** para adicionar todos os arquivos e alterações que foram realizadas.

* Digitar o comando **git commit -m "correção"** (entre as aspas você pode escolher o nome que quer dar ao commit).

* Digitar o comando **git push origin master**

* Feito! Agora o seu repository está atualizado.











