# Passo a Passo para criação e o envio de um arquivo no GitHub: Sessão 1

## Passos 1: Inicio 

1 - Logar com a sua conta no GitHub.

2 - Ao logar com a sua conta, clique no icone de **+** no canto superior direito da tela.

3- Quando clicar no simbolo de **+** irá aparecer  7 opções de cliques em uma caixinha, e dentre essas opções de um clique em **New repository**.

4 - Logo após você clicar em criar em **New repository**, vai abrir uma tela para você com a criação do repositorio. 

5 - Clique dentro do input aonde está escrito **Repository name** e de um nome para o projeto que deseja. Depois de dar o nome clique em **Description** aonde você dará uma descrição para seu
projeto, lembrando que essa parte será opcional.

6 - Indo para baixo, você vai se deparar com a 2 sessão **Configuration**, que seria a configuração de seu projeto.

7 - Na opção **Choose visibility**, terá **Public** ou **Private**, se você prefere que outras pessoas possam ver seu código deixe públic se não pode deixar privado que só você terá acesso.

8 - Em **Add README** terá as opções de **On e Off**, o README básicamente serve para você adicionar uma breve descrição sobre seu projeto, quais tecnologias, modo de rodar etc. Recomendo deixar ele **On** para ser adicionado essa descrição do seu projeto.

9 - A opção **Add .gitignore** será colocada na hora de produção do seu projeto, essa opção é de esconder alguma parte do seu projeto que você não quer que entre no seu GitHub, e com essa opção você pode ocultar.

10 - Logo quando for preenchida todas as opções, clique em **Create repository**.

#### Pronto agora você aprendeu a criar um arquivo no Github! [Acesse o GitHub por este Link](https://github.com/)



## Passo 2: Mandando os Arquivos para seu repositório

1 - Neste passo vou lhe ensinar a enviar um repositório com o Git, essa é uma técnica que você configura apenas 1 vez e usa para sempre.

2 - Primeiro passo é você instalar o sistema Git [neste link aqui](https://git-scm.com/install/windows).

3 - Após instalar o Git, abra o **Prompt de comando** em sua máquina, e digite esse primeiro comando **git --version ou git apenas**, se aparecer a versão ou aparecer varios comandos de git ele foi instalado com sucesso.

4- Agora vamos configurar seu git com seu computador e o **vscode**. Quando for aberto o Prompt de comando digite - **git config --global user.name "Seu Nome no GitHub"** e logo após - **git config --global user.email "seu.email@exemplo.com"**.

5 - Para verificar se deu certo digite esse comando - **git config --list**, se aparecer seu nome e email, ficou correto.


## Passo 3: Enviando o Projeto no VsCode

6 - Após ter feito as config no Git, entre no seu VsCode e abra o projeto que deseja mandar para seu GitHub.

7 - Quando entrar abra um novo **Terminal** e escreva os seguintes comando Git.
  - **git init** -> Para iniciar um novo repositório.
  - **git add .** -> Para adicionar arquivos no repositório.
  - **git commit -m "Breve descrição"** -> Para enviar o repositório com algum tipo de mensagem.

8 - Quando você escrever esses comando de inicialização, você irá até o GitHub, fazer o passo a passo de criar o repositório que foi ensinado anteriormente e quando clicar em **New repository**, irá abrir uma tela para fazer o carregamento dos arquivos e rolando para baixo você irá se deparar com alguns comandos git, e você vai copiar os seguintes comandos de lá:
  - **git remote add origin https://github.com/SeuNome/Exemplificacao-de-Criacao-de-um-Arquivo-GitHub.git**
  - **git branch -M main**
  - **git push -u origin main**
    
 **Lembrando que esses comando você copia diretamente do GitHub, não é necessario escrever eles manualmente.**

9 - Depois de você manda esse projeto você sempre pode fazer atualizações dele diretamente no vscode, sem precisar abrir o GitHub, utilizando esses comando você ATUALIZA O CODIGO:
  - **git add .**
  - **git commit -m "Breve descrição"**
  - **git push** -> apenas esses comando você já atualiza o projeto.
    
10 - Os passos 7 e 8 você realiza apenas para enviar algum tipo de projeto pro GitHub, e o Passo 3, 4 e 5 para configurar o Git e o passo 9 para ATUALIZAR o projeto no GitHub caso precise.



# Criação de README - Sessão 2

### Proposito

 - O README é uma forma de você expressar seu projeto antes de alguem ou algum recrutar fazer rodar ele, o README é a porta de entrada a chave do projeto, sem ele o projeto fica vazio e sem explicação. O público alvo atualmente do README são os recrutadores de empresas, no README o recrutador consegue ter uma noção do seu projeto e se ele está bem aplicado antes de abri-lo. O principal objetivo do README, é atrair atenção da pessoas que quer acessar seu projeto.

### Dados Fundamentais

 - 1 -> **Descrição de Projeto**: A descrição do projeto é fundamental para o recrutador saber quais tecnologias e aprendizados que você teve ao fazer este projeto. É um marco principal do seu README e deve ser bem feito.

 - 2 -> **Como Rodar**: Você colocar um passo a passo de como rodar seu projeto também é fundamental para seu README, para a pessoa que quiser testa-la saiba exatamente quais passos devem executar.

 - 3 -> **Status do Desenvolvimento**: As vezes a pessoas quer acessar o projeto porém da algum erro ao entrar, e nem é por causa de erro de código é por que o projeto ainda está em fase de teste e desenvolvimento então é muito importante deixar bem claro como esta o andamento.

 - 4 -> **Tecnologias**: O Projeto deve ter as tecnologias utilizas para o recrutador saber se você está realmente adequado para a vaga que está sendo ofertado, ou até para alguma pessoa ver quais tecnologias você sabe desenvolver.

 - 5 -> **Licença**: A pessoa que quiser acessar seu projeto va ter a ciencia que tem uma linceça e sabe que aquele projeto pertece a alguma coisa séria.

### Markdown 

- O markdown tem um importate gigantesca quando se trata de escrever um README e a documentação de um projeto, com o markdown você tem recursos que permite você deixar seu README bonito e organizado, com sessões de informações separadas por tópicos, tem a facilidade de colocar links de acessos, icones para melhor entendimento etc.



# Mapa das Atualizações (Commits e Pushes) - Sessão 3

**GitHub Online** -> Fazer a atualização pelo GitHub é muito pratico e necessário, porém não são todas as situações que precisa ser feito por la. Por exemplo:
- Você precisa fazer um alteração em uma documentação, usar o GitHub online vale mais apena do que fazer pelo Git, pois é uma alteração rápida e prática.
- Quando você precisa fazer um pequena alteração, mas o computador que você está utilizando não tem o Git configurado.

No entanto existe limitações, quando você está em um projeto muito grande o GitHub já não serve muito para alterações, pois você teria que substituir todos os arquivos ja existentes por outros novos, e levaria um tempo muito maior, que o Git resolveria em segundos.


**Git via Linha de Comando (Terminal)** -> Essa forma de atualizar projetos no terminal é muito mais prático e rapido, porém você deve saber no que está mexendo, pois errar algum comendo Git pode prejudicar todo seu projeto. No entanto utilizar o Git no seu dia a dia otimiza seu tempo no versionamento de código e consegue ter uma melhor organização em relação ao seu código. O fluxo de atualização se dar por mei de linhas de código no terminal da sua IDE, você pode atualizar, voltar código, ver as mudanças (status) do seu projeto.

**IDEs (Ex: Vs Code)** -> Já utilizei muito o Git para subir projetos grandes e projetos pequenos, no meu dia a dia o Git me ajuda a fazer o versionamento de código muito mais rápido e eu consigo manter o controle da minha produção e cada commit é uma parte que terminei do código, então consigo separar as Task que terminei e as que tem pendenca, também utilizando ferramentas de gestão de tarefas como o Jira.


**GitHub Desktop**: -> É o Git para quem não gosta de tela preta. Em vez de digitar comandos, você gerencia seu projeto com botões e cliques. Ele mostra o que você mudou em verde e vermelho e envia tudo para a nuvem com um clique no botão "Push".
