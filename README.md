# prof-lucas-tcc
Repositório com instruções para os orientandos de estágio, tcc e ic do Professor Lucas Dias Hiera Sampaio - Créditos do Modelo: Prof. Diogo Cezar.

# Quer ser meu orientando?

Então começe lendo isso aqui ;)

Neste repositório irei organizar uma série de instruções para os alunos que eu oriento e os possíveis futuros orientandos.

A primeira coisa é: __prepare-se para fazer as coisas bem feitas__.

# Áreas de Interesse

As duas frentes de pesquisa que trabalho atualmente estão contidas nas grandes áreas de __telecomunicações__ e __segurança da informação__

Dentro da área de __telecomunicações__ é possível abordar os seguintes temas/problemas:

+ Sensoriamento Espectral;
+ Redes de Rádio Cognitivo;
+ Rádio Definido por Software;
+ Access Point Deployment;
+ Alocação de Recursos;
	+ Potência;
	+ Espectro;
	+ Modulção;
	+ Codificação;
	+ Sequências Piloto;
	+ Sequências de Espalhamento;
	+ Tempo;
	+ Contínuo/Discreto;
+ Sistemas de Comunicação Massive MIMO;
+ Sistemas de Comunicação OFDM;

Por sua vez, na área de __segurança da informação__ é possível abordar os seguintes temas/problemas:

+ Sistemas de Detecção de Intrusão:
  + Análise Histórica
  + Análise Preditiva
+ Aplicação da Tecnologia Blockchain
+ Criptomoedas
+ Smart Contracts

# Como se candidatar?

Basta enviar um email com a ideia do seu projeto para __ldsampaio@utfpr.edu.br__

E marcar uma reunião em um dos meus horários disponíveis.

É importante salientar que neste momento possuo __9 alunos__ sob minha orientação e que será necessário analisar a viabilidade da orientação de seu projeto.

Dessa forma, para 2018-2 teremos as seguintes vagas disponíveis:

+ 3 vagas para __TCC 1__
+ 2 vagas para IC na área de __telecomunicações__
+ 2 vagas para IC na área de __segurança da informação__

__Logo, para que seja possível uma avaliação inicial eu gostaria que o candidato escrevesse resumidamente alguns parágrafos explicando a idéia inicial do seu trabalho, como se fosse um capítulo de introdução de sua monografia. Este material é essencial para a confirmação de sua vaga__

Se você não conhece as áreas e deseja saber mais a respeito, __marque um horário__ para conversarmos.

__Keep in touch.__

# Ferramentas

Vou listar a seguir algumas ferramentas que podem ser fundamentais para o bom andamento do seu trabalho e para a solução dos problemas que você escolher tratar.

+ Ferramentas Gerais
  + LateX (obrigatório)
  + ShareLatex/Overleaf (versão gratuita - obrigatória)
  + Inglês
  + Mendeley
  + SciHub
+ Ferramentas Específicas
  + Script M
  + Python
  + Heurísticas
  + Aprendizado de Máquina
    + Redes Neurais
    + TensorFlow
    + Support Vector Machine
  + Ferramentas de Otimização Linear e Não-Linear
  + Ferramentas de Otimização Convexa e Não-Convexa

# Organização

Vou colocar aqui algumas instruções essenciais para todos os meus orientandos.

É importante que essas sugestões sejam seguidas para uma boa organização do projeto como um todo.

Você precisará conhecer as seguintes tecnologias:

1. [Markdown](#markdown)
2. [LaTeX](#latex)
3. [Git e GitHub](#git-e-github)
4. [Mendeley](#mendeley)
5. [Organização do seu Repositório](#preparacao-do-ambinete)
6. [Aprenda Inglês](#aprenda-ingles)
7. [Normas TCC](#normas-tcc)
8. [Dicas TCC](#dicas-tcc)
9. [Modelo Word](#modelo-word)

# Markdown

Markdown é uma linguagem de marcação, simples e eficiente.

Ela será a base para nós trabalharmos com todos os documentos auxiliares. Estes documentos serão, essencialmente, arquivos no formato .MD que possuirão um conteúdo formatável.

## Por que?

Bom é bem simples, é uma forma fácil de versionar, e acompanhar a evolução das pesquisas que serão realizadas para embasar o seu trabalho.

Se você não conhece ou tem dificuldades com essa tecnologia, recomendo estudar através dos seguintes links:

* https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
* https://www.markdowntutorial.com/
* https://guides.github.com/features/mastering-markdown/
* https://blog.da2k.com.br/2015/02/08/aprenda-markdown/
* https://cezarcruz.com.br/como-escrever-textos-usando-markdown/


# LaTex

LaTeX vai ser muito útil para a escrita da sua monografia.

Eu recomendo fortemente que você invista um tempo e aprenda a utilizá-lo, desta forma, você não precisará se preocupar com regras de formatação de texto, e focar somente no conteúdo.

## Modelo LaTeX UTFPR

O modelo para elaboração de trabalhos acadêmicos está disponível aqui:

* https://github.com/utfpr-cp/utfpr-modelo-latex

Este é o modelo oficial e provavelmente o mais atualizado (pelo menos deveria ser!)

Se quiser aprender um pouco mais sobre LaTeX:

* http://each.uspnet.usp.br/sarajane/wp-content/uploads/2016/10/manual-latex-1.pdf
* http://www.mat.ufmg.br/~regi/topicos/intlat.pdf
* http://www.ime.unicamp.br/~encpos/VIII_EnCPos/Apostila_Latex.pdf

# Git e GitHub

Bom, você vai precisar versionar tudo o que fizer!

Não somente os seus códigos referentes ao seu trabalho final, mas também a sua pesquisa!

Isso mesmo, nós vamos trabalhar com uma organização feita dentro do GitHub.

Por isso, se Git e GitHub ainda são problemas... Então você pode consultar o material disponivel na pasta ~~materiais/git-github-utfware.pdf~~ e ~~materiais/git-github-apostila.pdf~~

# Organização do Seu Repositório

Bom, depois de criar uma conta no GitHub, peço que criem os seguintes repositórios:

+ __tcc-docs__ : Um repositório para organizarmos nossos documentos, anotações, pesquisas, dicas, resumos e etc. Podem organizar esse repositório em pastas. No README.MD principal, coloquem um índice para cada item e tentem seguir a seguinte estrutura de pastas:

    + __reuniões__ : Um log do que ficou combinado em cada uma das reuniões;

    + __cronograma__ : O seu arquivo PDF com cronograma atualizado.

    	O modelo para cronograma pode ser acessado aqui: https://docs.google.com/spreadsheets/d/1q67WijB6hsEm4XaBts3Mv_uK9AMseGHfommtM1MHw68/edit?usp=sharing

		Neste cronograma, organize:

        + atividades;
        + entregas;
        + reuniões;
        + apresentação final;

    + __pesquisas__ : Uma pasta com subpastas, uma para cada assunto/pesquisa realizada. (podem conter textos, pdfs ou apenas links para os pdfs de artigos)

    + __resumos__ : Uma cópia da pasta pesquisas, mas ao invés dos links ou pdfs, vamos criar os nossos resumos das pesquisas;

    + __apresentação__ : Uma pasta para armazenar a apresentação para banca em pdf;

    + __mono__ : Um repositório com a sua monografia em LaTeX;

    + __outros__ -> Uma pasta para deixar dicas, anotações e outros assuntos que podem ser pertinentes para pesquisas;

__tcc-samples__ : Um repositório para os estudos (códigos mesmo) vocês podem organizar da forma como desejarem, só não se esqueçam de escrever no README.MD o que cada código realiza de fato;

__tcc-code__ : Um repositório com a implementação de fato do seu trabalho;

# Mendeley

O Mendeley é uma ferramenta gratuita que te auxilia na criação, manutenção e utilização de uma base de dados como referências do teu trabalho. Basicamente, ele automatiza o processo de geração das informações de cada referência bibliográfica e, de quebra, te permite armazenar um PDF associado àquela referência.

Adicionalmente, a plataforma permite que você instale extensões no seu navegador para coletar automaticamente dados sobre PDFs que você venha a abrir no mesmo e incluí-lo em seu banco de referências. Por fim, o Mendeley permite que você compartilhe referências entre usuários da plataforma.

Tenha em mente que você lerá __muita informação__ para construir seu trabalho e, portanto, qualquer ajuda no gerenciamento desta base é sempre bem vinda.

# Aprenda Inglês

Em um cenário onde cada vez mais a linguagem universal da tecnologia é o inglês, se você ainda não tem conhecimento técnico de inglês, de forma fundamental a leitura, corra atrás do seu prejuízo. A quantidade de cursos, informações, vídeos, dicas e shortcuts hoje, com a internet, tende ao infinito.

Adianto que, no caso de __IC__ inglês é ferramenta obrigatória visto que toda escrita de artigos dar-se-á em inglês. Já para o __TCC__ a lingua inglesa é uma possibilidade e será considerada como fator determinante na eventual necessidade de existir mais candidatos que vagas.

Dos artigos das áreas de interesse, 99% estão em inglês.

__Get used to it__

# Normas TCC

Bom, para não dar uma de desavisado é importante estar por dentro das normas para elaboração do seu TCC.

O link com vários materiais referentes a isso, pode ser obtido aqui:

* https://github.com/utfpr-cp/utfpr-tcc-normas

# Dicas TCC

Algumas dicas são sempre bem-vindas certo?

Então dê uma olhada neste reposirótio:

* https://github.com/utfpr-cp/utfpr-tcc-dicas

# Modelo Word

It's a Trap! Não trabalharei com documentos em Word.

# Considerações Finais

Qualquer dúvida, basta enviar um e-mail para ldsampaio@utfpr.edu.br

Até++;
