# Lista de comandos úteis - Git e Github

## Setar usuário
git config --global user.name "Name"
## Setar email
git config --global user.email name@email.com
## Criar novo repositório
git init
## Verificar estado dos arquivos/diretórios
git status
## Adicionar um arquivo em específico
git add meu_arquivo.txt
## Adicionar um diretório em específico
git add meu_diretorio
## Adicionar todos os arquivos/diretórios
git add *
## Comitar um arquivo
git commit meu_arquivo.txt
## O primeiro push de um repositório deve conter o nome do repositório remoto e o branch
git push -u origin master
## Os demais pushes não precisam dessa informação
git push
## Atualizar os arquivos no branch atual
git pull
