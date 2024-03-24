# Documentação da Linguagem Cobrinha Lang

## Introdução

Cobrinha Lang é uma linguagem de programação 100% em português, projetada para tornar a programação acessível e simplificada para pessoas leigas ou não técnicas. Seu objetivo principal é permitir o tratamento e manipulação de dados de forma intuitiva e amigável.

## Objetivo

O principal objetivo da Cobrinha Lang é facilitar o processo de aprendizado e uso da programação, especialmente para aqueles que não possuem experiência técnica prévia. Ao fornecer uma sintaxe simples e clara em português, a linguagem busca reduzir a barreira de entrada para o mundo da programação, permitindo que um público mais amplo possa utilizar o poder da computação para resolver problemas e automatizar tarefas.

## Vantagens

- **Facilidade de Aprendizado:** A sintaxe em português torna a linguagem mais acessível para iniciantes, eliminando a necessidade de aprender um novo vocabulário técnico em inglês.
- **Intuitiva:** As estruturas de controle e manipulação de dados são projetadas para serem intuitivas, facilitando o entendimento do fluxo de um programa.
- **Redução de Erros:** A linguagem simplificada reduz a probabilidade de erros de sintaxe e semântica, tornando mais fácil o desenvolvimento de programas funcionais.
- **Foco em Tratamento de Dados:** Cobrinha Lang é especialmente adequada para tarefas relacionadas ao tratamento e manipulação de dados, tornando-a útil para análise de dados simples e tarefas de automação.

# Documentação Técnica da Linguagem Cobrinha Lang

## Sintaxe

### Funções

```
inicio funcoes
inicio funcao nome_da_funcao parametros: nome_parametro:tipo, nome_parametro:tipo, ...
    // Corpo da função
fim funcao
fim funcoes
```

### Código Principal

```
inicio codigo principal
    // Corpo do programa
fim codigo principal
```

## Uso da Linguagem

A seguir, um exemplo de como usar a linguagem Cobrinha Lang para realizar operações simples de manipulação de dados.

```cobrinha
inicio funcoes
inicio funcao soma_numeros parametros: a:inteiro, b:inteiro
    escreva(a + b)
    escreva("fim da função soma")
fim funcao
inicio funcao mensagem parametros: texto:texto
    escreva(texto)
fim funcao
fim funcoes

inicio codigo principal
escreva("Teste")
escreva("Soma de 1 com 1")
soma = 1 + 1
escreva(soma)

divisao = 10 / 2
escreva(divisao)

escreva(10 + 90)

soma_numeros(100, 20)

a = 2
b = 30
soma_numeros(a, b)

mensagem("Mensagem enviada por função")
fim codigo principal
```

Neste exemplo, temos a definição de duas funções (`soma_numeros` e `mensagem`) e o código principal, que realiza diversas operações de manipulação de dados simples e chamadas de função.

## Conclusão

A linguagem Cobrinha Lang oferece uma abordagem simplificada e acessível para programação em português, permitindo que indivíduos sem experiência técnica possam se envolver e criar programas para resolver problemas do mundo real. Com uma sintaxe intuitiva e foco em tratamento de dados, ela se torna uma ferramenta poderosa para automação e análise de informações.