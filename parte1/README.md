                                            HTML
As tags em HTML podem ser escritas em maisculas ou minusculas. Porém, por padrão, a tag DOPTYPE é toda maiuscula.

• h : é uma tag de título Existem 6 níveis de tag h

• p : tag de parágrafo de texto • strong : Tag em negrito

• em : Tag em itálico

• !DOPTYPE html : Informa ao navegador a versão do html que estamos utilizando. Ela é uma tag que não precisa ser "fechada" porque é uma tag de informação e não de conteúdo.

• html : O HTML tem uma tag estrutural, que é a própria tag HTML. Ela é uma tag de conteúdo que serve para marcarmos dentro da página, tudo o que é HTML que vai ser renderizado no navegador. • Dentro da Tag html costumamos informar qual é linguagem da página (lang-"pt-br")

• meta : Tag de informação. Dentro dela, diferente do h1, que é uma tag de conteúdo, colocamos uma propriedade dentro dela. A propriedade 'charset = "UTF-8"'. É preciso apontar para o navegador que estamos usando um dicionário que tenha acentos e cedilha, sinais gráficos comuns na língua portuguesa.

• title : título da página

• O html pode ser dividido em duas partes: o head e o body. • Na estrutura correta do HTML, inserimos as informações que queremos passar para o navegador no head e as tags de conteúdo no body.

                                           CSS
• Existem três formas de configurarmos o CSS. A chamada CSS inline, na linha onde temos nossa tag, adicionamos a propriedade do CSS. A segunda é incluindo a estilização em cada tag na propriedade style, no mesmo arquivo html. A terceira forma é através de um arquivo externo.

• style : Estilo do nosso elemento. Dentro do style e entre aspas vou inserir o que quero alterar. O tamanho da fonte padrão no navegador é medido em pixels. Ocasionalmente o navegador adiciona o tamanho da fonte inicial como 16. • style ="font-size:20px" : aumentando a fonte

• text align : Para alinhar os parágrafos no centro.

• p style ="font-size:20px;text-align:center" : uso de ; para separar duas informações

• No CSS o : serve para atribuir um valor a uma propriedade. É a forma correta de separar o valor da propriedade.

• style : Temos a opção de dentro do head, adicionarmos a tag style. Ela é uma tag que abre e fecha. Dentro da tag, podemos colocar marcações de CSS referentes aos elementos que temos no nosso HTML. Usamos p{} para que todas as Tags p recebam a propriedade que eu quero do CSS. Depois que foi criado o arquivo style.css , mudamos a parte do p{} para o style.css

• Link do CSS no head: Para utilizar a estilização do arquivo style.css no index.html, precisamos incluir no head link rel="stylesheet" href="style.css". Link é a ligação entre um arquivo e outro. Vamos dizer o relacionamento desse link com a propriedade rel e o valor stylesheet, ou seja, folha de estilo, e vamos dizer onde o arquivo está, href, que é o endereço de referência.

• Só com um arquivo externo, e fazendo referência a esse arquivo, podemos usar o mesmo CSS em páginas diferentes.