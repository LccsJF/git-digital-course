# Curso Digital: Git
* Repositório criado para o curso Ada|Santander Trilha Digital|Web Front-End

### Salvando alterações no Git
* comando git push
* comando git pull
* comando git fetch

### Comandos básicos do Git

    git init - inicia um repositório;

    git add - adiciona um arquivo ao "stage" ("estágio" em que o arquivo aguarda o "commit");

    git commit -m "texto explicativo" - finaliza o arquivo que está na área de "stage";

    git push origin master - envia o arquivo do "stage" para o repositório remoto (GitHub);

    git pull - atualiza qualquer alteração feita no repositório remoto GitHub com o repositório local Git;

    git fetch - sincroniza os arquivos do repositório remoto com o local, sem alterá-los;

    git diff origin/master - mostra a alteração feita no arquivo dentro do repositório remoto (GitHub);

    git branch (nome da branch) - cria uma nova "branch=ramo" de trabalho. A branch principal é a master/main;

    git branch - visualizo todas as branchs do meu repositório. A que está de cor de diferente, é minha branch atual;

    git log --oneline --decorate - mostra todas as "branchs" e a branch utilizada no momento;

    git checkout (nome da branch) - sai da branch atual e vai para a branch solicitada;

    git merge (nome da branch) - une, adiciona todas as branchs com seus arquivos a branch principal master/main;
