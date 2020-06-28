# GIT & GITHUB

* Comandos iniciais para o uso do Git + GitHub em seu projeto.

# Baixe e instale o GIT em sua máquina
* link: https://git-scm.com/downloads

# Após isso crie uma conta 
* link: https://github.com/

* Faça login e crie um repositório para trabalhar em um novo projeto 

* Antes de iniciarmos é importante que se você desejar evitar que arquivos pesados sejam 
enviados ao seu repositório online, é importante que você crie um arquivo dentro de sua pasta onde contém os arquivos que queira enviar ao seu projeto com o nome .gitignore, e dentro do mesmo
adicionar os nomes dos arquivos juntamente com a sua extensão, ou o nome da pasta caso queira evitar o upload do mesmo.
Exemplo: 'node_modules', com isso o GitHub será impedido de fazer upload desta pasta para dentro do seu projeto no servidor GitHub.

Os comandos a seguir devem ser executados dentro da pasta raiz o seu projeto onde contém os arquivos que queira trabalhar.

[1] git init => Inicializa a linha do tempo

[2] git add file.extensão => Adiciona um arquivo a linha do tempo

[3] git add --all ou git add . => Adiciona todos os arquivos a linha do tempo exceto os mencionados no arquivo .gitignore

[4] git status => exibe o estado da linha do tempo com os arquivos adicionados pelo comando anterior ou alterados e não alterados, e os arquivos não adicionados na linha do tempo também;

[5] git commit -m "Comentário breve" => Ao realizar um commit você está informando a linha do tempo que os arquivos foram alterados e que já estão prontos para envio do projeto para o github.

[6] git log => Exibe os registros de commit da linha do projeto com suas respectivas alterações e id's dos commits realizados pelo Dev.

[7] git branch nome-branch => Adiciona uma linha paralela sem alterar nada na linha principal master.

[8] git checkout nome-branch => Entra dentro da branch nome-branch para operação sem interferir na linha principal, o mesmo comando serve para alterar entre as branchs existentes na sua linha do tempo, para retornar a master só precisa executar o comando git checkout master.

[9] git branch => lista as brachs existentes em sua linha do tempo.

[10] git merge nome-branch => Você uni as linhas do tempo com a principal, você deverá estar na linha principal para realizar este comando, por exemplo a master, isso irá unir todos os arquivos tanto como os da branch's como os da master.

[11] git branch -D nome-branch => Você irá deletar esta branch do seu projeto localizado na sua máquina.

[12] git remote add origin https://github.com/jocgsousa/aula =>
Este comando adicionar a origin do seu repositório a qual você poderá estar enviandos seus projetos locais para ela.

[13] git remote -v => Este comando irá listar para você o endereço do repositório que você adicionou em seu projeto local

[14] git push -u origin master => Após o commit de todas suas alterações este comando é inicial para enviar seu projeto a nuvem e deverá neste formato ser executado uma vez dentro desta pasta raiz, após isso quando for necessário realizar um novo upload execute apena  git push, mas atente-se para realizar os adds e os commits -m antes deste comando ok!

[15] git pull => Faz a atualização do seu projeto local, pegando todas as alterações realizadas em nuvem ou por outro colaborador do projeto.

[16] git clone https://github.com/jocgsousa/aula.git => Faz uma cópia inteira do repositório online 'aula' para o seu computador local.


