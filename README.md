# Brazilian-E-commerce-Project

A ideia do repositório é simular algumas das etapas de criação de um projeto que segue a metodologia de Business Intelligence de um E-COMMERCE. As etapas realizadas foram a de **ETL** (Extract, Transform and Load), desenvolvidas na ferramenta *Pentaho Data Integration(PDI)* e Data Visualization no *Microsoft Power BI*.

## 1.Extract

A extração dos dados foi realizada de vários arquivos no formato .csv contidos nesse [repositório](https://github.com/levisouuza/Brazilian-E-commerce-Project/tree/master/DataSet/brazilian-ecommerce). 

## 2.Transform

A transformação dos dados foi dividida entre transformações das tabelas fato e dimensão, conforme metodologia.

![job](https://github.com/levisouuza/Brazilian-E-commerce-Project/blob/master/EtlBrazilianEcommerce.png)

## 3.Load

A carga de dados foi realizada em um banco de dados PostgreSql, onde foi montado nosso *Data Mart* E-commerce.

![dm](https://github.com/levisouuza/Brazilian-E-commerce-Project/blob/master/postgresBrazilianEcommerce.png)



