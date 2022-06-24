---
layout: post
title: "Mudanças no Ranking de Institutos de Pesquisa para 2022"
subtitle: "Pouco mudou desde a última atualização do Ranking; entenda nossa metodologia e como o Ranking afeta nossa cobertura"
description: "Pouco mudou desde a última atualização do Ranking; entenda nossa metodologia e como o Ranking afeta nossa cobertura"
author: daniel
image: /assets/post_images/agregador.png
date: 2022-06-24
refid: rankingat
tags: eleicoes
seo:
  type: NewsArticle
---

A pouco menos de quatro meses das eleições de 2022, o _Pindograma_ atualiza o
seu ranking de institutos de pesquisa. Desde o seu
[lançamento](https://pindograma.com.br/2020/09/07/ranking.html) em setembro de
2020, ele continua sendo a única classificação do desempenho das empresas de
pesquisa brasileiras a partir de critérios objetivos.

Como escrevemos em 2020, "existem empresas de pesquisa que refletem
adequadamente as intenções de voto nos seus levantamentos; assim como existem
institutos que produzem resultados de baixa qualidade – seja de propósito, seja
por incompetência". O propósito do ranking do _Pindograma_ é ajudar nossos
leitores a fazerem essa distinção. Nesta época em que pesquisas eleitorais
estão sujeitas a dúvidas e questionamentos incessantes, acreditamos que uma
análise do desempenho passado dos institutos é mais importante do que nunca.

#### As mudanças

Desde a última atualização do ranking de institutos do _Pindograma_, **pouco
mudou**. Às pesquisas analisadas, adicionamos:

* 171 sondagens referentes ao segundo turno das eleições de 2020; e
* cerca de 20 sondagens referentes a pleitos anteriores, que haviam sido ignoradas por nossa equipe.

Em termos de **critérios do ranking**, também foram poucas as mudanças. Em primeiro
lugar, passamos a calcular o erro médio dos institutos a partir da _média das
diferenças absolutas entre os percentuais das pesquisas e os votos válidos na
eleição_, em vez do _desvio padrão das diferenças com sinal_ entre as duas
grandezas. Na primeira versão do Ranking, havíamos [optado pelo desvio
padrão](https://pindograma.com.br/2020/09/07/ranking.html), por medo que a
média subestimasse o erro das pesquisas. O que notamos, contudo, é que a
diferença entre os dois critérios é mínima, e a média tem a vantagem de ser
mais intuitiva para nossos leitores.

Em segundo lugar, diminuímos pela metade o peso que a inscrição nos Conselhos
Regionais de Estatística (CONREs) ou da Associação Brasileira de Empresas de
Pesquisa (ABEP) tem sobre a nota dos institutos. Antes, adicionávamos 30
pesquisas "neutras" ao histórico de cada instituto, cujo erro médio dependia do
instituto ser ou não membro de um CONRE ou da ABEP — isso porque o site
norte-americano
[FiveThirtyEight](https://fivethirtyeight.com/features/how-fivethirtyeight-calculates-pollster-ratings/),
no qual o _Pindograma_ inspirou a metodologia do Ranking, usava o mesmo número.
Agora, adicionamos apenas 15 pesquisas "neutras", uma vez que, na média, os
institutos brasileiros produzem muito menos pesquisas eleitorais que os
norte-americanos. Sentimos, portanto, que fazer parte de um CONRE ou da ABEP
estava exercendo um peso grande demais sobre a nossa classificação.

Nessa linha, o _Pindograma_ ressalta que a lista de membros do CONRE-1 — que
cobre institutos sediados em Goiás, Mato Grosso, Mato Grosso do Sul, Tocantins
e no Distrito Federal — está desatualizada. Diferentemente de todos os outros
CONREs, o CONRE-1 descumpre a Lei de Acesso à Informação e se recusa a publicar
a lista de empresas que pagam suas anuidades. O _Pindograma_ entrou com um
[processo](https://www.jusbrasil.com.br/processos/518525863/processo-n-1084088-3620214013400-do-trf01)
contra o Conselho para obter esta lista, mas até hoje, a causa não foi julgada.
Assim que essa informação ficar disponível, iremos publicar nova atualização do
Ranking.


#### Reflexões sobre a qualidade do ranking

Quando introduzimos o Ranking de Institutos em setembro de 2020, chegamos a uma
conclusão que nos trouxe certa consternação: o desempenho passado dos
institutos não parecia estar relacionado com o seu desempenho no futuro. À época, propusemos
três hipóteses que poderiam explicar esse fenômeno: "(1) o Ranking foi mal
feito; (2) a maioria dos institutos têm poucas pesquisas publicadas, e por
isso, a relação entre desempenho passado e desempenho futuro não aparece nos
dados; (3) a desempenho passado dos institutos de pesquisa no Brasil realmente
não é um indicador para o desempenho futuro".

Avaliando o desempenho do Ranking no pleito de 2020, é possível rever algumas
dessas hipóteses:

![](/assets/post_images/poll_rating.png)

Com base no gráfico, não nos parece que o ranking foi mal feito. Fica claro que
a nota dos institutos com base nos pleitos de 2012, 2014, 2016 e 2018 está
correlacionada com o desempenho dos institutos em 2020.

Dito isso, as outras duas hipóteses também parecem estar corretas em certa
medida. Por um lado, o maior número de pesquisas na nossa base de dados
aumentou o poder de predição do Ranking. Por outro lado, a correlação entre as
notas dos institutos em 2012-2018 e o desempenho em 2020 está longe de ser
perfeita.

O gráfico parece sugerir algumas conclusões. Em primeiro lugar, **entre os
institutos com histórico de acertos relativamente bom (notas A e B+), é difícil
prever qual deles vai ter o melhor desempenho nas próximas eleições**. Isso
confirma a postura editorial que o _Pindograma_ já vinha tomando com relação às
pesquisas eleitorais. Em nossas análises, [evitamos
privilegiar](https://pindograma.com.br/2021/05/14/datafolha.html) certos
institutos ou metodologias sobre outros — desde que tenham uma nota alta em
nosso Ranking. É uma postura que vai na direção oposta dos nossos colegas no
Estadão, por exemplo, que dão [peso maior às pesquisas
presenciais](https://www.estadao.com.br/politica/eleicoes/agregador-pesquisa-eleitoral-2022/?cargo=presidencial&modalidade=todas).

Já **da nota B para baixo, quanto pior a nota, pior parece ser o desempenho nas
próximas eleições**. Dar um peso menor para os institutos com esse desempenho
parece ser razoável, e é um passo que o _Pindograma_ deve tomar nas análises
que vamos publicar sobre as eleições de 2022.

Como de praxe, o código que usamos para gerar o Ranking está [completamente
aberto](https://github.com/pindograma/pesquisas/blob/master/6-CalculatePollsterRatings.Rmd),
assim como os dados que usamos para gerá-lo. Além disso, estamos sempre abertos
(e ansiosos) para discutir a avaliação de pesquisas eleitorais e para receber
contribuições de nossos leitores. Basta mandar um email para
[redacao@pindograma.com.br](mailto:redacao@pindograma.com.br). 

<hr style="width:100%;">

**Dados utilizados na matéria**: Banco de Dados de Pesquisas Eleitorais
(_Pindograma_, Poder360).
