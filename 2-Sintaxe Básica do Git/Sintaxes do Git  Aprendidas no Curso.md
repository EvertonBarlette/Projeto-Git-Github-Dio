### <u>git init</u>

#### Comando usado para inicializarmos um repositório vazio no git.

### <u>git config --global</u>

#### Comando usado para configurar um repositório de forma global.

#### Exemplo : git config --global user.email "email@email.com" (Essa linha de comando está definindo um endereço de email que irá valer para todos os repositórios locais (maquina local (pc))).

### <u>git add *</u>

#### Adiciona todos os arquivos e diretórios deixando-os preparados para serem enviados para o repositório local.

### <u>git commit -m "mensagem"</u>

#### Esse comando envia todos os arquivos e diretórios contendo uma mensagem ,informações do autor ,data e hora para o repositório local os deixando prontos para serem enviados para o repositório remoto.

#### Exemplo : git commit -m "commit inicial" (Esse será o titulo dessa versão do repositório local , podendo a mesma a cada atualização de informação levar uma mensagem diferente descrevendo ali quais as mudanças foram feitas naquele repositório) .

### <u>git remote add</u>

#### Através dessa liha de comando mas um nome criado após ela, no nosso caso o nome será "origin" , mais o endereço do nosso github, isso irá gerar  o nosso repositório remoto, e é atraves dele que as informações do nosso repositório local são tranferidas para o  nosso github.

#### Exemplo : git remote add origin https://github.com/fulano/nome-do-repositorio.git.

### <u>git push</u>

#### Finalmente com essa linha de comando mais o apelido que colocamos no nosso endereço http (origin) conseguimos enviar uma cópia de tudo que tem no nosso repositório local para o nosso repositorio remoto lá no github e esse repositório remoto sendo publico ele fica disponível para toda a comunidade do github ver o que estamos desenvolvendo.

#### Exemplo : git push origin master (o termo "master" significa que estamos enviando os dados para o branch principal do nosso repositório remoto) .

### <u>git pull</u>

#### Essa linha de comando é usada geralmente quando dois ou mais usuários estão trabalhando no mesmo repositório e esses usuários fazem mudanças no mesmo arquivo sendo que a cada mudança enviada ao repositório remoto é lançado um novo versionamento, quando esse segundo usuario local tenta mandar a sua versão do arquivo o github apresenta um conflito.  E o git pull é o comando que integra essas mudanças e envia para o repositório local desse usuário , para ele fazer as devidas edições para resolver o conflito e enviar os dados de volta ao repositório remoto.

#### Exemplo : git pull origin master (Essa linha de comando integra as duas versão para que o usuario faça as devidas edições no arquivo) .

### <u>git clone</u>

#### E por fim essa linha de comando clona o repositório remoto do github para o nosso repositório local que fica na nossa maquina local (pc) .

#### Exemplo : git clone https://github.com/fulano/nome-do-repositorio.git.







####   



###   

