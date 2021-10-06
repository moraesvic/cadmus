#### Versão em português abaixo / Portuguese version below

# English version

## Idea

When we are developing a full stack system, there are some important settings that are practically repeated for every project. It is not always easy to remember, months later, how a specific technical issue was solved, or why a certain decision was taken. To replicate all of that in the client's machine and guarantee that the program is up to the highest level of quality can be even harder.

## An installer is born

As they say, necessity is the mother of invention, and I have decided to create my own installer — which I named Cadmus. After minutious testing, it is ready to be imported as a library in my new projects employing PostgreSQL. It creates a new user for the database with his/her credentials and permissions, configures the .env file with the environment variables, and, last but not least, populates the tables of the database with test data.

## How to use

If you still haven't installed PostgreSQL, I would recommend [this guide](https://phoenixnap.com/kb/how-to-install-postgresql-on-ubuntu) (for Ubuntu users). You will probably have to do something like **sudo apt install postgresql postgresql-contrib** . Package manager and package names may vary according to your operating system.

Go to the root of your project and do **git submodule add https://github.com/moraesvic/cadmus** . This will create a directory named **cadmus**, which can be renamed as **install** for better clarity: **git mv cadmus/ install** . You might also want to move the directories **cadmus/mkheader** and **cadmus/common** to **lib** folder, under your root directory, in case you want to use these libraries for something else later.

## [What's in a name?](https://en.wikipedia.org/wiki/A_rose_by_any_other_name_would_smell_as_sweet)

Cadmus was the first hero in Greek mythology, and the founder of the city of Thebes. That seemed fitting for a piece of software which lays the foundations to build upon.

# Versão em português

## A ideia

Quando estamos desenvolvendo um sistema full stack, existem algumas configurações importantes que são praticamente repetidas para cada projeto. Nem sempre é fácil se lembrar, meses depois, como uma questão técnica foi resolvida, e nem por que uma determinada decisão foi tomada. Replicar tudo isso na máquina do cliente e garantir que o programa atenda a todos os padrões de qualidade pode ser mais difícil ainda.

## Nasce um instalador

Como a necessidade aguça o engenho, resolvi criar meu próprio instalador — batizei-o de Cadmus — que, após ser minuciosamente testado, está pronto para ser importado como uma biblioteca em meus novos projetos que venham a utilizar PostgreSQL. Ele credencia um usuário no banco de dados, configura o arquivo .env com as variáveis de ambiente, e de quebra, povoa as tabelas do banco de dados com dados para teste.

## Modo de usar

Se você ainda não instalou o PostgreSQL, eu recomendo [esse guia](https://phoenixnap.com/kb/how-to-install-postgresql-on-ubuntu) (para usuários do Ubuntu). Você provavelmente terá que fazer algo como **sudo apt install postgresql postgresql-contrib** . Seu gerenciador de pacotes e os nomes dos pacotes podem ser diferentes de acordo com o seu sistema operacional.

Em seguida, vá para a raiz do seu projeto e digite **git submodule add https://github.com/moraesvic/cadmus** . Isso criará um diretório chamado **cadmus**, que pode ser renomeado como **install** para maior clareza: **git mv cadmus/ install** . Talvez você também queira mover os diretórios **cadmus/mkheader** e **cadmus/common** para a pasta **lib**, sob o seu diretório raiz, no caso de você querer usar essas bibliotecas para outros fins mais tarde.

## [O que há num simples nome?](https://en.wikipedia.org/wiki/A_rose_by_any_other_name_would_smell_as_sweet)

Cadmus foi o primeiro herói na mitologia grega, e o fundador da cidade de Tebas. O nome me pareceu apropriado para um software que assenta as fundações sobre as quais vamos desenvolver.


