Inicialmente, foi criada a pasta através do comando:
# mkdir projetotcn

Para acessar a pasta usei o comando:
# cd projetotcn

Criei o readme para poder documentar o trabalho com o comando: 
# touch readme.md

E para iniciar o gerenciador de pacotes Node, foi usado o
# npm init -y 
onde o comando criou o arquivo package.json

# npm i express nodemon dotenv
"npm i" para instalar os pacotes

em seguida dei um
# code . 
para iniciar o VSCode

# nano .gitignore
para criar e editar arquivos pelo terminal, no caso utilizei para criar o git ignore

# npm install 
para instalar o node_modules

para criar uma estrtura de arquivos e pastas eu usei 
# mkdir src

seguindo, para criar dentro da pasta src, eu usei
# touch src/app.js

criei também o server.js para criar a configuração da API através do comando:
# touch src/server.js

criei a pasta config para gerenciar a conexão com o banco de dados através do:
# mkdir src/config

criei a controllers pra gerenciar as requisições das rotas e coneção om banco de dados com o comando:
# mkdir/controllers

E por fim, a pasta routes para getenciar as requisições das rotas e conexão com o banco de dados
# mkdir src/routes

Para começar a enviar a estrutura do projeto pro GitHub, eu usei o comando 
# git init
onde eu precisei informar meu nome e email através dos comandos:
# git config --global user.name "Pedro_Hoffmann"
# git config --global user.email "pedrohoff87@gmail.com"

Depois disso eu dei um
# git status
para adicionar os arquivos ao versionamento

O GitBash disse que nada foi adicionado ao commit e pediu para dar um git add. Então foi feito 
# git add .

Feito esses passos, para salvar o projeto foi usado o comando:
# git commit -m 'estrutura do projeto'

Ao criar um repositório no gitHub, copiei o link e voltei para o terminal executando o comando
# git branch -M main
onde informamos ao repositório que queremos enviar os arquivos e após isso, usei o:
# git remote add origin "colar url do repositório"

e por fim, para enviar tudo, foi usado o:
# git push -u origin main
