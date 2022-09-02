Você está fazendo um curso na Alura e gostaria de dividir o código do projeto por aulas, para se organizar melhor e também não perder o código antigo depois de uma refatoração e conseguir revisar sua evolução. Como você pode fazer isso?

VER OPINIÃO DO INSTRUTOR
Opinião do instrutor

Caminho 1: criar uma branch para cada aula do curso com o comando:

git checkout -b nome-da-branch

Com esse comando, você cria uma nova branch e muda automaticamente para ela para dar início ao desenvolvimento.

Caminho 2: criar uma branch para cada aula do curso com o comando:

git branch nome-da-branch

Essa é outra forma de criar uma branch. Nesse caso, ela é criada, mas não há a mudança automática para esta nova ramificação. Para isso, você pode usar o comando git switch nome-da-branch.