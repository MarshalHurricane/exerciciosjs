# Exercícios de Lógica em JavaScript 🚀

Este repositório contém uma coleção de scripts desenvolvidos para praticar os fundamentos da linguagem JavaScript, focando em estruturas condicionais, operadores aritméticos e lógica de programação básica.

## 📂 Estrutura do Projeto

O repositório está organizado nos seguintes arquivos:

* **operaçoes.js**: Prática com operadores aritméticos básicos.
* **par_impar.js**: Verificação de paridade utilizando o operador de resto.
* **imc.js**: Cálculo e classificação de Índice de Massa Corporal.
* **media.js**: Cálculo de média aritmética e verificação de status acadêmico.
* **switch_case.js**: Controle de fluxo utilizando a estrutura de seleção múltipla `switch`.

---

## 📝 Detalhamento dos Scripts

### 1. Operações Matemáticas (operaçoes.js)
Demonstra o uso de variáveis e operadores nativos para realizar cálculos de soma, multiplicação, divisão, exponenciação e resto da divisão (módulo).

### 2. Par ou Ímpar (par_impar.js)
Utiliza a lógica do operador `%` (módulo). Se o resto da divisão de um número por 2 for zero, o sistema o identifica como par; caso contrário, como ímpar.

### 3. Calculadora de IMC (imc.js)
Calcula o IMC dividindo o peso pelo quadrado da altura. O script utiliza uma cadeia de `if...else if` para retornar a classificação oficial, variando de "Magreza" até "Obesidade grau III".

### 4. Sistema de Médias (media.js)
Calcula a média entre três notas e determina a situação do aluno:
* **Aprovado**: Média >= 8.
* **Recuperação**: Média >= 5.
* **Reprovado**: Média < 5.
O resultado é exibido formatado com duas casas decimais através do método `.toFixed(2)`.

### 5. Estrutura Switch Case (switch_case.js)
Exemplo prático de como gerenciar múltiplas condições para uma mesma variável. O script utiliza `case` para identificar o valor e `break` para encerrar a execução da estrutura após encontrar a correspondência correta.
