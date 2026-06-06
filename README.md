✈️ Análise da Segurança Operacional na Aviação Brasileira

📊 Sobre o Projeto
Este projeto apresenta uma análise de dados sobre ocorrências aeronáuticas registradas no Brasil.
A análise foi desenvolvida utilizando Power BI, com base em dados públicos disponibilizados pelo Centro de Investigação e Prevenção de Acidentes Aeronáuticos (CENIPA). O objetivo é explorar padrões, tendências e fatores associados às ocorrências aeronáuticas por meio de visualizações e dashboards interativos.

🎯 Objetivo
Explorar e visualizar dados de ocorrências aeronáuticas no Brasil, buscando identificar padrões relacionados à segurança operacional, distribuição geográfica, classificação das ocorrências e fatores contribuintes.

🗂 Fonte dos Dados
Os dados utilizados neste projeto são provenientes da base pública do Sistema de Investigação e Prevenção de Acidentes Aeronáuticos (SIPAER).

Fonte oficial:
CENIPA - Dados Abertos

A base contém informações detalhadas sobre:
Data da ocorrência
Localização da ocorrência
Estado e cidade
Classificação da ocorrência
Tipo da ocorrência
Aeródromo
Fatores contribuintes
Aspectos operacionais e humanos relacionados ao evento

Essas informações permitem realizar análises sobre o comportamento das ocorrências aeronáuticas e seus principais fatores associados.

🛠 Ferramentas Utilizadas
Power BI — Criação dos dashboards e análises visuais
Power Query — Tratamento e transformação dos dados
DAX — Construção de medidas e indicadores
CSV — Formato dos conjuntos de dados utilizados
GitHub — Versionamento e documentação do projeto

📊 Dashboard Desenvolvido
Dashboard de Segurança Operacional da Aviação Brasileira

O painel apresenta uma visão geral das ocorrências aeronáuticas registradas no Brasil, permitindo identificar padrões temporais, geográficos e operacionais.

Principais visualizações presentes no dashboard
Ocorrências por Estado
Classificação das Ocorrências
Fatores Contribuintes
Tipos de Ocorrência
Evolução das Ocorrências por Ano

O objetivo é compreender como as ocorrências estão distribuídas e quais fatores possuem maior influência na segurança operacional da aviação brasileira.

🖼 Visualização do Dashboard
Dashboard de Segurança Operacional

Visualização do dashboard desenvolvido no Power BI apresentando a distribuição das ocorrências aeronáuticas registradas no Brasil.

Analise_Aviacao_Civil_Brasileira.PNG

🔎 Principais Insights
Distribuição Geográfica
São Paulo apresenta o maior número de ocorrências registradas, seguido por Rio de Janeiro e Minas Gerais.
Os estados com maior movimentação aérea concentram maior volume de ocorrências.

Classificação das Ocorrências
Os incidentes representam a maior parte dos registros analisados.
Os acidentes correspondem a uma parcela menor do total de ocorrências, indicando que a maioria dos eventos não resultou em consequências graves.

Fatores Contribuintes
Julgamento de Pilotagem aparece como o principal fator contribuinte identificado.
Aplicação de Comandos e Supervisão Gerencial também apresentam alta frequência.
Os resultados evidenciam a relevância dos fatores humanos e operacionais na prevenção de ocorrências.

Tipos de Ocorrência
Falha ou mau funcionamento de sistema/componente é o tipo de ocorrência mais frequente.
Colisão com aves e falha de motor em voo também se destacam entre os eventos registrados.

Evolução Temporal
Observou-se crescimento significativo no número de registros a partir de 2023.
O aumento foi impulsionado principalmente pelos incidentes registrados na base de dados.
A quantidade de acidentes manteve-se relativamente estável ao longo do período analisado.


🏗 Modelagem de Dados

O modelo foi estruturado utilizando relacionamentos do tipo 1:N, tendo a tabela Ocorrência como entidade central.

Modelo_dados.PNG
           
A modelagem permite realizar análises integradas sobre tipos de ocorrência, fatores contribuintes e características gerais dos eventos registrados.

📂 Estrutura do Repositório
analise-ocorrencias-aeronauticas

dataset/            Base de dados utilizada na análise

dashboard/          Arquivo Power BI (.pbix)

imagens/            Capturas dos dashboards

README.md           Documentação do projeto


👩‍💻 Autora
Barbara Alves
Estudante de Análise e Desenvolvimento de Sistemas
