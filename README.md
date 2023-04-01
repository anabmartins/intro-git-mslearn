# Comandos GIT 
# verificar usuário global 
git config --list 
# definir usuário e email 
git config --global use.name “nomeDoSeuUsuário” 
git config –global use.email “seuemail@email.com” 
# Crie um novo repositório no github 
#Criando vínculo entre arquivos locais com o github 
git init 
git add . 
git commit -m “uma mensagem” 
git remote add origin https://github.com/pbattistella/lista-tarefas-html-css-js-localstorage.git *após origin adicine o link do seu repositório no github 
git push –u origin máster 
# Para baixar um repositório em um diretório vazio 
git clone https://github.com/pbattistella/lista-tarefas-html-css-js-localstorage.git *após origin adicione o link do seu repositório no github 
# Atualizar seus arquivos, baixando as novas funcionalidades  
git pull
