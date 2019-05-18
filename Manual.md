# Configurando o Git

## Instalando Git

	sudo apt install git

## Configurando Usuário e E-mail

	git config --global user.name "Myke Albuquerque Pinto de Oliveira"
	git config --global user.email "mykeapo@gmail.com"

## Configurando editor padrão

	git config --global core.editor emacs

## Visualizando as configurações

	git config user.name
	>> Myke Albuquerque Pinto de Oliveira
	git config user.email
	>> mykeapo@gmail.com
	git config --list
	>> user.name=Myke Albuquerque Pinto de Oliveira
	>> user.email=mykeapo@gmail.com
	>> core.editor=emacs

# Iniciando Repositório

	git init
	>> Initialized empty Git repository in /home/myke/Dropbox/git_course/.git/

# Comandos de Manipulação do Vesionamento

	git status
	git add read.md
	git commit -m "Add read.md"
	git reset HEAD 01\ configuração.txt
	git log --decorate
	git log --author "Myke"
	git log --author "Wil"
	git log --shortlog
	git shortlog
	git shortlog -sn
	git log --graph
	git show 
	git config --global user.name "Myke Albuquerque Pinto de Oliveira"

# Utilizando Repositórios Próprios Online

## SSH

	git remote add origin git@github.com:myke-oliveira/Git-course.git
	git push -u origin master

## Removendo Ligação

	git remote remove origin

## HTTPS

	git remote add origin https://github.com/myke-oliveira/Git-course.git
	git push -u origin master

# Clonando Repositórios de Tercerios

	git clone https://github.com/gianlima/ce083.git

# Teorema de Pitágoras

$$
a^2 = b^2 + c^2
$$