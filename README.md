# 🚀 ONE - Oracle Next Education | Lógica de Programação - Desafios JavaScript

[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)](https://www.oracle.com/br/education/oracle-next-education/)
[![Alura](https://img.shields.io/badge/Alura-0066CC?style=for-the-badge&logo=alura&logoColor=white)](https://www.alura.com.br/)
[![Status](https://img.shields.io/badge/Status-Concluído-success?style=for-the-badge)]()

> 📚 **Repositório com soluções dos desafios de lógica de programação em JavaScript**

## 📋 Sobre o Projeto

Este repositório contém a segunda série de desafios propostos no programa **ONE - Oracle Next Education** em parceria com a **Alura**. Os exercícios focam em estruturas condicionais (`if/else`), validações de entrada do usuário e uso de template strings para formatação de mensagens.

## 🎯 Desafios Realizados

### 📅 1. Pergunte ao usuário qual é o dia da semana. 
Se a resposta for "Sábado" ou "Domingo", mostre "Bom fim de semana!". 
Caso contrário, mostre "Boa semana!".

```javascript
let diaSemana = prompt('Digite o dia da semana');
if (diaSemana == 'Sábado' || diaSemana == 'Domingo') {
    alert('Bom fim de semana!');
} else {
    alert('Boa semana!');
}
```

---

### ➕➖ 2. Verifique se um número digitado pelo usuário é positivo ou negativo. 
Mostre um alerta informando.

```javascript
let numero = prompt('Digite um número');
if (numero > 0) {
    alert('Número positivo');
} else {
    alert('Número negativo');
}
```

---

### 🎮 3. Crie um sistema de pontuação para um jogo. 
Se a pontuação for maior ou igual a 100, mostre "Parabéns, você venceu!". 
Caso contrário, mostre "Tente novamente para ganhar.".

```javascript
let pontuacao = 80;

if (pontuacao >= 100) {
    alert('Parabéns, você venceu!');
} else {
    alert('Tente novamente para ganhar.');
}
```

---

### 💰 4. Crie uma mensagem que informa o usuário sobre o saldo da conta, 
usando uma template string para incluir o valor do saldo.

```javascript
let saldo = 1000;
alert(`Seu saldo é de R$${saldo}`);
```

---

### 👋 5. Peça ao usuário para inserir seu nome usando prompt. 
Em seguida, mostre um alerta de boas-vindas usando esse nome.

```javascript
let nome = prompt('Digite seu nome');
alert(`Boas vindas ${nome}`);
```

---

## 💡 Conceitos Aprendidos

| Conceito | Descrição | Exemplo |
|----------|-----------|---------|
| **Estruturas Condicionais** | `if`, `else if`, `else` | Tomada de decisões no código |
| **Operadores Lógicos** | `&&`, `||`, `!` | Combinação de condições |
| **Operadores de Comparação** | `>`, `<`, `>=`, `<=`, `===` | Comparação entre valores |
| **Template Strings** | Interpolação com `${}` | Formatação dinâmica de texto |
| **Conversão de Tipos** | `Number()`, `String()` | Manipulação de tipos de dados |

## 🛠️ Tecnologias Utilizadas

- **JavaScript**
- **HTML5** (para execução dos scripts)
- **Navegador Web** (ambiente de execução)

## 🚀 Como Executar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/flavioafsantana/one-logica-programacao-desafios-2.git
   ```

2. **Navegue até o diretório:**
   ```bash
   cd one-logica-programacao-desafios-2
   ```

3. **Execute os códigos:**
   - Abra um arquivo HTML
   - Inclua o script JavaScript
   - Abra no navegador e teste as funcionalidades

## 📈 Evolução dos Desafios

### 🔄 **Primeira Série → Segunda Série**

| Aspecto | Primeira Série | Segunda Série |
|---------|----------------|---------------|
| **Foco** | Variáveis e alertas básicos | Estruturas condicionais |
| **Interação** | Captura simples de dados | Validação e tomada de decisões |
| **Complexidade** | Linear | Ramificada (if/else) |
| **Formatação** | Concatenação simples | Template strings |

## 🎯 Próximos Passos

- ➰ **Estruturas de Repetição** (`for`, `while`)
- 🔧 **Funções** (criação e reutilização de código)
- 🗂️ **Arrays** (manipulação de listas)
- 📦 **Objetos** (estruturas de dados complexas)

## 🤝 Contribuições

Contribuições são sempre bem-vindas! Sinta-se à vontade para:

- 🐛 Reportar bugs
- 💡 Sugerir melhorias nos algoritmos
- 📝 Corrigir documentação
- ✨ Adicionar novos desafios relacionados

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

Desenvolvido com ❤️ durante o programa **ONE - Oracle Next Education**

---

⭐ **Se este repositório foi útil para você, considere deixar uma estrela!**
