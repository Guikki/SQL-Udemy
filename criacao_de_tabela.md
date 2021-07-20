Agora que você já tem os materiais do **SQLite** baixados, vamos começar fazendo uma tabela. Vale lembrar que eu tô criando de um **_windowns 10_** aqui, ok?

> **_FIRST STEPS_**

- Vamos começar iniciando o Prompt de comando. para isso, comece **segurando a tecla WINDOWS em seu teclado**, e junto disso a tecla **R**,para abrir o **_EXECUTAR_**. 
Porém, você também poderá pesquisar o **Prompt de Comando** na barra do Windows, ok?

 - depois disso, você digita **cmd** na barrinha de execução. 

Aí vai ficar assim:

![image](https://user-images.githubusercontent.com/86801366/126260272-88d20a37-93a6-4df2-81fd-b98e72619608.png)

dê um enter que você entrará no Prompt de comando, assim:
![image](https://user-images.githubusercontent.com/86801366/126260324-23d1f6fa-d625-46c2-81d7-2fa3c87db129.png)

Nesse exercício, iremos construir as tabelas na área de trabalho. Dessa forma, a gente deve entrar na área de trabalho pelo prompt de comando.

Lembra que no material anterior eu mostrei sobre o One Drive? Agora ele será importantíssimo!

> **Entrando na Área de Trabalho**

 - Existe um comando de entrada chamado **CD**; esse comando é responsável para que você entre nas pastas sem usar o mouse.

Em meu caso, optei usar o One Drive, serviço de nuvem da Windows, para aplicar nele minha área de trabalho.

 - Assim, o comando a ser aplicado é o **cd OneDrive**, que eu devo digitar no prompt de comando, ficando dessa forma.

![image](https://user-images.githubusercontent.com/86801366/126260510-a29810c6-8679-4c62-aded-541b1b021388.png)

 - Deu certo aí também? Agora sim, é só colocar o **cd "Área de Trabalho"** que você estará em sua área de trabalho visível na interface do seu PC.

![image](https://user-images.githubusercontent.com/86801366/126260874-b7ce594a-a954-4512-92be-85fe13bbb229.png)

É importante lembrar que esses comandos estão acessíveis dessa forma por eu configurar meu computador no idioma **PT-BR**. Caso você esteja configurado em outro idioma
(como o inglês, por exemplo), tente digitar **cd Desktop** ao invés de **cd "Área de Trabalho"**

Também vale lembrar que o nome **Área de Trabalho** está acompanhado das aspas por ter espaço entre as palavras. Assim, com as aspas, o computador reconhece que deve buscar o nome completo, ir até o fim e chegar na palavra "Trabalho", ao invés de limitar sua busca na palavra "Área", e parar por aí, porque após "Área" tem um espaço. 

> **_ENTRANDO NO SQLITE_**

Agora que você está em sua área de trabalho, vamos entrar no SQlite. 

- Você deve usar o comando **"sqlite3 aula.sqlite"**, tal como escrevi, só que **SEM AS ASPAS**. Note bem que aqui você **NÃO PRECISA USAR O CD** antes. Notou?
Com tudo dando certo, vai ficar assim pra você.

![image](https://user-images.githubusercontent.com/86801366/126261237-07b0ad52-714e-419a-bcc3-4646dcb0f466.png)

> Não é obrigatório você colocar o nome de **aula**, nem escrever a extensão **.sqlite**. Eu estou fazendo isso apenas pra critério organizacional.

> Também não é obrigatório você salvar a sua tabela na sua Área de Trabalho. Eu estou fazendo isso pra simplificar a visualização do processo, além de ser lembrado onde parei
sempre que inicio o computador.

- No momento que você fizer isso, a partir de agora, seus comandos escritos no **Prompt de Comando** estarão sendo registrados no arquivo que você acabou de criar, o 
**aula.sqlite**.

>**_DDL - Data Definition Language_**

A **Linguagem de Definição de Dados** é por onde começaremos, são os comandos utilizados para **criar dados**, como o próprio nome sugere.

- No nosso exemplo, iremos mirar a agenda tratada nas anotações anteriores, por ser um método simples e fácil de você memorizar, afinal, todo mundo um dia manuseou uma agenda.

Então, o comando a ser inserido é o **CREATE**, que usaremos para **CRIAR** a nossa agenda. Fácil? Vamos lá!

- Uma vez já dentro do sqlite, o comando a ser inserido é o **create table agenda**, que nesse primeiro momento usaremos com apenas dois campos: **nome** e **telefone**.

- O **nome** é um comando de **texto**, que por isso será salvo com o formato **text**; o **telefone**, neste exemplo será um texto também, por não envolver operações matemáticas. Dessa forma, vai ficar +/- assim:

![image](https://user-images.githubusercontent.com/86801366/126262082-7c2d5b76-933b-4f2d-a59d-9f43575e448d.png)

- O comando **.tables** foi utilizado como um verificador. É importante você lembrar que **os comandos iniciados com . são próprios do sqlite, e não gerais de SQL**

- Com o **.tables** você estará basicamente perguntando: "Sistema, existe alguma tabela aqui?", e assim enxergar que o sistema retorna informando que existe uma tabela sim, chamada **agenda**

> Bora criar mais uma, dessa vez com números?

Vamos fingir que estamos criando uma tabela simples, de uma pequena escola, que tá buscando registrar **matrícula**, **nome** e **cidade**.

- A **matrícula** será salva como **número inteiro**, e assim, o comando é **integer**. Para as demais, manteremos o comando de salvar em texto, ficando dessa forma:

![image](https://user-images.githubusercontent.com/86801366/126262534-986bfcab-8dea-4857-99bd-8568bdd65ac4.png)

Conseguiu?

> Vamos para uma terceira tabela agora?

Imagine que você tá criando uma tabela pra algum mercadinho, ou pequena loja, que quer manter um registro dos seus produtos. 

- Aqui, precisaremos salvar **código do produto**, como um número inteiro; o **nome do produto**, como texto; e a **quantidade do produto**, como número inteiro. Aposto que agora, você já consegue bem mais fácil do que na primeira tabela, a **agenda**. Confere aí se ficou igual:

![image](https://user-images.githubusercontent.com/86801366/126263028-2b54a381-d036-4489-8eae-a7c640f2dabd.png)

Conseguiu? **PARABÉNS!** Você usou o comando **CREATE** muito bem! 

Pode usar o .exit pra sair do sqlite, e fechar o prompt de comando (seja digitando exit no próprio prompt, ou seja fechando clicando no X mesmo)

- Lembrando que nossas tabelas até aqui ainda estão vazias, tá? Apenas **criamos as tabelas** e **projetamos os tipos de dados** que pretendemos colocar dentro das tabelas
