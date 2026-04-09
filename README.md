
<div align="center">
  

# Distribuições de Probabilidade  
### Aplicações em Materiais Cimentícios Reforçados com Fibras 

<img src="https://chatgpt.com/s/m_69d7ae26b58081918f26537ba65797fc" width="500"/>

  
<br>


**Disciplina:** Estatística e Planejamento de Experimentos  
**Curso:** Doutorado em Engenharia Civil  

<br>

**Discente:** Bruna Taiana Almeida Brito  
**Área:** Construção Civil e Materiais

<br>

Universidade Federal da Bahia (UFBA)
2026  

</div>

<div align="justify">
  Este repositório foi desenvolvido no contexto da disciplina de Estatística e Planejamento de Experimentos, com foco na aplicação das distribuições de probabilidade à Engenharia de Materiais.  O material apresenta conceitos fundamentais das distribuições Binomial, Normal e de Poisson, integrando teoria estatística com aplicações práticas. 
</div>

# 1. Introdução
<div align="justify">
  A análise de fenômenos na engenharia civil, especialmente na área de materiais, está intrinsecamente associada à variabilidade dos resultados experimentais. Propriedades como resistência mecânica, módulo de elasticidade, fissuração e durabilidade não são determinísticas, apresentando dispersões decorrentes de fatores como heterogeneidade dos materiais, variabilidade no processo de produção e incertezas inerentes aos ensaios experimentais.
  
  Nesse contexto, a teoria das probabilidades e a estatística desempenham papel fundamental na modelagem e interpretação desses fenômenos, permitindo descrever o comportamento de variáveis aleatórias por meio de distribuições de probabilidade. Uma distribuição de probabilidade pode ser entendida como uma função que associa a cada valor possível de uma variável aleatória a sua respectiva probabilidade de ocorrência, representando, portanto, o comportamento estatístico de um fenômeno (MONTGOMERY; RUNGER, 2014).
  
  De acordo com o material apresentado em aula, a distribuição de probabilidade expressa o comportamento de uma variável aleatória vinculada às probabilidades de ocorrência de seus possíveis resultados . Essa abordagem é essencial para compreender experimentos simples, como lançamentos de moedas, até aplicações mais complexas, como a análise de desempenho de materiais cimentícios.
  
  Na engenharia de materiais, particularmente em compósitos cimentícios reforçados com fibras, a utilização de distribuições de probabilidade permite avaliar a variabilidade experimental e a confiabilidade dos resultados. Por exemplo, a resistência à flexão de elementos cimentícios pode ser modelada por distribuições contínuas, como a distribuição normal, enquanto a ocorrência de fissuras ou falhas pode ser analisada por distribuições discretas, como a binomial ou de Poisson.
  
  A adoção de modelos probabilísticos é, portanto, indispensável para o planejamento de experimentos e para a interpretação adequada dos resultados, permitindo não apenas a determinação de valores médios, mas também a quantificação da dispersão e da incerteza associada às propriedades analisadas. Segundo Devore (2016), a utilização de métodos probabilísticos possibilita uma compreensão mais realista dos fenômenos de engenharia, uma vez que incorpora a variabilidade natural dos processos.
  
  Além disso, a aplicação de ferramentas computacionais, como linguagens de programação e ambientes interativos (por exemplo, Python em notebooks), tem ampliado a capacidade de análise e visualização de dados, permitindo a implementação prática de modelos probabilísticos e facilitando a interpretação dos resultados experimentais.
  
  Dessa forma, este trabalho tem como objetivo apresentar e discutir as principais distribuições de probabilidade — Binomial, Normal e de Poisson — com ênfase em suas aplicações na engenharia civil, especialmente no estudo de materiais cimentícios reforçados com fibras, integrando conceitos teóricos, exemplos aplicados e implementações computacionais.
</div>
  
# 2. Conceitos Fundamentais
## 2.1 Variável Aleatória

Uma variável aleatória é uma função que associa a cada resultado de um experimento aleatório um valor numérico. Essas variáveis podem ser classificadas em dois tipos principais: discretas e contínuas (DEVORE, 2016).

As variáveis aleatórias discretas assumem valores finitos ou enumeráveis, sendo comuns em experimentos que envolvem contagem, como o número de falhas em um conjunto de corpos de prova. Já as variáveis contínuas podem assumir qualquer valor em um intervalo, sendo típicas em medições físicas, como resistência, deformação e deslocamento.

No contexto da engenharia de materiais, a resistência à compressão ou à flexão de um compósito cimentício é um exemplo clássico de variável contínua, enquanto o número de fissuras em um elemento estrutural pode ser tratado como uma variável discreta.

2.2 Distribuição de Probabilidade

A distribuição de probabilidade descreve como os valores de uma variável aleatória estão distribuídos, associando probabilidades a cada possível resultado. No caso de variáveis discretas, essa distribuição é definida por uma função de probabilidade; para variáveis contínuas, é descrita por uma função densidade de probabilidade (MONTGOMERY; RUNGER, 2014).

As distribuições de probabilidade permitem não apenas descrever o comportamento dos dados, mas também realizar inferências e previsões, sendo fundamentais no planejamento e análise de experimentos.

2.3 Importância na Engenharia Civil

Na engenharia civil, a variabilidade dos materiais e dos processos construtivos torna indispensável o uso de modelos probabilísticos. A análise estatística permite:

quantificar a dispersão dos resultados experimentais;
avaliar a confiabilidade de materiais e estruturas;
comparar diferentes composições ou processos;
apoiar a tomada de decisão em projetos e controle tecnológico.

Em materiais cimentícios reforçados com fibras, por exemplo, a variabilidade na distribuição das fibras, na aderência fibra-matriz e nas condições de moldagem influencia diretamente o comportamento mecânico, sendo essencial a utilização de distribuições de probabilidade para uma análise adequada desses sistemas.
