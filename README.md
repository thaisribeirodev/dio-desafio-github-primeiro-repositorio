# Desafio de Projeto sobre Git/GitHub da DIO
Repositório criado para o Desafio de Projeto.

Curso realizado na plataforma [DIO - Digital Innovation One](https://web.dio.me) - "Criando seu Primeiro Repositório no GitHub para Compartilhar Seu Progresso" 

## Anotações
```
git init //iniciar o git no respositório atual
git add * //para incluir o que será submetido
git commit -m "Msg do que se trata o commit" //submeter no repositório local
git status //visualizar o status atual, se há arquivos para adicionar ou comitar
```
```
git config --list //visualizar as configurações de conta/usuário do seu git

git config --global --unset user.email
git config --global --unset user.name
//comandos acima resetam o usuário que estava configurado antes

git config --global user.email "meuemail@gmail.com"
git config --global user.name "Thaís Ribeiro"
//comandos acima inserem os dados novamente do usuário
```
```
//após alterações no código:
git add *
git status
git commit -m "texto..."
git push origin master

/** Quando você tenta empurrar (push) o código para o GitHub e o seu commit não representa o estado mais atual do repositório o git irá: */
R.: Pedir para você fazer um pull e depois um push.
git pull origin master
git push origin master
```
```
//clonar um respositório para a máquina local
git clone https://github.com/usuario/projeto.git
```