---
layout: post
title: "Django + PostgreSQL + Redis + Knockout.js. Acerte!"
comments: false
categories: tech
---

A produção de aplicações pra web, especialmente *user-facing* é uma demanda constante. Seja uma *enterprise* seja uma startup. Você vai precisar de muitas delas. Mas qual *stack* usar?

Claro, existem alguns requisitos que restrigem as opções, mas muitas das restrições vem junto com a falta de conhecimento em alternativas pra lá de maduras no mercado e que poderiam beneficiar o negócio com **agilidade**, **simplicidade** e principalmente: **Seu projeto no ar em menos tempo!**

Após anos desenvolvendo aplicações, tenho recomendado um kit que deve cobrir grande parte das demandas de aplicações modernas. E aqui me refiro não só à UIX, mas principalmente como esse tipo de aplicação se encaixa em produção causando o mínimo de fricção.

Django
---

Este framework não é novo. Foi lançado em 2005, e daí já se vão mais de 10 anos de amadurecimento. Hoje é um framework deixa pra traz a maioria dos frameworks web usados na *enterprise*. Podemos elencar algumas das principais vantanges do [Django](https://www.djangoproject.com/).

Baixíssimo *Load Time* e *Auto Reload* sempre funcionando, permitem um desenvolvimento suave, sem stress. O *Template System* simplesmente funciona sem ser uma pedra no caminho. E o que dizer das ferramentas de testes já disponíveis no framework?

O Django conta com um ecosistema grande que permite fácil integração com outros elementos na sua solução como o a parte de matepamento objeto-relacional muito fácil, com migrações automáticas seguras compatíveis também com o PostgreSQL, nosso próximo ítem.

PostgreSQL
---

O [Postgres](http://www.postgresql.org/) é open source e performa muito bem. É interessante ver empresas como o [Heroku](htts://www.heroku.com) [oferecendo](https://www.heroku.com/postgres) o Postgres como produto diferenciado.

Existem features do postgres nem sempre utilizadas, mas que vem a calhar em algumas situações como o armazenamento Json e Full Text Search.

Combinado com o Django, é possível desenvolver com criação automática de modelos, esquemas, migrações de DDL e de dados. Mas existem situações onde o próximo banco cuida melhor. Vejamos.

Redis
---

É mais do que comum o uso de sessão, cache e fila em aplicações mesmo sendo pequenas. O [Redis](http://redis.io/) é um banco de dados não relacional que consegue se encaixar neste requisito sem dificuldade.

Mais uma vez a comunidade do Django provê bibliotecas que, em conjunto com sua estrutura plugável de cache e sessão, são facilmente integráveis com poucas linhas de configuração.

Knockout.js
---

Sendo aplicações de uma página só ou não, poucos frameworks javascript são tão enxutos e poderosos como o [Knockout.js](http://knockoutjs.com). O Knockout reduz a complexidade de páginas com DOM dependente em vários níves ou que tratam de objetos distintos mas relacionados.

Conclusão e **Atenção**
---

Esta combinação não é uma bala de prata. Mas confesso que muitas das situações em que passei, tudo seria resolvido com este "kit" com uma ou outra ferramenta a mais ou a menos.

No entanto, temos verificado pessoalmente o sucesso desta combinação aliada a algumas outras ferramentas DevOps. Aí chega-se a um nível de fricção inexistênte na sua TI.

Considere experimentar esta combinação, e se precisar de uma mão, conte conosco!

Forte abraço da sua equipe [Panda Team](http://www.pandateam.com.br)

*Post por Paulo Suzart (paulo.suzart@pandateam.com.br)* Co Founder.
