# Hey! 👤
[![Github Badge](https://img.shields.io/badge/-Github-000?style=flat-square&logo=Github&logoColor=white&link=https://github.com/luciolemos)](https://github.com/luciolemos)
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/lucio-lemos-a550441a1/)](https://www.linkedin.com/in/lucio-lemos-a550441a1/)
[![Twitter Badge](https://img.shields.io/badge/-Twitter-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/lucciolemos)](https://twitter.com/lucciolemos)
[![Youtube Badge](https://img.shields.io/badge/-YouTube-ff0000?style=flat-square&labelColor=ff0000&logo=youtube&logoColor=white&link=https://studio.youtube.com/channel/UCrNM1nr2nw0lSqMD10m6rLw)](#)
## Começando com o **EXPRESS** 📌: 
Use o gerador de aplicativos do express para criar rapidamente uma estrutura básica de aplicativo, seguindo os passos abaixo descritos.
### Resumo das rotinas que seráo executadas no _bash_:
- Instale o Node `$ sudo apt-get install nodejs`. O NPM é o Gerenciador de Pacotes do Node (Node Package Manager). Node e NPM são empacotados juntos.
- Instale o express com o comando `$ npm install express-generator -g`.
- Crie o diretório da sua aplicação express com `$ express myapp`.
- Navegue para dentro de `myapp` com o comando `$ cd myapp`.
- Instale as dependêcias do Node, que o projeto necessita com `$ npm install`;  
- Verificandoa se há atividade na porta 3000 `$ sudo netstat -nlp | grep :3000`;
- Interrompendo o processo na porta 3000, caso haja `$ kill 11020`; 
- Carregando o projeto no vscode com `$ code .`;
- Abrindo o terminal no vscode `Ctrl+J`;
- Startando a aplicação com `$ DEBUG=myapp:* npm start`. 
- Rodando a aplicação digitando no browser `http://localhost:3000`.

### Etapas da criação do projeto no terminal
#### ✔️ Listando arquivos/diretórios em vscode com `$ ls -l`:
    luciolemos@dev:~/vscode$ ls -l
    total 12
    drwxrwxr-x  3 luciolemos luciolemos 4096 abr 27 14:35 git_cli
    drwx------ 10 luciolemos luciolemos 4096 abr 18 17:47 maratona
    drwxrwxr-x  6 luciolemos luciolemos 4096 abr 17 22:20 vscodeteste
#### ✔️ Criando o diretório do projeto `express_generator_project` com `$ mkdir`. 
    luciolemos@dev:~/vscode$ mkdir express_generator_project
#### ✔️ Listando arquivos/diretórios `$ ls -l` para verificar se o diretório `express_generator_project` foi efetivamente criado.
    luciolemos@dev:~/vscode$ ls -l
    total 16
    drwxrwxr-x  2 luciolemos luciolemos 4096 mai  2 21:56 express_generator_project
    drwxrwxr-x  3 luciolemos luciolemos 4096 abr 27 14:35 git_cli
    drwx------ 10 luciolemos luciolemos 4096 abr 18 17:47 maratona
    drwxrwxr-x  6 luciolemos luciolemos 4096 abr 17 22:20 vscodeteste
#### ✔️ Navegando até a raiz do projeto `/express_generator_project` com o comando `$ cd` (change directory): 
    luciolemos@dev:~/vscode$ cd express_generator_project
#### ✔️ Gerando o projeto com `$ npx express-generator`:
    luciolemos@dev:~/vscode/express_generator_project$ npx express-generator

    warning: the default view engine will not be jade in future releases
    warning: use `--view=jade' or `--help' for additional options


    create : public/
    create : public/javascripts/
    create : public/images/
    create : public/stylesheets/
    create : public/stylesheets/style.css
    create : routes/
    create : routes/index.js
    create : routes/users.js
    create : views/
    create : views/error.jade
    create : views/index.jade
    create : views/layout.jade
    create : app.js
    create : package.json
    create : bin/
    create : bin/www

    install dependencies:
        $ npm install

    run the app:
        $ DEBUG=express-generator-project:* npm start
#### ✔️ Instalando as dependências do projeto com `$ npm install`
    luciolemos@dev:~/vscode/express_generator_project$ npm install
### Git CLI
#### Ao criar o projeto no Github será gerado o seguinte bloco de código:
    echo "# express_generator_project" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/luciolemos/express_generator_project.git
    git push -u origin main
#### ✔️ Criando o arquivo **README.md** `echo "# express_generator_project" >> README.md`.
#### ✔️ Iniciando o projeto com `git init`.    
#### ✔️ Adicionando o arquivo **README.md** ao repositório local com `git add README.md`.   
#### ✔️ Salvando as alterações feitas no repositório local com `git commit -m "first commit"`.
    luciolemos@dev:~/vscode/express_generator_project$ git commit -m "first commit"
#### ✔️ Informando o ramo do projeto onde serão salvas as alterações.
    luciolemos@dev:~/vscode/express_generator_project$ git branch -M main
    luciolemos@dev:~/vscode/express_generator_project$ git remote add origin https://github.com/luciolemos/express_generator_project.git
#### ✔️ Empurrando (_push_) as alterações para o repositório remoto
    luciolemos@dev:~/vscode/express_generator_project$ git push -u origin main
    Username for 'https://github.com': luciolemos
    Password for 'https://luciolemos@github.com': 
    Enumerating objects: 1067, done.
    Counting objects: 100% (1067/1067), done.
    Delta compression using up to 4 threads
    Compressing objects: 100% (1009/1009), done.
    Writing objects: 100% (1067/1067), 1.47 MiB | 1.13 MiB/s, done.
    Total 1067 (delta 180), reused 0 (delta 0), pack-reused 0
    remote: Resolving deltas: 100% (180/180), done.
    To https://github.com/luciolemos/express_generator_project.git
    * [new branch]      main -> main
    Branch 'main' set up to track remote branch 'main' from 'origin'.

#### ✔️ Abrindo o diretório corrente no VSCode com `$ code .`: 
    luciolemos@dev:~/vscode/express_generator_project$ code .

### Identificando e parando o processo na porta 3000, caso haja:
#### ✔️ Localizando o PID (Process ID) escutando na porta 3000 com `$ sudo netstat -nlp | grep :3000`:
    luciolemos@dev:~/nextlevelweek/restful$ sudo netstat -nlp | grep :3000
    [sudo] senha para luciolemos:     
    tcp6       0      0 :::3000                 :::*                    OUÇA       11020/node 

#### ✔️ O ID do processo é o número antes do nome do processo na sexta coluna (11020). Parar o processo com o comando `$ kill 11020`.
    luciolemos@dev:~/nextlevelweek/restful$ kill 11020
### Rodando nosso projeto
#### ✔️ Startando na porta 3000.
    luciolemos@dev:~/vscode/express_generator_project$ DEBUG=express:* npm start
#### ✔️ Digitando no browser `http://localhost:3000`.

