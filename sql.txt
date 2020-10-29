create database escola_futebol
create table matricula(
id bigint not null,
nome varchar not null,
nome_pai varchar not null,
nome_mae varchar not null,
endereco  bigint not null,
primary key (id)
);
create table professor(
id bigint ,
nome char,
primary key (id)
);
create table aluno(
id bigint,
nome char ,
primary key (id)
);