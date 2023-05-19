
01. Git e Versionamento

1- O que é git ?

Git é um sistema de versionamento de código, que guarda os registros de versão
como snaphots(fotos) de estados do projeto, além do referência,
referência/caminho para essa foto.
************************************************************
2.Instalação e configuração do git

Acesse o site oficial e faça o download do instalador do GIT para Windows. 
Depois de baixado, clique duas vezes no arquivo para iniciar o assistente 
de instalação. Basta seguir as instruções na tela, clicando em Next. 
Ao término, clique em Finish para concluir com êxito a instalação.


https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Configura%C3%A7%C3%A3o-Inicial-do-Git 
***********************************************************
3. Repositórios do git 

Para fazer download de um projeto basta executar o comando $ git clone, passando o endereço do repositório. Pode ser Github, Gitlab, Bitbucket, etc.

Esse comando é bem conhecido, mas ele está aqui por um detalhe que muitas pessoas não sabem: por padrão será criada uma pasta com o nome do projeto, mas você também pode no final do comando indicar qual o nome da pasta que você quer que seja criada.

$ git clone https://meu-endereco.com/meu-projeto.git minha-pasta



O GIT é consideravelmente simples de usar. Para começar, você pode criar um repositório ou conferir um já existente. Após a instalação, um simples git-init irá deixar tudo pronto. Da mesma maneira, o comando git clone pode criar uma cópia de um repositório local para um usuário.

************************************************************
4. Gravando mudanças no repositório

Comando usados nessa aula

1. cd + link do endereço da pasta no pc
2. gitclone + link do git
3. git init
4. git status 
5. git add .\README.md    
********************************************************************
05. Git diff, commit e rm
