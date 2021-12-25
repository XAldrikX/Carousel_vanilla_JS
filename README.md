# Carousel_vanilla_JS

Utilizei uma variável que conta quantos elementos eu tenho no array que "document.getElementsByClassName" me devolve, e uma variável counter para poder observar em qual “slide” estamos no momento, assim pude criar duas funções para os botoes "next" e "previous" mudarem os slides, também tive que criar uma função chamada "hideAllSlides" que define todos os slides com uma classe inicial chamada "carousel-item-hidden", isso faz com que o estado inicial dos slides seja "Display: none;", o primeiro slide sempre começa com a classe "carousel-item-visible" onde o Display esta definido como "block", essa mudança de classes pode ser feita utilizando o método "classList" que permite utilizarmos .add() ou .remove() para adicionar ou remover classes de um elemento HTML. 
Também utilizei keyframes para obter uma transição mais suave entre os slides.

link do deployment --> https://xaldrikx.github.io/Carousel_vanilla_JS/
