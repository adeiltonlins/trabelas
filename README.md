# trabelas
CREATE TABLE produtos10 (
cod_prod integer UNIQUE NOT NULL,
nome text,
preco numeric
);
CREATE TABLE produtos11 (
cod_prod integer PRIMARY KEY,
nome text,
preco numeric
);
– Se mais que um atributo forma a chave primária:
CREATE TABLE exemplo (
a integer,
b integer,
c integer,
PRIMARY KEY (a, c)
);
