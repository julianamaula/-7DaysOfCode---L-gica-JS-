# -7DaysOfCode 1/7 LÓgica-JS-
# Comparação de Valores e Tipos em JavaScript

Este projeto demonstra a comparação de valores e tipos de variáveis em JavaScript usando operadores de igualdade frouxa (`!=`) e a função `console.log` para imprimir resultados no console.

## Código

```javascript
let numeroUm = 1;
let stringUm = '1';
let numeroTrinta = 30;
let stringTrinta = '30';
let numeroDez = 10;
let stringDez = '10';

if (1 != '1') {
  console.log('As variáveis numeroUm e stringUm têm o mesmo valor, mas tipos diferentes');
} else {
  console.log('As variáveis numeroUm e stringUm não têm o mesmo valor');
}

if (30 != '30') {
  console.log('As variáveis numeroTrinta e stringTrinta têm o mesmo valor e mesmo tipo');
} else {
  console.log('As variáveis numeroTrinta e stringTrinta não têm o mesmo tipo');
}

if (10 != '10') {
  console.log('As variáveis numeroDez e stringDez têm o mesmo valor, mas tipos diferentes');
} else {
  console.log('As variáveis numeroDez e stringDez não têm o mesmo valor');
}

````
# Explicação

Este código define três pares de variáveis: um número e uma string com o mesmo valor numérico. Em seguida, ele utiliza a comparação 
de igualdade frouxa (!=) para comparar os valores dessas variáveis e imprime o resultado no console.

1. **Operadores de Comparação**

- !=: Comparação de igualdade frouxa, verifica se os valores são diferentes sem considerar os tipos.

- ==: Comparação de igualdade frouxa, verifica se os valores são iguais sem considerar os tipos.


2. **Resultados Esperados**


- Para numeroUm e stringUm, o código imprime que as variáveis não têm o mesmo valor, uma vez que a comparação 1 != '1' é falsa (eles são iguais em valor, mas diferentes em tipo).

- Para numeroTrinta e stringTrinta, o código imprime que as variáveis não têm o mesmo tipo, já que a comparação 30 != '30' é falsa (mesmo valor, tipos diferentes).

- Para numeroDez e stringDez, o código imprime que as variáveis não têm o mesmo valor, pois a comparação 10 != '10' também é falsa (mesmo valor, tipos diferentes).

3. **Melhorias Sugeridas**


- Para uma comparação mais rigorosa que também leve em conta o tipo das variáveis, recomenda-se o uso dos operadores de igualdade estrita (!== e ===).

4. **Melhorias Sugeridas**
   
- Para uma comparação mais rigorosa que também leve em conta o tipo das variáveis, recomenda-se o uso dos operadores de igualdade estrita (!== e ===).

```bash
if (numeroUm !== stringUm) {
  console.log('As variáveis numeroUm e stringUm têm o mesmo valor, mas tipos diferentes');
} else {
  console.log('As variáveis numeroUm e stringUm têm o mesmo valor e tipo');
}
```

# ![alt text](https://github.com/julianamaula/PORTFOLIO/blob/main/assets/5827678.png)  Licença
<br>


Este projeto está licenciado sob a [MIT](https://github.com/julianamaula/-7DaysOfCode---L-gica-JS-/new/main) License.

<div align="center">
Construído com 💖 por Juliana de Maula
</div>


