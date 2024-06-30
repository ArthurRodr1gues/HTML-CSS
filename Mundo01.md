
# <center> Estrutura Básica de um HTML5 </center>

```HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>

```
+ O titulo da página é o que aparece na barra da guia.
+ No _VSCODE_ essa estrutura básica é criada através do atalho: `!`


# <center> Parágrafos </center>
+ Funções principais do parágrafo: legibilidade, semântica, formatação e estilo.
+ **Exemplo**: _Pode ser escrito qualquer coisa, </br>basta colocar no meio do par de tags &lt;p&gt; e &lt;/p&gt;_.

### O código do exemplo acima foi gerado por:
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <p>
        Pode ser escrito qualquer coisa, </br>basta colocar no meio do par de tags &lt;p&gt; e &lt;/p&gt;
    </p>


</body>
</html>
```
+ Perceba a quebra de linha `<br>` antes de _basta_.
+ Perceba que os parágrafos foram adicionados entre as tags `<body>` e que para exibir as tags foi preciso adicionar alguns símbolos.
+ `lt` significa <u>less than</u> e `gt` <u>greather than</u>.

# <center>Adicionando Imagens</center>
+ Para adicionar uma imagem, siga o modelo abaixo.

### Exemplo de HTML com Imagem e Link

```html
<!DOCTYPE html>
<html>
<head>
    <title>Exemplo de HTML</title>
</head>
<body>
    <!-- Imagem na mesma pasta -->
    <h1>Imagem na mesma pasta</h1>
    <img src="imagem.jpg" alt="Descrição da Imagem">

    <!-- Imagem em página diferente -->
    <h1>Imagem em página diferente</h1>
    <img src="imagens/imagem.jpg" alt="Descrição da Imagem">

    <!-- Link -->
    <h1>Link para outra página</h1>
    <a href="https://www.exemplo.com">Clique aqui para visitar o exemplo</a>
</body>
</html>

```

+ Criando a tag `<img>` no _VsCode_: Digite _img_ e selecione a sugestão. 
+ Para selecionar o arquivo: `ctrl + espaço`


# <center>Adicionando Favicons</center>

+ Adicione a seguinte linha ao head:
```html
<link rel="icon" href="favicon.ico" type="image/x-icon">
```
+ Geralmente usa-se o formato ícone.

#  <center>Hierarquia de Títulos</center>
+ Vai do `<h1>` ao `<h6>`.
+ Não considere aspectos estéticos, mas funcionais.
+ Pode-se gerar textos automáticos com o uso da palavra _lorem_ no _VsCode_.


# <center>Formatação de Textos</center>
+ `<strong>`: semanticamente informa que o texto tem alta importância e estéticamente aplica um <strong>negrito</strong>.
+ `<em>`: semanticamente informa que o texto tem ênfase e estéticamente aplica um <em>itálico</em>.
+ `<ins>`: semanticamente indica uma inserção de texto e estéticamente aplica um <ins>sublinhado</ins>.
+ `<sub>`: semanticamente marca texto como subscrito e estéticamente aplica um texto <sub>subscrito</sub>.
+ `<sup>`: semanticamente marca texto como sobrescrito e estéticamente aplica um texto <sup>sobrescrito</sup>.
+ `<code>`: semanticamente informa que o texto é código e estéticamente aplica uma formatação de <code>código</code>.
+ `<q>`: semanticamente indica uma citação curta e estéticamente aplica <q>aspas</q>.
+ `<abbr>`: semanticamente indica uma abreviação e estéticamente pode exibir uma dica com o significado completo quando o cursor passa sobre a abreviação, por exemplo, <abbr title="HyperText Markup Language">HTML</abbr>.
