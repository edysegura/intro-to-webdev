# Introdução a linguagem HTML {#introdu-o-a-linguagem-html}

HTML é uma linguagem para marcação de hipertexto e o seu objetivo é de estruturar e adicionar semântica[^1] para as informações que visualizamos através dos navegadores. Pode-se dizer que a HTML é a linguagem universal para a publicação de informações na Internet.

O HTML é composto por elementos que comumente são chamados de _tags_ ou marcações. Segue a sua estrutura básica:

```html
<tag attribute="value">content</tag>
```

Muitas _tags_ possuem conteúdo, desta forma o uso correto envolve uma _tag_ de abertura e uma _tag_ de fechamento com uma barra antes do seu nome.

Algumas _tags_ podem receber atributos, que são parâmetros que usam a sintaxe nome=valor. Os atributos serão apresentados em maiores detalhes durante a abordagem dos tópicos CSS e JavaScript.

O exemplo abaixo exibe uma _tag_ com o valor semântico para um título de nível 1 e outra _tag_ para informar que o conteúdo marcado é um parágrafo.

```html
<h1>Isso é um Título</h1>
<p>Isso é um parágrafo.</p>
```

Toda linguagem requer uma estrutura mínima para a sua utilização e para o HTML não é diferente. A seguir é apresentada a sua estrutura mínima.

```html
<!DOCTYPE html>
<html>
<head>
    <title>Your title here</title>
</head>
<body>

</body>
</html>
```

Um documento HTML válido precisa obrigatoriamente seguir a estrutura composta pelas tags `<html>`, `<head>`, `<body>` e a instrução `<!DOCTYPE>`, que define o tipo do documento e como ele será renderizado pelo navegador.

Dentro da _tag_ `<html>` é necessário declarar outras duas tags: `<head>` e `<body>`. Essas duas tags são "irmãs", pois estão no mesmo nível hierárquico em relação à sua _tag_ "pai", que é `<html>`.

O conteúdo que se deseja tornar visível para os usuários deve estar marcado entre as _tags_ &lt;body&gt;&lt;/body&gt;, localizadas nas linhas 6 e 8. Sempre que utilizar uma _tag_ HTML é preciso considerar o seu valor semântico, ou seja, deve-se pensar no significado da _tag_ antes da sua utilização.

Existem mais de 90 elementos HTML cada qual com um propósito específico: títulos, parágrafos, listas ordenadas e não ordenadas, listas de definição, imagens, tabelas, links e formulários. Uma referência completa das [_tags_ HTML](https://developer.mozilla.org/en/docs/Web/HTML/Element) encontra-se no site da [_Mozilla Developer Network_](https://developer.mozilla.org/en-US/). No próximo tópico serão apresentadas as principias _tags_ HTML.

[^1]: Semântica é a área da língua que estuda os significados das palavras

