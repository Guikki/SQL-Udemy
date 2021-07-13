# SQL-Udemy

É aqui que eu irei anotar absolutamente tudo sobre o curso feito na Udemy sobre SQL, disponível em: https://www.udemy.com/course/aprenda-sql-do-zero/

_**The Start**_

**O que é Linguagem de Programação?**
É a forma como você conversa com o Computador, porque a máquina precisa de espeficidades para não haver mal entendidos.

_Perae, como assim?_

Vamos de exemplo: Se eu disser pra você: "Vá ao mercado e traga pão. Caso tenha leite, traga 6". E eis que você chega ao mercado e encontra leite lá. O que você trará pra casa?

a) Já que tem leite, vou levar 6 caixinhas de leite... essa foi _easy like a sunday morning_
b) Ué... Já que tem leite, eu vou levar 6 pães, oras!

Pode parecer absurdo, mas o computador nesse caso levaria... 6 pães. Exatamente!

Por isso que as linguagens de programação existem. Elas servem para **organizar as informações de forma clara, objetiva, do jeito que o computador possa entender!**

Teoricamente, você consegue fazer o que quiser com qualquer linguagem, mas você vai ter muito mais trabalho se não usar uma linguagem que foi feita para o que você quer.

E vale lembrar que não há uma linguagem de programação que é a maior de todas, vencedora máxima do universo. As linguagens de programação têm uma adaptabilidade, fazendo com que certas linguagens de programação sejam melhores pra algumas situações, e outras linguagens serão mais adequadas para outros objetivos.

Pronto. Já sabe o que é Linguagem de programação? Então, #PartiuSQL

**O QUE É SQL?**

_Structured Query Linguage_ , que significa **Linguagem Estruturada para Pesquisas** ou **Linguagem Estruturada para Perguntas**
- Para um Banco de Dados _estrutural_, essa é a linguagem padrão de **_adicionar, buscar, classificar, atualizar_** informações, além de poder **criar tabelas e estruturas de controle**
- A função desse curso é tratar a **linguagem SQL de forma abrangente**, não focando em um SQL específico (como Oracle, SQL Server, SQLite etc). Aqui, é uma **NOÇÃO GERAL** do que é SQL.
- Vale lembrar que SQL é uma linguagem de programação que existe **há 21 anos**, e ainda é usada; ao contrário de outras línguas, como o Clipper, que hoje está em desuso/ pouco uso.

**CONCEITOS IMPORTANTES PARA SQL**

**Banco de Dados**

É um local de  **armazenamento de informações**, onde você também pode **guardar dados de forma organizada e estruturada**,facilitando a busca, a atualização, o armazenamento e o manejo em geral dos dados.  Esses dados podem estar em vários formatos, como texto, números, datas, booleanos, nulo, dentre outros.

Uma forma simples de pensar em um "banco de dados" seria a **agenda telefônica**, que organiza as informações de forma organizada, em regra em ordem alfabética; nela, você pode colocar informações como **nome, telefone, endereço, aniversário**, entre outras informações.

A agenda é comparável a uma **tabela**, onde no exemplo acima, temos **uma TABELA com 4 pedaços de informação (nome, telefone, endereço e aniversário)**. Assim, para cada pessoa preenchida na agenda, haverão essas 4 informações preenchidas. A esse **pedaço de informação**, chamamos de **CAMPO** 

Ou seja: Se estivéssemos criando uma tabela em SQL com essas informações, a tabela teria o nome de **AGENDA TELEFÔNICA**, onde teríamos os **CAMPOS** de nome, telefone, endereço e aniversário.

E é essa a lógica de uma tabela: organizar as informações em campos, facilitando o manejo para quando a informação buscada for necessária. SQL, por sua vez, é a linguagem de programação que melhor se aplica para esse manejo, seja criando tabelas, adicionando campos, buscando as informações etc.
