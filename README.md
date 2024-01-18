# Builders - Business Intelligence challenge

## Descrição
Esse projeto é referente ao Desafio Técnico da Builders. O objetivo é criar um ETL para extração de dados locais da empresa disponibilizados, transformar e limpar os dados 
e posteriormente criar um dashboard com modelagem dimensional starschema.

## Requisitos do projeto

- Construção de ETL carregando dados de banco MySql e MongoDB.
- Construir starschema com o output do ETL. 
- Construir dashboard com visões pedidas.

## Finalidade

Os dados só estarão disponíveis para a realização do processo seletivo da Builders, os dados e acesso aos banco não são disponíveis para o publico.

## Instruções
 
- A etapa de ETL foi feita em python, com a ferramenta jupyter notebook localmente. 
- A lista de pacotes instalados estão dispostos nas primeiras linhas.
- Optei pelo output do csv que posteriormente será utilizado pelo dashboard para a construção das visões.

## Visões do dashboard

Crie um dashboard dos dados de multas e Covid (bases de dados MySql e MongoDB), no qual contenha as seguintes visões:

- Visão acumulada por período. (multas e Covid)
- Visão comparativa do período anterior. (multas e Covid)
- Classificação por ranking do maior para o menor por tipo de multa e estado.
- Classificação por ranking do maior para o menor por quantidade de mortes por Cidade/Estado.

## Importante

Para que o Power BI leia os dados csv é necessário mudar o caminho que o Power BI ler os csv´s. 
Criei uma consulta nula nos dados do Power BI com o caminho dos dados.
Para alterá-lo vá em **dados** e procure pela consulta **caminho**. Posteriormente cliquei com o botão direito e encontre **editar consulta**. 
Posteriormente altere o caminho com o nome da pasta que está salva os arquivos csv. 
