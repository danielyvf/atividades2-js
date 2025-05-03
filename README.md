
# 🚀 Prática de JavaScript - Arrays e Strings

Exercícios simples para treinar manipulação de arrays e strings em JavaScript.

## 🥘 Comidas
```js
const comidas = ['Pizza', 'Frango', 'Carne', 'Macarrão'];
const primeiroValor = comidas.shift();     // Remove o primeiro
const ultimoValor = comidas.pop();         // Remove o último
comidas.push('Arroz');                     // Adiciona no fim
comidas.unshift('Peixe', 'Batata');        // Adiciona no início
```

## 👨‍🎓 Estudantes
```js
const estudantes = ['Marcio', 'Brenda', 'Joana', 'Kleber', 'Julia'];
estudantes.sort();                         // Ordem alfabética
estudantes.reverse();                      // Inverter ordem
estudantes.includes('Joana');              // true
estudantes.includes('Juliana');            // false
```

## 🧱 HTML para Lista
```js
let html = `<section><div>Sobre</div><div>Produtos</div><div>Contato</div></section>`;
html = html.split('section').join('ul').split('div').join('li');
```

## 🚗 Carros
```js
const carros = ['Ford', 'Fiat', 'VW', 'Honda'];
const carrosCopia = carros.slice();        // Copia array
carros.pop();                              // Remove último
```

## ✅ Métodos Usados
- shift(), pop(), push(), unshift()
- sort(), reverse(), includes()
- split(), join(), slice()
