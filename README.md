Meu primeiro sistema git
Aqui você deve colocar o máximo de informações sobre o sistema
Alteração no readme para descrever melhor o comit

git init // inicia o git
git status //verifica como está o git
git add -A //adiciona arquivos que não estão no git
git add arquivo.extenção // adiciona só o arquivo
git log // vê todos os commits
git commit -m "Mensagem" //faz o commit para o git, para enviar as alteração da maquina para o git
git commit -am "Mensagem" //adiciona arquivos e faz commit
git branch //lista os branch existentes - branch serve para criar um novo histórico
git branch teste //cria o branch teste
git checkout teste //vai para o branch teste
git diff // alterações nos arquivos
git diff --name-only //mostra só o nome dos arquivos
git diff style.css // pega só as alterações do arquivo
git checkout HEAD -- style.css //HEAD pega o branch atual | o comando remove as alterações feitas

git reset --hard //hard volta tudo e apaga arquivos, soft - mais usado em equipe, mantem os arquivos criados

depois de criado as chaves locais, ligado com o git e executado o comando de conexão
git remote // mostra o repositório remoto 

fetch //pega o que tem remoto
git push -u origin master // (-u destino local )envia oque tem local para o remoto

//Alterações no Repositório remoto
git push origin master // envia para o remoto

