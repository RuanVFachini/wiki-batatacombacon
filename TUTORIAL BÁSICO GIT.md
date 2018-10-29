# GitHub básico

## Associando a issue em um novo Branch

Bom, todos nos deparamos com situações que teríamos que ler muito conteúdo para entender como certas coisas funcionam ou até mesmo fazer inúmeras tentativas para chegar no objetivo de cumprir determinada tarefa por meio da força bruta. A meu ver, tornamo-nos mais produtivos quando conseguimos executar certas tarefas básicas entendendo como elas funcionam sem a necessidade de absorvermos uma massa gigantesca de informações pois nem sempre o tempo está do nosso lado.

Basicamente os passos são estes:

 1. Clonar o repositório:
 `git clone “link do repositório github”`
 
  2. Realizar checkout para o novo Branch:
 `git checkout -b “nome do novo branch”`
 
  3. Fazer a adição dos arquivos que serão comitados:
 `git add “arquivos a serem enviados” | 
 git add . (este comando adiciona todos os arquivos)`
 
 4. Comitar:
 `git commit -m “‘#NumeroIssueAssociada’ mensagem de commit”`
 
 5. Dar o push para o repositório GitHub:
 `git push origin “nome do branch criado”`

Feito isso já estará disponível o ‘pull request’ no GitHub
- Autor: Ruan Vinicius fachini.
- Linkedin: https://www.linkedin.com/in/ruan-fachini-27a313144/
