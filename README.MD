
#01. Git e Versionamento

![image](https://github.com/chritianegozza/GitVersionamento/assets/72118415/e5b84e79-6a11-4677-ae96-ed3126c030cb)


********************************************************************************

#1- O que é git ?

Git é um sistema de versionamento de código, que guarda os registros de versão
como snaphots(fotos) de estados do projeto, além do referência,
referência/caminho para essa foto.
************************************************************
#2.Instalação e configuração do git

Acesse o site oficial e faça o download do instalador do GIT para Windows. 
Depois de baixado, clique duas vezes no arquivo para iniciar o assistente 
de instalação. Basta seguir as instruções na tela, clicando em Next. 
Ao término, clique em Finish para concluir com êxito a instalação.


https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Configura%C3%A7%C3%A3o-Inicial-do-Git 
***********************************************************
#3. Repositórios do git 

Para fazer download de um projeto basta executar o comando $ git clone, passando o endereço do repositório. Pode ser Github, Gitlab, Bitbucket, etc.

Esse comando é bem conhecido, mas ele está aqui por um detalhe que muitas pessoas não sabem: por padrão será criada uma pasta com o nome do projeto, mas você também pode no final do comando indicar qual o nome da pasta que você quer que seja criada.

$ git clone https://meu-endereco.com/meu-projeto.git minha-pasta



O GIT é consideravelmente simples de usar. Para começar, você pode criar um repositório ou conferir um já existente. Após a instalação, um simples git-init irá deixar tudo pronto. Da mesma maneira, o comando git clone pode criar uma cópia de um repositório local para um usuário.

************************************************************
#4. Gravando mudanças no repositório

Comando usados nessa aula

1. cd + link do endereço da pasta no pc
2. gitclone + link do git
3. git init
4. git status 
5. git add .\README.md    
********************************************************************
#05. Git diff, commit e rm

git diff é um comando Git multiuso que, quando executado, realiza uma função de comparação nas fontes de dados Git

O Git commit permite que você crie um commit, ou seja, você consegue guardar o estado do seu repositório naquele momento.
Exemplo:  Primeiro Commit. Agora faremos o primeiro commit do projeto. Basta utilizar o seguinte comando: git commit -m "meu primeiro commit".

O comando git rm pode ser usado para remover arquivos individuais ou uma coleção de arquivos. A principal função do git rm é remover arquivos rastreados do índice de Git. 
********************************************************************************
#6. Git log e restore

O comando git log exibe uma lista de todos os commits feitos em um repositório. Você pode visualizar o hash de cada confirmação do Git

O comando git restore restaura os arquivos que estão visiveis (working tree) para serem idênticos aos do commit atual (HEAD).
************************************************************************************
#07. Repositórios remotos

- git init
- git add .
- git status
- git commit -m "Adicionando os comandos novos"
- git branch -M main
- git remote add origin https://github.com/chritianegozza/Git.git
- Comando git push 
******************************************************************************
#8.GitHub



O que é git?
Git é um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de software, mas pode ser usado para registrar o histórico de edições de qualquer tipo de arquivo.

O que é github?

GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. Ele permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo. 
******************************************************************************
#9.Git Branch

O comando git branch permite criar, listar, renomear e excluir ramificações. Ele não permite alternar entre as ramificações ou reunir um histórico bifurcado de novo. Por esse motivo, o comando git branch é muito integrado com os comandos git checkout e git merge .
*****************************************************************************
#10.Merging branches

O comando git merge permite que você pegue as linhas de desenvolvimento independentes criadas pelo git branch e as integre em uma ramificação única.

