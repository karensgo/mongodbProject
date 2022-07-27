# mongodbProject

MongoDB

1 - Crie uma coleção chamada Filmes que contenha os seguintes campos:
- Nome, Diretor, Elenco, Ano, Prêmios
E os seguintes documentos: (Não escreva os dados à mão e sim copie e cole!)
NOME DIRETOR ELENCO ANO PRÊMIOS
Duna Denis Villeuneve Timothée Chalamet,
Rebecca Ferguson,
Zendaya

2021 0

Central do Brasil Walter Salles Fernanda
Montenegro,
Vinicius de Oliveira

1998 20

Cidade dos Sonhos David Lynch Naomi Watts, Laura
Elena Harring

2001 18

King Kong Peter Jackson Naomi Watts, Jack
Black, Adrien Brody

2005 10

Bela Vingança Emerald Fennel Carey Mulligan, Bo

Burnham

2020 22

SDA: A Sociedade
do Anel

Peter Jackson Elijah Wood, Ian
McKellen, Liv Tyler

2001 15

Shrek Andrew Adamson
Vicky Jenson

Mike Myers, Eddie
Murphy, Cameron
Diaz

2001 10

Cidade de Deus Fernando Meirelles,
Kátia Luind

Alexandre
Rodrigues, Leandro
Firmino da Hora

2002 15

Pânico Wes Craven Neve Campbell,
Courtney Cox,
David Arquette

1996 6

2 - Busque filmes lançados entre 1997 e 2004.
3 - Busque filmes de 2001 ou que comecem com a letra D.
4 - Busque filmes lançados dirigidos pelo Peter Jackson ou pelo Walter Salles usando $in.
5 - Busque filmes lançados entre 2002 e 2021 e que contenham as atrizes Naomi Watts ou Carey Mulligan.
6 - Busque todos os filmes que não sejam entre 2001 e 2005.
7 - Conte quantos filmes foram lançados em 2001.
8 - Selecione apenas o elenco numa distinct.
9- Selecione os filmes lançados em 2001, apresentando seu nome e diretor apenas, em ordem decrescente,
limitando a dois resultados.
10 - Crie uma index usando o ano como referência.
11 - Some os prêmios de todos os filmes.
12 - Na coleção `sample_mflix` do Mongo Atlas DB, crie uma consulta que retorne os filmes com os seus
comentários utilizando o estágio de agrupamento (e.g.: `$lookup`).
