# Aula 00 - Git e GitHub
## _Principais comandos do Git_
## Instalação
colocar aqui como instalar o git

## Principais comando do git
Para visualizar as configurações globais do git
```sh
git config --global -e
```
```sh
# Para sair
# digita ctrl + c
:qa!
#para editar e salvar
# I para editar
# digita ctrl + c
:qw
```
Add configurações de nome e email no git
```
# seu nome da forma que você quer que seja registro no commit
git config --global user.name "Antonio Motta"

# seu email, de preferencia o mesmo registro no repositorio
git config --global user.email "fmotta.antonio@gmail.com"
```
Inicializando o git
```
git init
```
Para vizualizar o status do arquivos no git
```
git status
```
Legenda:
Vermelho: O git não encherga, ou seja, não vai entrar no git
Verde: o git enxerga

para ignorar os arquivos usar .gitignore
```
vim .gitignore
#dica: estudar uso do vim
```
