---
layout: post
title: "Competição e Colaboração no Ensino de Teoria de Jogos"
date: 2011-02-08 13:55:13
categories: computação educação
---

Em cursos de Inteligência Artificial os assuntos [Busca Competitiva e Teoria de Jogos]({{ site.url }}/materiais/docs/ia/buscaCompetitiva.pdf) são ministrados para que os alunos saibam as bases para o desenvolvimento de agentes capazes de atuar em um ambiente competitivo composto por outros agentes (naturais ou artificiais). Neste contexto. é muito comum propor exercícios que envolvam a implementação de um agente para algum tipo de competição, por exemplo: implementar um jogador de damas ou um jogador de jogo da velha.

Em agosto de 2007, influenciado pelo [@mgalves](http://twitter.com/mgalves), decidi propor aos alunos do 6o semestre do curso de Ciência da Computação do Centro Universitário SENAC (São Paulo - SP) a implementação de jogadores para o jogo [Liga Quatro](http://en.wikipedia.org/wiki/Connect_Four). Um ambiente de competição de dois jogadores sem varável aleatória, ou seja, ideal para a implementação de algoritmos relacionados com o tema "busca competitiva". 

Desenvolvi um gerenciador para o jogo, criei o enunciado, as regras da competição e disponibilizei tudo em um [SVN](http://pt.wikipedia.org/wiki/Subversion) ([http://www.assembla.com/wiki/show/fourInRow](http://www.assembla.com/wiki/show/fourInRow)). O resultado foi bem legal. Os alunos entregaram diversas implementações, algumas baseadas no algoritmo [MinMax](http://pt.wikipedia.org/wiki/Minimax), outras baseadas em um [banco de regras](http://pt.wikipedia.org/wiki/Sistema_especialista).

O resultado da competição foi tão bom que eu resolvi dar continuidade no próximo semestre. No entanto, ao invés de liberar apenas o código fonte do gerenciador no 2o semestre de 2008, também liberei o código fonte de todos que participaram da primeira versão da competição. Assim, as equipes do 2o semestre de 2008 poderiam aprender com as soluções desenvolvidas pelas equipes do 2o semestre de 2007 e também competir contra as melhores equipes.

Além dos anos 2007 e 2008, esta competição também foi executada nos anos de 2009 e 2010. Durante estes anos sempre houve algum tipo de aperfeiçoamento nas implementações: o uso de poda alpha-beta no algoritmo MinMax, a implementação de uma função de utilidade mais adequada ou o uso de uma base de conhecimento mais eficiente.

No 2o semestre de 2010 resolvi parar com a competição, pois ninguém mais conseguia ganhar de um jogador que fez uso do algoritmo MinMax com uma base de conhecimento - talvez este seja o melhor critério de parada para este tipo de atividade. Em suma, esta atividade valeu a pena porque permitiu aos alunos desenvolverem uma solução com uma complexidade razoável, utilizarem o código de outras pessoas para aprimorar as próprias soluções, além de exercitar o uso de um sistema de controle de versão.

Infelizmente, as implementações dos jogadores desenvolvidos em 2010 não estão no link apontado acima. Para ter acesso a todos os jogadores é necessário baixar o tar.gz localizado [aqui]({{ site.url }}/materiais/LinhaQuatro.tar.gz). Tentei organizar os resultados e fazer o commit no SVN, mas ainda não tive tempo.
