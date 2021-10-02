# DIO-Desafios
Repositório para armazenar os desafios oferecidos pela Digital Innovation One; https://digitalinnovation.one/

## Comandos GIT
**CONFIGURA SSH**


**Criar chave ssh:** ssh-keygen -t ed25519 -C academicojosealves@gmail.com

**Informar chave no github - (site)**

**Incializar o ssh agent**: eval $(ssh-agent -s)

**Entregar a chave pro agente:** ssh-add id_ed25519 

###PRIMEIROS COMANDOS

Criar pasta workspace no diretório c:
Digitar comandos no gitbash dentro do diretorio workspace/livro-receitas/

**git init:** git init  

Configurações iniciais: 

git config --global user.email "academicojosealves@gmail.com"

git config --global user.name Perkles

Criar arquivo strogonoff.md (markdown) na pasta livro-receitas

**git add:** git add * ou git add . 


**git commit:** git commit -m "commit inicial"

**git status** git status

Criar o diretorio receitas dentro do livro receitas

Mover o arquivo strogonoff para o diretório receita

git add strogonoff.md receitas/

git commit -m "cria pasta receitas e move arquivo para receitas"

echo > READMe.md

apos editar o README.md

git add *

git commit -m "adiciona index"

**LINK ENTRE REPOSITÓRIO LOCAL E REPOSITÓRIO NO GITHUB**

**git config --list**

**git config --global --unset user.email**

**git config --global --unset user.name**

git remote add origin git@github.com:academicojosealves/livro-receitas.git

git remote -v

git status

**git clone git@github.com:academicojosealves/livro-receitas.git**

