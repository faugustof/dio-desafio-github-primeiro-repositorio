#Tutorial de Git e GitHub

#####  Git e GitHub, um sistema do controle de versão e um repositório online para os nossos projetos.


## O que é Git?

##### Git é um sistema de código aberto e gratuito para controle de versão, criado em 2005 por Linus Torvalds enquanto desenvolvia o Kernel do Linux. Controle de versão é um sistema que permite gravar alterações em arquivos ao longo do tempo, portanto, podemos visualizar versões específicas desses arquivos posteriormente.

##### Geralmente, acontece de termos muitos desenvolvedores trabalhando numa mesma base de códigos, então um sistema de controle de versão como o Git é necessário para diminuir conflitos entre o código de cada desenvolvedor.


## O que é GitHub?

##### Se você vai utilizar Git, é necessário armazenar seu repositório em algum lugar. Existem duas formas de se fazer isso, offline, no seu próprio computador, ou online, em alguma plataforma como GitHub, BitBucket ou GitLab.

##### É exatamente para isso que o GitHub serve, para armazenar seus repositórios, ele é o “Google Drive dos códigos”.

## Configuração do ambiente

##### Primeiramente, é necessário possuir o Git instalado no seu computador e uma conta no GitHub. Você pode baixar o Git no site oficial, basta selecionar o seu sistema operacional e seguir o guia de instalação.

##### No Linux, recomenda-se instalar o Git via gerenciador de pacotes, nesse caso, você pode ir até essa página e executar no seu terminal o comando específico da sua distribuição.

##### Depois de instalar o Git, é necessário configurar o seu nome e e-mail que serão exibidos em seus commits, para isso é só digitar no terminal os comandos abaixo:

##### git config --global user.name "Seu Nome" 
##### git config --global user.email "seu-email"