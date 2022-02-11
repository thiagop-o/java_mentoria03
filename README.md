<h1> Mentoria Java - Programa 03 </h1>

<h2> Api - Repositorio </h2>

<hr/>

<p>Neste terceiro desafio, iniciaremos a criação de um serviço, onde contará com vários microsserviços, o segundo deles será o de REPOSITORIO. 

Nossa API se comunicará com um banco de Dados NoSQL(Mongo) e nele teremos a seguinte estrutura:</p>


TABELA CARDAPIO 


Campo           |    Tipo                | Exemplo    | 
---------       | -------                | ------     |  
chaveParticao   | String(pk)             | Hamburger  | 
chaveFiltragem  | String(sk)             | Bovino     | 
dataAtualizacao | LocalDate(yyyy-MM-dd)  | 2022-02-10 | 
pao             | Enum                   | Brioche    | 
acompanhamentos | List                   |            | 


LISTA ACOMPANHAMENTOS


Campo           |    Tipo           | Exemplo| 
---------       | -------           | ------ | 
alface          | Quantidade(int)   | 200    |
tomate          | Quantidade(int)   | 200    |
queijo          | Quantidade(int)   | 200    | 
picles          | Quantidade(int)   | 200    |





<p>Lembrando que esse repositório iremos realizar as consultas e gravações
logo precisaremos dos endpoints criados</p>

- Get 
- Post 
- Delete 
- Put


<p>DOD (definition of done) </p>

- Cobertura de testes >= 85%
- Registros no banco de dados
- Validação dos casos

<p>Qualquer dúvida estarei no Discord para Auxilia-los</p>

![discord logo](https://img.icons8.com/office/16/000000/discord-logo.png)  [thiagocrow#9854](https://discordapp.com/users/412300823234609153)