---
layout: post
title: "Mudanças no currículo da CMU e novas disciplinas no MITOpenCourseWare: programação
  funcional, estrutura de dados e paralelismo"
date: 2011-03-01 16:19:25
categories: computação educação
---

Todos os anos a _Carnegie Mellon University_ (CMU) avalia seus cursos de computação e faz pequenos ajustes no currículo. No entanto, este ano parece que eles fizeram grandes mudanças, entre elas: introduzir técnicas e ferramentas de engenharia de software mais cedo e preparar os alunos para o desenvolvimento de softwares que não processam dados de forma sequencial [[1](http://www.cs.cmu.edu/~sisotani/CMU-ungrad-curriculum.pdf)].

O que me chamou mais atenção no relatório gerado foi o esquema ilustrado na figura 1 que apresenta a grade das disciplinas introdutórias.

![]({{ site.url }}/{{ site.baseurl }}/assets/cmu-300x212.png "Disciplinas básicas dos cursos de computação da CMU")

Principalmente a sequência de disciplinas: 15-122 _Imperative computation_, 15-150 _Functional computation_, 15-120 _Data structs & algoritms_ e 15-214 _Software system construction_.

O objetivo da disciplina 15-122 é apresentar o paradigma imperativo de programação (até ai, tudo normal). No entanto, em paralelo com esta disciplina é ministrada a disciplina 15-150, que tem como objetivo apresentar o paradigma funcional de programação, um paradigma que tem como característica principal a inexistência de estados. Geralmente, este tipo de conteúdo era ministrado como uma pequena parte de uma disciplina sobre paradigmas de programação. No entanto, parece que o tema obteve uma importância maior nos últimos anos.

**Será que esta importância dada ao paradigma funcional está relacionada com o desafio de manipulação de grandes massas de dados?** Acredito que sim! Principalmente, por que as disciplinas seguintes na grade da CMU, 15-120 _Data structs & algoritmos_ e 15-214 _Software system construction_, tem um enfoque no desenvolvimento de estrutura de dados otimizadas para ambientes sequenciais e paralelos, e no desenvolvimento de softwares para aplicações de larga escala, respectivamente.

Ao mesmo tempo que isto acontece na CMU, no MIT (outra instituição de ensino e pesquisa dos EUA) enfatiza a importância o ensino de estrutura de dados: "_Data structures play a central role in modern computer science. You interact with data structures much more often than with algorithms (think of Google, your mail server, and even your network routers)..._" [[2](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-851-advanced-data-structures-spring-2010/)], uma disciplina que durante muito tempo foi considerada apenas mais uma disciplina obrigatória na formação de um profissional em computação, mas sem muita "aplicação prática para a maioria dos profissionais". 
