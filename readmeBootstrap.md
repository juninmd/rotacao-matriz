# Rotação de matriz com Javascript

## Cabeçalho
```html
// Aqui definimos o cabeçalho do nosso html
// A tag <head> é a mesma coisa que div, porém é o certo ao usar a semântica.
<head>
    // Aqui é o padrão de codificação, usamos sempre esse.
    // Para renderizar ascentos.
    <meta charset="UTF8">

    // Aqui é como vai aparecer na aba do navegador
    <title>Rotação de Matriz</title>
</head>
```
 
 ## Body
 ```html
 // Aqui é a semântica que define que é o corpo do nosso site
 <body>
     // <h1> é uma tag usada para títulos
     // existe <h2> <h3> ... quanto maior número, menor a fonte, indicam sub-título.
    <h1>Rotação de Matriz</h1>
    
    // <label> é o componente para escrever um texto na tela. O for é só pra indicar de qual input, se existir.
    <label for="txtNumero">Por favor, informe a quantidade.</label>
    // <input> como o nome sugere será algum valor que o usuário vai informar para o site.
    // placeholder é uma mensagem padrão que fica no fundo transparente.
    // id é o nome que definimos pra indentificar ele (apelido)
    // type é o tipo, ele poderia ser text, date..
    // como é um number, definimos um valor mínimo e máximo.
    <input placeholder="Entre 2 e 27" id="txtNumero" type="number" min="2" max="26" />
    // <br> significa break, quebra de linha
    <br>
    // <button> gera um botão na tela
    // onclick chama uma função javascript
    // assim eu passo de parametro 1 
    <button onclick="rotate('1')" type="button">Normal</button>
    <button onclick="rotate('2')" type="button">Esquerda</button>
    <button onclick="rotate('3')" type="button">Direita</button>
</body>
```