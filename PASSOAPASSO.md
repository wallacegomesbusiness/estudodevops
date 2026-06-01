# Criar os comandos no git

Adicionar ao projeto

- git init
- git add . // Esse comando coloca todos os arquivos para poder comitar
- git status // Verifica como estão os arquivos
- git commit -m "" // Realiza o commit das informações
- git log // Verificamos as informações dos commits realizados
- git branch -M main // Essa informação passamos que iremos utilizar a branch main
- git push -u origin main // Essa informação estão subindo para o github na branch main
- git branch // Informa quais são as branchs que temos no nosso projeto
- git ckeckout // Altera a branch
- -b testes // Cria a branch testes
- git branch origin testes // Envia os arquivos para a branch informada
- git merge // Esse comando apenas especificando a branch para poder puxar as informações
- git branch -D nome_branch // Nesse comando excluimos a branch que queremos excluir
- git push origin testes --delete // Esse comando agora estamos removendo do github

# Trabalhando com issues e pullrequest

1. Passos

- Criamos uma branch nova
- Após isso subimo no repositorio github
- Cria uma issues do que precisa ser realizado
- realizamos a alteração em nosso arquivo, e subimos para o repositorio
- depois realizar a pull request para realizar a transferencia do arquivo e em seguida deletar a branch
- Não esquecendo de colocar o FIX -# para poder escolher a issuer que precisar ser fechada
