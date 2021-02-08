## Primeiro Repositório Git 

## Aprendendo Comandos Básicos do Git

git --version : Para verificar a versão do Git

git config --global user.name "Messias Silva" : Registrar na configuração do Git o nome
git config --global user.email "silvamessias016@gmail.com" : Registrar na configuração do Git o e-mail

git config --list : Verificar as configurações de dados do Git

git init : Para tornar uma pasta um repositório, para isso usamos este comando para inicialização do Git 

git status : Checar o status do repositório 

git add -all : Adicionar as mudanças no próximo commit

git commit -m "Criando o Readme" : Realizando o commit. Obs.: Para realizar um commit você precisa sempre redigir uma mensagem que irá representar o que o seu commit está fazendo no código ou repositório

git log : Ver o histórico de versões do seu repositório

git log -p : Mostra o conteúdo que foi feito o commit e com mais detalhes também

git checkout -- README.md : Desfaz a mudança antes de adicioná-la ao próximo commit

git reset HEAD README.md : Retira as mudanças adicionadas pelo "git add -all" do próximo commit. Ai sim, você poderá usar desfazer as alterações no arquivo com o checkout

git reset --soft HEAD~1 : Desfaz o commit 

git reset --hard HEAD~1 : Opção mais agressiva para desfazer todas as alterações do último commit

## Gerenciando Repositórios Remotos

ssh-keygen : Gerar a chave SSH 

cat ~/.ssh/id_rsa.pub : Visualizar o hash de sua chave SSH 

git remote add origin git@github.com:messiassilva/firstrepo.git : Informar para o Git qual será o nosso repositório remoto no GitHub

git push origin master : Enviar o commit para nosso repositório remoto  
