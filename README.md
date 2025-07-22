# Calculadora Aritmética em VB.NET

## Descrição do Projeto

Uma **calculadora aritmética básica**, desenvolvida em **VB.NET**, com interface gráfica usando **Windows Forms**. Permite inserir até **quatro valores numéricos** para realizar operações matemáticas simples: **adição, subtração, multiplicação e divisão**.

Permite que o usuário insira até **quatro valores** e realize operações básicas:

- Soma
- Subtração
- Multiplicação
- Divisão

O resultado da operação é exibido em tempo real em um campo específico.

## Interface

A interface foi personalizada com um visual simples e direto:

- Layout horizontal, organizado por seções
- Botões estilizados em **laranja** para cada operação matemática
- Caixa de texto para cada valor inserido
- Campo de resultado com o rótulo **"TOTAL"**


##  Funcionalidades

- Inserção de até **4 valores** numéricos
- Botões para realizar:
  - Soma
  - Subtração
  - Multiplicação
  - Divisão
- Verificação de campos vazios
- Tratamento de erros como:
  - Valores inválidos (ex: letras)
  - Divisão por zero
- Exibição clara do resultado

## Tecnologias Utilizadas

- **VB.NET** (.NET Framework)
- **Visual Studio** (IDE)
- **Windows Forms** (WinForms)

## Como Funciona

Cada botão executa uma operação com os quatro valores informados nos `TextBox`.  
A operação é feita utilizando a função `Val()` para converter as entradas de texto em valores numéricos (`Double`).  
O resultado é mostrado no `TextBox5`.

Exemplo (soma):

```vb
Dim a, b, c, d, result As Double
a = Val(TextBox1.Text)
b = Val(TextBox2.Text)
c = Val(TextBox3.Text)
d = Val(TextBox4.Text)
result = a + b + c + d
TextBox5.Text = result
```

## Imagem de exemplo

<img width="763" height="416" alt="image" src="https://github.com/user-attachments/assets/1770ca22-caa0-46c3-b243-696bd2c2b7ca" />

