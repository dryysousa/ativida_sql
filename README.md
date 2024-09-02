# atividade_sql
-- 1. Criar o banco de dados ESCOLA


CREATE DATABASE ESCOLA;

-- 2. Usar o banco de dados ESCOLA


USE ESCOLA;

-- 3. Criar a tabela ALUNO


CREATE TABLE ALUNO (
    ID INT AUTO_INCREMENT PRIMARY KEY,  
    nome VARCHAR(255),                  
    email VARCHAR(255),                 
    endereco VARCHAR(255)              
);
