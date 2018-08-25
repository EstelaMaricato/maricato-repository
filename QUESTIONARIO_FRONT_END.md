# maricato-repository

1) Se você tivesse 5 diferentes arquivos de folhas de estilo, qual seria a melhor forma de integrá-los no site? 
  A melhor forma é utilizando o "IMPORT". 
  <estilo tipo="text/css"> <!-- @import url("source/page.css"); --> </style>.  

2) Fale 3 formas de diminuir o page load (tempo de carregamento real e percebido).
  Packer, Minify e o JSMin.

3)Quais ferramentas você usa para testar a performance do seu código?
  Apache JMeter
  
4) Considere o HTML5 como uma plataforma web aberta. Quais são os blocos de construção de HTML5?
  div, h1 até h6, p, blockquote, ul, ol e form.

5) Você pode explicar a diferença entre GET e POST?
  - A grande diferença entre os métodos GET e POST provavelmente é a visibilidade. Uma requisição GET é enviada como string anexada a 
  URL,enquanto que a requisição POST é encapsulada junto ao corpo da requisição HTTP e não pode ser vista.
  - Com o uso do GET a string não pode conter mais que 255 caracteres(embora exista diferenças entre navegadores, mas em geral o limite
  é 255). Já na requisição POST não há limitações de comprimento da mensagem, já que a mesma é enviada no corpo da requisição HTTP.
  - Já que GET é enviado via URL, então nós sabemos que ela só transporta textos. A requisição POST não tem restrições, pode 
  transportar tanto texto, como dados binários.
  - A requisição GET pode ser armazenada em cache, ou em um sistema de bookmark(favoritos). A mesma coisa não é possível para 
  requisições 
  POST.
  - GET é o método HTML padrão. Para submeter um formulário HTML usando POST é preciso especificar no atributo “method” o valor “POST”.

6) Liste quantas propriedades display você puder lembrar.
  block, inline, none, inline-block, list-item, run-in e table.

7) Qual a diferença entre inline e inline-block?
  A diferença é que inline não pode ser definido height e width para eles, ao contrário do inline-block que os elementos aceitam que 
  seja definido os respectivos atributos css.
  
8) Qual a diferença entre elementos posicionados de forma relativa, fixa, absoluta e estática?
  A diferença é que quando posicionamos um elemento relativamente ele é posicionado de acordo com sua própria posição. Já quando um 
  elemento é definido como posicionamento fixo, sua posição é computada com relação à parte visível do User Agent (em geral, o browser) 
  em que a página está sendo exibida. Já quando um elemento é posicionado absolutamente, sua posição é computada de acordo com a posição 
  do elemento “posicionado” mais próximo, que o contém. E um elemento posicionado estaticamente segue o fluxo normal dos elementos da 
  página, ou seja, se posiciona abaixo do elemento imediatamente anterior e acima do imediatamente posterior, quando nenhum destes está 
  posicionado de outra forma que não a estática.

9) Qual a diferença entre .call e .apply?
  A diferença está nos parâmetros, Apply invoca uma função com o this (contexto) e um array com os parâmetros da função, já o Call 
  utiliza como primeiro parâmetro o this (contexto) e os próximos são os parâmetros da função.
  
10) Qual a diferença entre == e ===?
  A diferença é que se utilizarmos == haverá uma coerção do valor para que ambos os lados da expressão tenham o mesmo tipo e se 
  usarmos === não haverá coerção.
