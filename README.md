# SQL_GuardaRoupas
Atividade desenvolvida em sala, com o auxilio do professor

CREATE TABLE tecnico (
ID bigint generated always as identity primary key not null,
coluna1 text,
coluna2 varchar(15),
coluna3 int
);
--entidade geralmente se refere a tabela que vocês querem criar--
--coluna1 foi colocada como texto(text) que é a premisssa mais básica de escrita de coluna--
--coluna2 foi utilizado o varchar para mostrar como voce limita a quantidade de caracteres--
--coluna3 se refere ao item de configuracao mais basico para inserir numeros(int esta associado a inteiro, ou seja, um numero INTeiro)--
