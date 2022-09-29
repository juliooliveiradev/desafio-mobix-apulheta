# desafio-mobix-apulheta
Ola Tudo Bem.
Aqui se encontra o repositorio do desenvolvimento do desenho de uma apulheta em Javascript.
É um programa simples mas com muita eficiencia e eficacia.
Vou contar como foi minha experiencia no desafio.
Trabalhar com matriz e algo que exige bastante empenho por conta da complexidade de seu preenchimento.
Ja desenvolvi muitos desafios com matriz na Linguagem C mas nao fiz ainda programas com matriz em JavaScript, por isso eu primeiro desenvolvi o programa em C e depois transpus para JavaScript.
Primeiro desenvolvi o desenho da ampulheta sem o preenchimento.Preencher as extremidades foi acessivel pois deu para analisar como que ele foi feito e reproduzir no codigo alem do preenchimento da esquerda para direta deu para analisar pois e o principio de uma matriz identidade que ja fiz um preenchimento na liguagem C. O que tive pucas dificuldades para descobri foi o preenchimento da lateralda direta para esquerda mas quando descobrir que de uma linha para outra, a posicao da linha crescia e a posicao da coluna decrescia e consegui reproduzir no codigo.
Ja no preencimento da parte de cima e de baixo, tive difulcades para descobrir mas percebi que da parte de cima, o prechimento em cada linha comeca quanho o numero do vetor da coluna fica maior ou igual que o da linha mas depois da metade das colunas vi que isso nao era suficiente. Entao Descobri que alem desta condição, o vetor da linha fica menor que a diferença entre a quantidade de elemntos  e o numero do vetor da coluna. entao consegui reproduzir. Na parte de baixo percebi que quando passa da metade da linha, percebi que so poderia preencher se o numero do vetor da linha for maior ou igual a da coluna e tambem percebi que so preencheria se tambem o numero do vetor da coluna  for menor que a diferença entre o numero do vetor da linha , a quantidade de elementos e dois pois  como o numero da coluna do segundo quadrante diminuia ao passar das linhas, no quarto quadrante eles cresciam entre descobti este calculo atraves desta analise.
Gosto muito de ser desafiado, gostei bastante deste desafio, muito bom analisar bem como ele e desenvolvido e quebra a cabeca de como explicar para a maquina como se deve preencher. Espero que se agradem com o programa pois este me agradou bastante.
Atenciosamente
Julio
