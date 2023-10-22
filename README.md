# Banco de Dados de Informações de Países

Este repositório contém um script SQL para criar um banco de dados que armazena informações sobre países. O banco de dados é projetado para permitir o armazenamento de detalhes sobre países.

## Arquivos SQL
Dentro do diretório .\Countries estão localizados os arquivos:

- `countries.sql`: Este script cria o banco de dados `paises`, as tabelas necessárias, e os dados de cada um.
- `Dockerfile`: Este arquivo parametriza a criação do container no Docker Desktop.
- `etl-tabelas`: Os arquivos .ktr foram gerados via etl e utlizados para construção do arquivo .sql para criação do banco de dados.  

## Uso

mysql:8.0.16
Docker Desktop