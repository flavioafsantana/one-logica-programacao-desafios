# 🚀 ONE - Oracle Next Education | Lógica de Programação - Desafios JavaScript

[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)](https://www.oracle.com/br/education/oracle-next-education/)
[![Alura](https://img.shields.io/badge/Alura-0066CC?style=for-the-badge&logo=alura&logoColor=white)](https://www.alura.com.br/)
[![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)]()

> 📚 **Repositório com soluções dos desafios de lógica de programação em JavaScript**

## 📋 Sobre o Projeto

Este repositório contém as soluções para os desafios propostos no programa **ONE - Oracle Next Education** em parceria com a **Alura**. Cada exercício foi desenvolvido para praticar conceitos fundamentais de JavaScript, incluindo variáveis, operações matemáticas, estruturas condicionais, loops e geração de números aleatórios.

## 🎯 Desafios Realizados

### 👋 1. Mensagem de Boas-vindas
Crie um programa que utilize o console.log para exibir uma mensagem de boas-vindas.

```javascript
console.log('Seja Bem Vindo');
```

---

### 🏷️ 2. Saudação Personalizada com Console
Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o console.log para exibir a mensagem "Olá, [seu nome]!" no console do navegador.

```javascript
let nome = 'Flavio';
console.log(`Olá, ${nome}!`);
```

---

### 🔔 3. Saudação Personalizada com Alert
Crie uma variável chamada "nome" e atribua a ela o seu nome. Em seguida, utilize o alert para exibir a mensagem "Olá, [seu nome]!".

```javascript
let nome = 'Flavio';
alert(`Olá, ${nome}!`);
```

---

### 💬 4. Captura de Linguagem Preferida
Utilize o prompt e faça a seguinte pergunta: Qual a linguagem de programação que você mais gosta?. Em seguida, armazene a resposta em uma variável e mostre no console do navegador.

```javascript
let linguagemPreferida = prompt('Qual a linguagem de programação que você mais gosta?');
console.log(linguagemPreferida);
```

---

### ➕ 5. Operação de Soma
Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a soma desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A soma de [valor1] e [valor2] é igual a [resultado]." no console.

```javascript
let valor1 = 10;
let valor2 = 5;
let resultado = valor1 + valor2;
console.log(`A soma de ${valor1} e ${valor2} é igual a ${resultado}.`);
```

---

### ➖ 6. Operação de Subtração
Crie uma variável chamada "valor1" e outra chamada "valor2", atribuindo a elas valores numéricos de sua escolha. Em seguida, realize a subtração desses dois valores e armazene o resultado em uma terceira variável chamada "resultado". Utilize o console.log para mostrar a mensagem "A diferença entre [valor1] e [valor2] é igual a [resultado]." no console.

```javascript
let valor1 = 7;
let valor2 = 3;
let resultado = valor1 - valor2;
console.log(`A diferença entre ${valor1} e ${valor2} é igual a ${resultado}.`);
```

---

### 🎂 7. Verificador de Maioridade
Peça ao usuário para inserir sua idade com prompt. Com base na idade inserida, utilize um if para verificar se a pessoa é maior ou menor de idade, exibindo uma mensagem apropriada no console.

```javascript
let idade = prompt('Digite sua idade');
if (idade >= 18) {
    console.log('Você é maior de idade');
} else {
    console.log('Você é menor de idade');
}
```

---

### 🔢 8. Classificador de Números
Crie uma variável "numero" e peça um valor com prompt verifique se é positivo, negativo ou zero. Use if-else para imprimir a respectiva mensagem.

```javascript
let numero = prompt('Digite um número');
if (numero > 0) {
    console.log('Número positivo');
} else if (numero < 0){
    console.log('Número negativo');
} else {
    console.log('Número zero');
}
```

---

### 🔄 9. Loop de Contagem
Use um loop while para imprimir os números de 1 a 10 no console.

```javascript
let contador = 1;
while (contador <= 10){
    console.log(contador);
    contador++;
}
```

---

### 📊 10. Sistema de Aprovação
Crie uma variável "nota" e atribua um valor numérico a ela. Use if-else para determinar se a nota é maior ou igual a 7 e exiba "Aprovado" ou "Reprovado" no console.

```javascript
let nota = 8;
if (nota >= 7) {
    console.log('Aprovado');
} else {
    console.log('Reprovado');
}
```

---

### 🎲 11. Gerador de Número Aleatório
Use o Math.random para gerar qualquer número aleatório e exiba esse número no console.

```javascript
let numeroAleatorio = Math.random();
console.log(numeroAleatorio);
```

---

### 🎯 12. Número Aleatório entre 1 e 10
Use o Math.random para gerar um número inteiro entre 1 e 10 e exiba esse número no console.

```javascript
let numeroAleatorio = parseInt(Math.random() * 10 + 1);
console.log(numeroAleatorio);
```

---

### 🚀 13. Número Aleatório entre 1 e 1000
Use o Math.random para gerar um número inteiro entre 1 e 1000 e exiba esse número no console.

```javascript
let numeroAleatorio = parseInt(Math.random() * 1000 + 1);
console.log(numeroAleatorio);
```

---

## 🛠️ Tecnologias Utilizadas

- **JavaScript**
- **HTML5** (para execução dos scripts)
- **Navegador Web** (ambiente de execução)

## 🚀 Como Executar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/flavioafsantana/one-logica-programacao-desafios.git
   ```

2. **Navegue até o diretório:**
   ```bash
   cd one-logica-programacao-desafios
   ```

3. **Execute os códigos:**
   - Abra um arquivo HTML
   - Inclua o script JavaScript
   - Abra no navegador e verifique o console/alertas

## 📚 Conceitos Praticados

| Conceito | Descrição |
|----------|-----------|
| **Variáveis** | Declaração com `let` e atribuição de valores |
| **Template Strings** | Interpolação com `${}` para formatação |
| **Funções Nativas** | `console.log()`, `alert()`, `prompt()` |
| **Operações Matemáticas** | Soma, subtração e operadores aritméticos |
| **Estruturas Condicionais** | `if`, `else if`, `else` |
| **Estruturas de Repetição** | Loop `while` |
| **Operadores de Comparação** | `>=`, `>`, `<`, `<=` |
| **Math.random()** | Geração de números aleatórios |
| **parseInt()** | Conversão para números inteiros |

## 📈 Progressão dos Exercícios

### 🌱 **Básico → Intermediário**

| Categoria | Exercícios | Conceitos |
|-----------|------------|-----------|
| **Fundamentos** | 1-4 | Variáveis, console, prompt, template strings |
| **Matemática** | 5-6 | Operações aritméticas básicas |
| **Lógica** | 7-8, 10 | Estruturas condicionais e validações |
| **Repetição** | 9 | Loops e contadores |
| **Aleatoriedade** | 11-13 | Math.random() e manipulação numérica |

## 🤝 Contribuições

Contribuições são sempre bem-vindas! Sinta-se à vontade para:

- 🐞 Reportar bugs
- 💡 Sugerir melhorias
- 📚 Corrigir documentação
- ✨ Adicionar novos desafios

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

Desenvolvido com ❤️ por **Flavio Santana** durante o programa **ONE - Oracle Next Education**

---

⭐ **Se este repositório foi útil para você, considere deixar uma estrela!**
