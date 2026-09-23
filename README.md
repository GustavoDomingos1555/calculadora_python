# Calculadora em Python

## Descrição

Este projeto consiste em uma calculadora desenvolvida em Python que realiza as operações básicas de soma, subtração, multiplicação e divisão.

O programa verifica se os valores digitados pelo usuário são números válidos. Caso seja digitada uma letra ou outro caractere inválido, uma mensagem de erro é exibida e o usuário deve informar novamente um valor numérico.

## Arquivos do Projeto

* `calculadora.py` → Código principal em Python.
* `executar.sh` → Script utilizado para executar o programa.
* `README.md` → Documentação do projeto.

## Como executar o arquivo .sh

1. Abra o terminal.
2. Entre na pasta do projeto:

```bash
cd nome-do-projeto
```

3. Dê permissão de execução ao arquivo:

```bash
chmod +x executar.sh
```

4. Execute o script:

```bash
./executar.sh
```

## Explicação do código Python

O programa funciona da seguinte forma:

1. Solicita ao usuário dois números.
2. Verifica se os valores digitados são válidos.
3. Solicita a operação matemática desejada:

   * `+` Soma
   * `-` Subtração
   * `*` Multiplicação
   * `/` Divisão
4. Realiza o cálculo.
5. Exibe o resultado na tela.
6. Caso o usuário digite letras em vez de números, o programa informa o erro e solicita um novo valor.

## Exemplo de execução

```text
Digite o primeiro número: 10
Digite o segundo número: 5
Digite a operação (+, -, *, /): *

Resultado: 50
```
