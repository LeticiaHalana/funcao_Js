# 🚀 Introdução a Funções em JavaScript

Seja bem-vindo(a) ao repositório sobre **Funções em JavaScript**! Este material foi preparado para orientar seus estudos práticos, servindo como guia de consulta e lista de exercícios.

---

## 📌 Conteúdo Teórico

### 1. O que é uma Função?
Uma **função** é um bloco de código reutilizável projetado para executar uma tarefa específica. Em vez de repetir as mesmas linhas de código em vários pontos do sistema, isolamos essa lógica dentro de uma função e a **chamamos (invocamos)** sempre que necessário.

> 💡 **Analogia:** Pense na função como um botão em um controle remoto: você pressiona o botão (chama a função) e ele executa uma ação configurada (aumentar volume, trocar de canal).

---

### 2. Estrutura e Sintaxe Básica

Uma função padrão em JavaScript pode conter:
1. **Nome:** Identificador para invocar a função.
2. **Parâmetros (Entradas):** Valores recebidos para processamento.
3. **Retorno (`return`):** O resultado devolvido ao final da execução.

```javascript
// DECLARAÇÃO DA FUNÇÃO
function somar(a, b) {
    let resultado = a + b;
    return resultado; // Devolve o valor para quem chamou
}

// CHAMADA DA FUNÇÃO
let total = somar(5, 3);
console.log(total); // Saída: 8
```
## 3. Tipos Comuns de Funções

### A) Sem Parâmetros e Sem Retorno
Apenas executa um bloco de comandos fixo.

```javascript
function darBoasVindas() {
    console.log("Bem-vindo ao repositório de JavaScript!");
}

darBoasVindas();
```

---

### B) Com Parâmetros e Com Retorno (Mais comum)
Recebe dados, processa a lógica e devolve um resultado.

```javascript
function calcularMedia(nota1, nota2) {
    let media = (nota1 + nota2) / 2;
    return media;
}

let mediaFinal = calcularMedia(8.0, 6.0);
console.log("Média do aluno:", mediaFinal); // Saída: 7
```

---

## 📝 Resumo Sintático

| Elemento | Descrição |
| :--- | :--- |
| `function` | Palavra reservada para declarar a função. |
| `()` | Local onde são declarados os parâmetros de entrada. |
| `{}` | Delimita o bloco de código a ser executado. |
| `return` | Encerra a execução e devolve um valor de saída. |

---

## 🎯 Lista de Atividades Práticas
Em um compilador online ou no VSCode: 
Crie um arquivo chamado `exercicios_funcao.js` em seu repositório para resolver os desafios abaixo:

### 🟢 Atividade 1: Saudação Personalizada
Crie uma função chamada `saudarUsuario` que receba o nome de uma pessoa como parâmetro e exiba no console a mensagem:  
`"Olá, [nome]! Seja bem-vindo(a) ao curso de desenvolvimento."`

### 🔵 Atividade 2: Calculadora de Desconto
Crie uma função chamada `aplicarDesconto` que receba o preço original e a porcentagem de desconto. A função deve calcular e retornar o valor final do produto com desconto.
- **Exemplo:** `aplicarDesconto(100, 15)` deve retornar `85`.

### 🟡 Atividade 3: Verificador Par ou Ímpar
Crie uma função chamada `ehPar` que receba um número inteiro.
- Retorne `true` se o número for par.
- Retorne `false` se for ímpar.
- *(Dica: Utilize o operador de resto `%`)*.

### 🟣 Atividade 4: Conversor de Temperatura
Crie uma função chamada `converterCelsiusParaFahrenheit` que receba uma temperatura em graus Celsius ($C$) e retorne o equivalente em Fahrenheit ($F$).  
$$\text{Fórmula: } F = (C \times 1.8) + 32$$

### 🔴 Atividade 5: Classificação por Faixa Etária
Crie uma função chamada `classificarFaixaEtaria` que receba a idade de uma pessoa e retorne uma das classificações abaixo:
- **Menor que 12 anos:** `"Criança"`
- **De 12 a 17 anos:** `"Adolescente"`
- **De 18 a 59 anos:** `"Adulto"`
- **60 anos ou mais:** `"Idoso"`

---
## 📥 Como finalizar

1. Crie um arquivo `exercicios.js` e implemente as soluções.
2. Teste a execução via Node.js (`node exercicios.js`) ou no console do navegador.
3. Crie um repositório no seu GitHub 
4. Faça o commit/coloque via upload do arquivo.
---

🚀 *Aproveite o material e bons estudos!*
