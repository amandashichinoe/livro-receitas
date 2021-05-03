# Livro de receitas :woman_cook:

Olá! Bem-vindx ao meu livro de receitas

- Macarrão à Carbonara



## Repositório criado no curso Introdução ao Git e GitHub da Digital Inovation One

### Aprendizados :books:

#### Comandos básicos do terminal

| Windows                    | Linux                  | Função                                                       |
| -------------------------- | ---------------------- | ------------------------------------------------------------ |
| dir                        | ls                     | Lista as pastas do diretório atual                           |
| cd nome_diretorio          | cd nome_diretorio      | Navega até a pasta (diretório) desejada                      |
| cd ..                      | cd ..                  | Retrocede um nível de diretório                              |
| cls                        | clear                  | Limpa o terminal                                             |
| mkdir nome_diretorio       | mkdir nome_diretorio   | Cria uma nova pasta                                          |
| echo hello                 | echo hello             | Imprime no terminal o texto hello                            |
| >                          | >                      | redirecionador de fluxo                                      |
| echo hello > hello.txt     | echo hello > hello.txt | Irá criar um arquivo txt om o nome hello, cujo conteúdo é a palavra hello |
| rmdir nome_diretorio /S /Q | rmdir -rf              | Remove recursivamente o diretório exibir mensagem de confirmação |



### Primeiros comandos com o Git

#### Configurando o git

**git config --list** - lista todas as configurações aplicadas no git

Caso o Git já esteja configurado e você deseja alterar essas configurações, utilize os comandos:

**git config --global --unset user.email** - remove o e-mail configurado

**git config --global --unset user.nickname** - remove o nome de usuário configurado

Para configurar e-mail e nome de usuários utilize os comandos:

**git config --global user.email** _seu_email_aqui_ - configura o email 

**git config --global user.nickname** _seu_usuario_github_aqui_ - configura o nome de usuário



#### Criando um repositório

1. Crie um repositório no GitHub sem adicionar um arquivo README.
2. Copie o link do seu repositório.
3. Na sua máquina, vá até a pasta onde estão os arquivos que você deseja enviar para o repositório remoto.
4. Clique no botão esquerdo do mouse e selecione a opção "Git Bash here".
5. No terminal do Git utilize os seguintes comandos:

**git init** - Inicia o repositório

**git status** - aqui aparecerão os arquivos que ainda não foram "empacotados" para serem enviados para o repositório remoto

**git add** _nome_arquivo_ - adiciona um arquivo específico

ou

git add *  ou **git add .** - adiciona todos os arquivos

**git commit -m** _"primeiro commit"_

**git remote add origin** _insira_link_repositorio_remoto_ - aponta para onde o repositório deve ser enviado

**git push origin master** - Faz o upload dos arquivos do repositório local para o repositório remoto



#### Adicionando mais arquivos ao repositório

1. Vá até a pasta onde estão os arquivos do repositório.

2. Clique com o botão esquerdo do mouse e na opção "Git Bash here".

3. Digite os seguintes comandos no terminal:

   **git status** (aqui irão aparecer os arquivos que estão no repositório local e não estão no repositório remoto e arquivos que foram modificados localmente)

   **git add** _nome_arquivo_ - adiciona um arquivo específico

   ou

   **git add * ** ou **git add .** - adiciona todos os arquivos

   **git commit -m** _"descrição do commit"_

   **git push origin master** - Faz o upload dos arquivos do repositório local para o repositório remoto

   Caso algum este repositório tenha sido modificado remotamente, será necessário clonar o repositório remoto antes de adicionar mais arquivos.

   

#### Clonando um repositório remoto para o repositório local

1. Copie o link do repositório remoto que deseja clonar.

2. Vá até a pasta aonde deseja fazer o download do repositório para a máquina.

3. Clique com o botão esquerdo do mouse e na opção "Git Bash here".

4. Digite o seguinte comando no terminal do Git, para colar o link copiado do repositório use a tecla _Insert_:

   **git clone** _link_repositorio_remoto_ 





