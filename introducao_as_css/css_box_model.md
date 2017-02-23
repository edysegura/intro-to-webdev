## CSS Box Model {#css-box-model}

Entender o _CSS Box Model_ é fundamental para o trabalho de formatação do documento com as CSS. Todos os elementos do HTML se comportam como uma caixa. Existem dois tipos básicos de _containers_, que são os _inline_ e os de bloco.

Os elementos _inline_ são aqueles distribuídos na mesma linha. Eles ocupam somente o espaço necessário para que seu próprio conteúdo seja exibido, permitindo assim que outros elementos em linha possam ser renderizados logo na sequência, tais como as _tags_ `<img />` e `<br />`.

Os elementos de bloco são aqueles que ocupam toda a largura do documento, como as _tags_ `<p></p>` e `<h1></h1>`, distribuídas em linhas separadas.

![](/assets/css-box-model.png)

A primeiro momento não é perceptível, mas todos os elementos possuem, por padrão, margens e espaçamentos internos pré-definidos.

Figura 16 - Diagrama com a representação do CSS Box Model

As propriedades das CSS que compõem o _box model_ são: _width_, _height_, _padding_, _border_ e _margin_.

Segue um link para um estudo aprofundado sobre _CSS Box Model_:

[https://developer.mozilla.org/en-US/docs/Web/CSS/box\_model](https://developer.mozilla.org/en-US/docs/Web/CSS/box_model)

### CSS Reset {#css-reset}

Quando nenhum estilo é especificado para os elementos HTML o navegador utiliza uma série de estilos _built-in_. Não existe uma padronização para o valor inicial das propriedades CSS e cada navegador implementa essa funcionalidade à sua maneira.

Para evitar este tipo de inconsistência é recomendado uso de um CSS _Reset_, o qual é um arquivo CSS que contém especificações com o objetivo de alinhar os navegadores em um mesmo patamar de estilo, o que permite ter um resultado muito mais sólido entre os navegadores.

Figura 17 - Exemplo de CSS Reset

Uma alternativa ao uso desta técnica é o uso do normalize.css \([http://necolas.github.io/normalize.css/](http://necolas.github.io/normalize.css/)\) onde, ao invés de remover o estilo padrão dos navegadores, normaliza-os para que os elementos do HTML tenham uma consistência entre os diversos navegadores.

