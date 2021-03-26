# Exercicio Aula 5

 Continuação 

Exercício - Listas

Dentro do seletor “#menu” altere a propriedade da lista para que ela não possua mais o estilo de lista, utilizando a propriedade:list-style-type: none;

Crie um novo estilo para os itens do menu, para que fiquem 

    inline:#menu li { display: inline}

No arquivo .css:

Insira a imagem fundoSite.jpg como fundo da tela para as páginas, para isto crie copie o código abaixo:

body{
    background:url('../imagens/fundoSite.jpg') no-repeat;}

Veja que o cabeçalho que está na cor preta, não é exibido corretamente, para isto altere a fonte das duas tagsde spanpara ficarem com a cor branca(utilizando herança)

    header {
        color:#FFFFFF; font-size: large;padding: 3px 0 0 50px;
        }

Exercício - Bordas

Crie os seletores para tratamento das imagens no arquivo css:

div.thumb{ border: 1px dashedblack; margin:10px;}

div.thumbspan{ display: block; text-align:center; }

div.thumbimg{ height:200px; }

No arquivo foto.html utilize este seletor de classe para as quatro primeiras fotos

Exercício - figure 

Até o momento,na página fotos.html, temos as 4 imagens utilizando o estilo de classe com o nome “thumb”.

Ajuste as imagens para que: 

– Fiquem dentro da tag HTML5 de figura; 

– O elemento span com a legenda da figura seja transformada em figcaption.

Ajuste os seletores utilizados para que as figuras continuem tendo o mesmo resultado visual até o momento

Exercício - Sombra 

Adicione um seletor para todas as tag img para que fiquem com uma sombra do lado esquerdo e acima da imagem:

Todas as imagens deverão ficar com uma sombra