![image](https://user-images.githubusercontent.com/89918957/143512061-90e175fa-01c2-437b-b526-7ec4edd89793.png)


# Git e Github - Comandos

https://www.youtube.com/watch?v=kB5e-gTAl_s&t=857s

##
### git init
Para iniciar, aqui ele vai criar o arquivo "oculto" do git dentro da pasta. 
##
### git status
Para ver quais os arquivos ainda não subiram para o github.
##
### git add "nome do arquivo"
Para adicionar um por um.
##
### git add .  
Para adicionar todos os arquivos de uma só vez.
##
### git commit -m "mensagem do commit" 
Para fazer o primeiro commit, se essa for a primeira vez fazendo commit, ele vai pedir para configurar o usuario do github.
##
### git config --global user.email "seuemail.com"
Para configurar seu e-mail
##
### git config --global user.name "seu nome" 
Para configurar seu nome 
##
### git push
Para enviar essas alterações (aqui precisa informar o link do repositorio, aqui também você precisa definir a brach que os arquivos estão sendo enviados. 
##
### git remote add origin + definir a brach 
Colar o link do repositorio

<br>

# Verificando histórico de versão

- git reflog: mostra quantas versões foram criadas, na imagem abaixo, existem dois números o 1658aa4 é a primeira versão e o 53b2dfb é a segunda versão. 

![image](https://user-images.githubusercontent.com/89918957/143510146-f59ee885-de2e-4362-894d-089a910617bc.png)

- git reset --hard "número que você quer voltar a versão" 

![image](https://user-images.githubusercontent.com/89918957/143510121-18a8ebba-ad52-471a-8a9d-3bfbe02cbc11.png)

# Branch 

### git branch 
Para ver as branch disponiveis no repositorio 
##
### git branch + nome da branch
Para criar uma nova branch 

![image](https://user-images.githubusercontent.com/89918957/143510859-df458743-af4c-494b-ac10-b8c20903f43b.png)

### git checkout + nome da branch 
Para mudar de branch, perceba que na imagem acima, tem um * e a branch em verde é a que está sendo usada no momento, ou seja, tudo que você enviar para o repositorio, vai ir para essa branch. 

![image](https://user-images.githubusercontent.com/89918957/143510962-757fd5b3-20ee-4d87-ae74-4ca0e6ae01ec.png)

# Unir os códigos 

Para unir os códigos em uma brach só, chamamos de merge, e para isso você precisa seguir os seguintes passos 

- para verificar que o código é o atual: git pull
- verificar em qual brach está: git branch
- mudar para a branch: git checkout + nome da brach
- para puxar as atualizações: git merge + nome da brach que está o código 
- para enviar: git push 
