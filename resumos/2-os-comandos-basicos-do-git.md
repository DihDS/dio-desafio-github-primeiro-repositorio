# **Os comandos básicos do Git** ⌨ 

Separei para vocês alguns comandos do Git. Para quem está começando igual eu estou, é uma lista muito bem-vinda. 

## **1 - git config** 

Quando se utiliza pela primeira vez o Git, é um comando fundamental para configurar sua identidade de usuário que serão aplicadas em cada commit.

Veja os exemplos:

- $ git config –global user.name “Nome de usuário do GitHub”

 - $ git config –global user.email “Seu e-mail utilizado no GitHub”

## **2 – git init**

Utilizado para criar um novo projeto no Git. Ele vai criar um novo repositório, e assim você consegue armazenar seu código fonte, alterar e etc.

Veja os exemplos:

- $ git init

Se você já possuir um repositório anterior ou deseja criar um repositório com um nome em específico, então pode ser feito da seguinte forma:

- $ git init < o nome do seu repositório > 

## **3 – git clone**

Realiza a cópia de um repositório existente.

Veja o exemplo:

- $ git clone  < URL do projeto >

## **4 – git add**

Adiciona os arquivos especificados de código no repositório, novos ou alterados.

Veja os exemplos:

- $ git add seu_arquivo (esse comando irá adicionar o arquivo em específico ao repositório)

- $ git add * (esse comando irá adicionar todos os arquivos novos ou modificados ao repositório)

## **5 – git commit**

Existe uma diferença entre git commit e git add:

- O git commit executa o commit dos arquivos que foram adicionados e cria uma nova revisão com um log. E se você não adicionar nenhum arquivo, o git não fará o commit de nada.

- Já o git add adiciona seus arquivos modificados na fila para serem submetidos a um commit posteriormente. E os arquivos não passaram por um commit.

Veja os exemplos:

Você consegue combinar as duas ações em um único comando: 

- $ git commit -a

Ou consegue adicionar uma mensagem para a execução de um commit:

- $ git commit -m “seu comentário”

## **6 – git remote**

Consegue estabelecer uma conexão entre seu repositório local e um repositório remoto.

Veja o exemplo:

- $ git remote add < nomecurto > < URL >

## **7 – git push**

Serve para enviar as modificações realizadas para um repositório remoto conectado.

Veja os exemplos:

- $ git push -u < nomecurto > < nomedobranch >

Lembrando que é importante especificar a origem e o upstream antes de usar o git push:

- $ git push –set-upstream < nomecurto > < nomedobranch >

## **8 – git pull**

Baixa o conteúdo (não os metadados) do que foi alterado no repositório remoto para o seu repositório local e atualiza o seu conteúdo para a última versão.

Veja o exemplo:

- $ git pull < URL >

## **9 – git status**

Serve para checar o estado atual de um repositório. Ele confere o status e reporta se existe pendências.

Veja o exemplo:

- $ git status

## **10 – git help**

O Git tem muitos comandos e cada um com sua função, então se você estiver com dúvida o comando help vai te ajudar.

Veja o exemplo:

- $ git help <comando que se tem dúvida>