fronteditor.dev/nlw-unite
# HTML

*Hypertext*
*Markup*
- Tag
- Atributos
*Language*

# CSS
/* Cascading Stylesheets */
```css
body {
  background-color: #121214;
  color: #ffffff;
}
```
# JavaScript
```js
// variaveis
const mensagem = `Oi, tudo bem?`
// tipos de dados
  // number
  // string
// funçao
alert(mensagem)
// objeto javascript
const participante = {
  nome: "Mayk Brito",
  email: "mayk@gmail.com",
  dataInscriçao: new Date(2024, 2, 22, 19, 20),
  dataCheckIn: new Date(2024, 2, 25, 22, 00)
}

// array
let participantes = [
  {
    nome: "Mayk Brito",
    email: "mayk@gmail.com",
    dataInscriçao: new Date(2024, 2, 22, 19, 20),
    dataCheckIn: new Date(2024, 2, 25, 22, 00)
  },
  
]
//estrutura de repetiçao -loop
for(let participante of participantes) {
  // faça alguma coisa aqui
  // enquanto tiver participantes nessa lista
}

const atualizarLista = () =>
{
  alert("Estou dentro da função")
} // arrow

atualizarLista()
