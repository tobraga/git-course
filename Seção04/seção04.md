# Seção 04

## Criando um Repositório no Github

* Criar conta no Github e logar [Github](https://github.com/)
    - Criar Repositório;
    - Nome do Repostório;
    - Descrição (opcional);
    - Público ou Privado;
    - Adicionar arquivo "Readme";
    - Adicionar um licensa.

**Obs:** Vale ressaltar que, para iniciar um repositório do Github trazendo os arquivos de uma máquina local, é importante realizar os seguintes procedimentos:
* Deixar o repositório público;
* Não adicionar o arquivo "Readme" no Github.

## Criação e adicionando chave SSH

Para licar um máquina ao Github por meio do ssh, basta seguir os seguintes passos:
* Caso não tenha uma chave pública SSH: 
    1. Abra o Git Bash
    2. Cole o código: `$ ssh-keygen -t ed25519 -C "your_email@example.com"` Substituindo o endereço de email.
    3. pode utilizar o comando para listar as chaves: `cd ~/.ssh` e `ls`
    4. `cat + <nome da chave publica`
    5. copie e cole a chave no github, em:
        1. Settings
        2. SSH and GPG keys
        3. New SSH key
        4. Adicione um título e a chave


## Licando Repositório Local com o remoto
Após criar um repositório, descrito no primeiro passo a passo desse documento, o GitHub mostra uma série de formas de ligar os repositórios, dentre elas o seguinte código:

`git remote add origin git@github.com::<nome do usuário>/<nome do repositorio.git`
`git push -u origin master`

**Obs:** O nome "origin" pode ser mudando
