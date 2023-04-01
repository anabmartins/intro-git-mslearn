# Comandos GIT 
# definir usuário e email 
git config --global user.name “nomeDoSeuUsuário” 
git config --global user.email “seuemail@email.com” 
# Crie um novo repositório no github 
## Criando vínculo entre arquivos locais com o github 
git init 
git add . 
git commit -m “uma mensagem” 
git remote add origin https://github.com/anabmartins/intro-git-mslearn *após origin adicine o link do seu repositório no github 
git push –u origin master 
# Para baixar um repositório em um diretório vazio 
git clone https://github.com/anabmartins/intro-git-mslearn *após origin adicione o link do seu repositório no github 
# Atualizar seus arquivos, baixando as novas funcionalidades  
git pull
