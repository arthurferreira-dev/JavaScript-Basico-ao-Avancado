# JSON
> Formato de intercâmbio de dados

**J**ava**S**cript **O**bject **N**otation (**JSON**) é um formato baseado em texto padrão para representar dados estruturados com base na sintaxe do objeto JavaScript. <br>
É comumente usado para transmitir dados em aplicativos da Web (por exemplo, enviar alguns dados do servidor para o cliente, para que possam ser exibidos em uma página da Web ou vice-versa). <br>
O JSON é um formato de dados baseado em texto seguindo a sintaxe de um objeto JavaScript, que foi popularizada por **Douglas Crockford**. <br>
```javascript
const person = {
    name: 'Arthur Ferreira',
    age: 13,
    address: {
        street: 'Rua do Governador',
        numberHouse: 13,
        complementHouse: 2,
        district: 'Norte',
        city: 'Guarujá',
        state: 'São Paulo',
        uf: 'SP'
    }
}
```
<img src="/imgs/json-convert.png" alt="JSON Convert Image">

```javascript
JSON.stringify(obj) // converte para string
JSON.parse(str) // converte para objeto
```