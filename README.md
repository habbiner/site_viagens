# Site de viagens
Site desenvolvido como prova do primeiro semestre da faculdade de Desenvolvimento de Software Multiplataforma na Fatec Dr. Thomaz Novelino, objetivo era desenvolver um site utilizando apenas HTML e CSS.

# Link para o site hospedado
<a href="https://habbiner-travel-world.netlify.app/">LINK PARA O SITE</a>

# Tags utilizadas no HTML

- HEAD
  - LINK -> Conexão com CSS e para adicionar o logo da empresa na barra de janelas do Google;
  - TITLE -> Serve para definir no nome do site na barra de janelas;
- BODY
  - DIV -> Divisória entre as seções existentes no site;
  - INPUT -> O input da linha 14 do index.html é um input tipo texto para fazer pesquisa dentro do proprio site;
  - BUTTON -> A tag button serve para criar botões dentro da pagina;
  - A -> Tag a serve para criar links, no caso desta pagina na linha 16 à 20 possibilita a navegação entre as outras paginas;
  - H1, H2 e H3 -> São titulos de três tamanhos diferentes;
  - P -> Paragrafos de que fora usados dentro do site;
  - I -> Adiciona  icones da biblioteca do site fontawesome que pode ser acessado pelo link https://fontawesome.com/search;
  - IMG -> Foi usada para adicionar imagens dentro do site;
  - FOOTER -> Tag especifica para o rodapé do site;
  - SPAM -> Tag usada em conjunto com o A para criar a barra de navegação. Escolhi essas duas tags pelo fato de ambas serem componentes de linha;
  
  # Tags utilizadas no CSS

- MARGIN -> Movimenta o compontente usando a margem da tela como referência;
- PADDING -> Movimenta a posição do componente baseado no espaço interno do item;
- FONT-FAMILY -> Define qual fonte será exibina no corpo do site;
- BACKGROUND-COLOR -> Define a cor de fundo dos componentes;
- BACKGROUND-IMAGE -> Define define uma imagem como fundo da pagina ou componente;
- BACKGROUND-SIZE -> Movimenta o comportamento de tamanho e formato da imagem quando usada de fundo;
- FLEX-DIRECTION -> Define como item se alocaram dentro de um display-flex;
- DISPLAY -> Define como o elemento será tratado, se em linhas ou em bloco flexivel;
- COLOR -> Define a cor de componetes dentro do site;
- JUSTIFY-CONTENT -> Alinha o conteudo da esquerda para a direita;
- ALIGN-ITENS -> Alinha o conteudo de cima para baixo;
- TEXT-ALIGN -> Alinha o conteudo da div para o inicio, meio ou final;
- WIDTH -> Define largura da pagina ou componente;
- HEIGHT -> Define altura da pagina ou componente:
- MAX-WIDTH -> Define largura máxima da pagina ou componente;
- MAX-HEIGHT -> Define altura máxima da pagina ou componente:
- BORDER-RADIUS -> Define o quão arredondado será as bordas do item;
- BOX-SHADOW -> Adiciona efeito de sombra ao redor do componente;
- TRANSITION -> Altera o estado da componente por tempo determinado;
- CURSOR -> Modifica o cursor do mouse ao passar ele por cima do componente com essa configuração;
- FLOAT -> Define se o item ficara no seu local de origem, ou flutuando; 
- .MENU-BAR -> Configuração da barra de navegação, background-color define a cor azul que ela possui, color: white modifica as letras para a cor branca, justify-content: space-between; faz com que os itens alinhados tenham um espaço igual entre si e o width: 100% faz com que a barra ocupe 100% da largura da tela;
- A e A:HOVER, BUTTON:HOVER -> text-decoration faz com que o A fique sem o link azul e o sublinhado o color configurado no A da linha 20 do style.css faz com que as letras fique com a cor branca e o mouse modifique por conta do pointer. Ja na linha 26 ao usar o hover os links passaram a ter o meio branco e as letras vermelhas;
- .CONTAINER1 -> Esse container foi criado usando display: flex para fazer com que os itens de bloco fique em linha e o justify-content: space-between faz com que os itens deste container se distancie recebam um espaço ecatamente igual entre eles;
- .CARD1, CARD2, CARD3 -> As class do card possui a mesma configurações, o text-align: center centraliza todos componente de texto e imagem dentro do corpo do card, enquanto a tag width e height definem a largura e altura que os cards tem;
- .CORPO -> A tag corpo configura o "fundo" onde os card estão posicionados, o backgroung-image define qual imagem será adicionada ao fundo, o background-size: cover faz com que a imagem preencha todo o espaço em que ela se encontra. O display: flex; faz com que os itens de bloco se transformem em linha coloca o texto no centro, flex-direction: column; dispõe os arquivos em coluna e text-align: center; centraliza tudo dentro da div;
- .COLUNA -> Coloca os item em linha com o display: flex; e centraliza os cards com o justify-content: center; e align-items: center;
- .CARD -> border-radius arredonda as pontas do card e box-shodow cria uma pequena sombra ao redor dele. padding e magin ajusta o espaço entre os cards e o conteudo interno, width define o tamanho dele e o transition configura a animação de "destacar" e instrui que todos os elementos serão afetados pela transição com a duração de 0.3s e o ease-out define que a animação começa de forma rapida e diminui gradualmente;
- .CARD:HOVER -> hover aplica configura o que o componente fará ao passar o mouse por cima, nesse caso o card se move para cima por conta do translateY;
- .IMAGE -> Configura o tamanho maximo que a imagem poderá ter dentro do card, isso é especificado pelo max-width (largura maxima) e max-height (altura maxima) e que tudo deverá ficar flotando no centro;
- .PACOTES -> background-color faz com que o fundo fique com uma cor parecido com o creme, background-repeat: no-repeat;nao deixa a imagem se repetir para completar um lugar que ficaria em branco alinha com o comando object-fit: cover;
- .CARD_PACOTES -> Define tamanho e espaçamento do padding de 4px;
- FOOTER -> Tem uma largura de 100% para ocupar toda tela e com um height auto para acompanhar o conteudo sem que deforme algo. Displau: flex; align-items: center; e justify-content:space-around; faz com que os itens de bloco se alinhem e tenham espaços iguais entre eles;
  