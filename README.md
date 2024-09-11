# Análise de Vagas de Emprego em T.I.

## Autor
Vinícius Nário Vasconcelos  
Data: 10/09/24

## Índice
- [Análise de Vagas de Emprego em T.I.](#análise-de-vagas-de-emprego-em-ti)
  - [Autor](#autor)
  - [Índice](#índice)
  - [Introdução](#introdução)
    - [1.1 Declaração do Problema](#11-declaração-do-problema)
    - [1.2 Abordagem Metodológica](#12-abordagem-metodológica)
    - [1.3 Abordagem Proposta](#13-abordagem-proposta)
    - [1.4 Benefícios da Análise](#14-benefícios-da-análise)
  - [Tratamento Inicial dos Dados](#tratamento-inicial-dos-dados)
    - [Carregamento e Mesclagem dos Dados](#carregamento-e-mesclagem-dos-dados)
    - [Filtragem das Vagas de T.I.](#filtragem-das-vagas-de-ti)
  - [Visão Geral do Dataset](#visão-geral-do-dataset)
    - [Fonte dos Dados](#fonte-dos-dados)
    - [Importação e Limpeza de Dados](#importação-e-limpeza-de-dados)
    - [Conjunto de Dados Final](#conjunto-de-dados-final)
  - [Análise Geral do Dataset](#análise-geral-do-dataset)
    - [Distribuição de Vagas por País](#distribuição-de-vagas-por-país)
    - [Distribuição de Vagas por Posição](#distribuição-de-vagas-por-posição)
  - [Artigo Publicado](#artigo-publicado)

## Introdução

### 1.1 Declaração do Problema

A tecnologia da informação (T.I.) é um setor crucial que impulsiona a inovação em diversas indústrias. Este projeto busca analisar ofertas de emprego em T.I., compreendendo como estão distribuídas geograficamente, quais habilidades são mais requisitadas, e como o mercado está estruturado em termos de modalidades de trabalho e níveis de senioridade. Utilizando um dataset de 1,3 milhões de vagas do LinkedIn, o objetivo é proporcionar uma visão detalhada do mercado de T.I. nos Estados Unidos, Austrália, Canadá e Reino Unido.

### 1.2 Abordagem Metodológica

O dataset "1.3M Linkedin Jobs & Skills (2024)" disponível no Kaggle será consolidado, filtrado e analisado, focando nas vagas relacionadas à área de T.I.

### 1.3 Abordagem Proposta

Utilizaremos a chave `job_link` para unir três arquivos distintos e, em seguida, aplicaremos filtros com base em títulos de trabalho comuns à T.I.

### 1.4 Benefícios da Análise

Os resultados fornecerão insights sobre as tendências de emprego, habilidades mais demandadas, modalidades de trabalho e níveis de senioridade no setor de T.I.

## Tratamento Inicial dos Dados

### Carregamento e Mesclagem dos Dados

O primeiro passo é consolidar três arquivos de dados (`jobSkills.csv`, `linkedin_job_postings.csv`, `job_summary.csv`) em um único dataset, utilizando a coluna `job_link` como chave. Em seguida, aplicamos uma filtragem específica para vagas de T.I.

### Filtragem das Vagas de T.I.

A filtragem foi feita com base em uma lista de títulos de trabalho comumente associados à área de T.I., e o dataset filtrado foi salvo como `it_jobs.csv`.

## Visão Geral do Dataset

### Fonte dos Dados

Os dados utilizados são provenientes de um dataset do LinkedIn, que contém 1,3 milhões de vagas de emprego e habilidades relacionadas ao setor de T.I., coletados em 2024.

### Importação e Limpeza de Dados

Os dados passaram por uma limpeza cuidadosa, removendo caracteres especiais e valores ausentes para garantir a integridade da análise.

### Conjunto de Dados Final

O dataset consolidado fornece uma visão abrangente das oportunidades de emprego em T.I. nos países analisados.

## Análise Geral do Dataset

### Distribuição de Vagas por País

A maior parte das vagas de T.I. está concentrada nos Estados Unidos, seguidos por Reino Unido, Canadá e Austrália. Esta distribuição oferece insights sobre o mercado de trabalho em cada região.

### Distribuição de Vagas por Posição

A análise revela uma forte demanda por operadores de computador e programadores, refletindo a necessidade de habilidades operacionais e de desenvolvimento de software.

## Artigo Publicado

Para uma análise mais detalhada das tendências de emprego no mercado de T.I., acesse o artigo publicado [aqui](https://rpubs.com/Viinario/analise-tendencias-mercado-ti-2024).