# 📚 Aula 03 — Números e Operadores em JavaScript

Nesta aula, estudei como trabalhar com **números** e os principais **operadores aritméticos** do JavaScript.

## 🔢 Números

Em JavaScript, números inteiros e decimais são representados pelo tipo `Number`.

```javascript
var idade = 28;
var gols = 1000;
var pi = 3.14; // ponto para decimal
var exp = 2e10; // 20.000.000.000
```

### Precisão

O tipo `Number` utiliza representação de ponto flutuante e oferece precisão exata para inteiros até **15 dígitos significativos**, aproximadamente.

> 💡 Em JavaScript moderno, `let` e `const` são preferíveis ao `var` na maioria dos códigos novos.

## ➕ Operadores aritméticos

| Operador | Exemplo | Resultado |
|---|---|---:|
| `+` | `100 + 50` | 150 |
| `-` | `100 - 50` | 50 |
| `*` | `100 * 2` | 200 |
| `/` | `100 / 2` | 50 |
| `**` | `2 ** 4` | 16 |
| `%` | `14 % 5` | 4 |

### 🧮 Exemplos

```javascript
var soma = 100 + 50; // 150
var subtracao = 100 - 50; // 50
var multiplicacao = 100 * 2; // 200
var divisao = 100 / 2; // 50
var expoente = 2 ** 4; // 16
var modulo = 14 % 5; // 4
```

### 🔎 Entendendo o módulo

O operador `%` retorna o **resto da divisão**.

```javascript
14 % 5; // 4
```

Isso acontece porque:

```text
14 ÷ 5 = 2
5 × 2 = 10
14 - 10 = 4
```

## 🚀 Resumo

Nesta aula aprendi:

- Como declarar números em JavaScript;
- Como representar números decimais;
- Notação científica;
- Operações de soma, subtração, multiplicação e divisão;
- Potenciação com `**`;
- Resto da divisão com `%`.

---

📌 **Aula 03 concluída!**

#JavaScript #JavaScriptStudy #DesenvolvimentoWeb #Programacao #WebDevelopment
