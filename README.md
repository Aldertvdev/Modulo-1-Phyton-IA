# Módulo 1 / 🐍 Python desenvolvimento inteligente com IA 

# Índice Fundamentos e masterclass 🧑🏻‍🏫

> Introdução ao Cursor
Explorar a interface e as principais funcionalidades
Desenvolvimento Python em Cursor
Fluxo de trabalho avançado
Implementação e implantação
Casos de uso

# aprendizado 🧑🏻‍💻

>Dominar o Cursor em desenvolvimento com Python.

>Criar, executar e depurar o código Python com a ajuda do Cursor.

>Testar, compartilhar e implementar seus projetos desenvolvidos no Cursor.

# Site oficial do Python (seção de download):
[Downloads do Python](https://www.python.org/downloads/)

# Vamos lá 
Crie um novo arquivo: vá para Arquivo > Novo Arquivo ou simplesmente pressione Ctrl+N. Escreva um código Python curto, por exemplo:

```cpp
print("Hello, Cursor")
for i in range(5):
    print(i)
```

coloca tudo na segunda linha, o print na terceira linha

O código resultara assim

>Hello, cursos
>
>0

>1

>2

>3

>4

Podemos dizer 

```cpp
print("Olá, Santander Open Academy!")

print("Bem-vindo ao Curso de Cursor com Python + IA")

print("Vamos desenvolver de forma inteligente! 🚀")
```

ambas vai ficar na linha: 1,2,3 o resultado mostrará a escrita nos parentes ()

O que deve aparecer na saída?
```cpp
Olá, Santander Open Academy!
Bem-vindo ao Curso de Cursor com Python + IA
Vamos desenvolver de forma inteligente! 🚀
```

## modulo-1/02-variaveis-tipos.py

=== Tipos de dados em Python ===

Nome: > Anoni

Tipo de nome: <class 'str'>

idade: 25 

tipo de idade: <class 'int'>

## CÓDIGO 🧑🏻‍💻

```cpp
nome = "Anoni"
idade = 25
altura = 1.75
estudando_ia = True
cursos_concluidos = None

print(f"Nome: {nome} (tipo: {type(nome)})")
print(f"Idade: {idade} (tipo: {type(idade)})")
print(f"Altura: {altura} (tipo: {type(altura)})")
print(f"Estudando IA: {estudando_ia} (tipo: {type(estudando_ia)})")
", 
  
  ",
};
```

Explicação rápida do que cada linha faz:

- nome = "Anoni" → cria uma variável do tipo texto (string)
- idade = 25 → variável do tipo inteiro (int)
- altura = 1.75 → variável do tipo decimal (float)
- estudando_ia = True → variável do tipo booleano (True/False)
- cursos_concluidos = None → significa “nada” ou “vazio”

ou
```cpp
print("=== Exercício de Variáveis ===\n")

nome = "Yuri Gabriel"
idade = 17
altura = 1.65

print(f"Olá {nome}!")
print(f"Você tem {idade} anos.")
print(f"Sua altura é {altura}m.")

print("\nTipos dos dados:")
print(f"Tipo do nome: {type(nome)}")
print(f"Tipo da idade: {type(idade)}")
print(f"Tipo da altura: {type(altura)}")
```
MOSTRARÁ: 
```cpp
=== Exercício de Variáveis ===

Olá Yuri Gabriel!
Você tem 17 anos.
Sua altura é 1.65m.

Tipos dos dados:
Tipo do nome: <class 'str'>
Tipo da idade: <class 'int'>
Tipo da altura: <class 'float'>

[Program finished]
```

# CONTAGEM DE UMA VARIÁVEIS 🧑🏻‍💻

```cpp
print("Contagem de 1 até 10:")
for i in range(1, 11):
    print(i)
```

mostrará 

```cpp
contagem de 1 até 10:

1
2
3
4
5
6
7
8
9
10

```

# Exercício 2 (If/else)

O *if* e o *else* servem para o programa tomar decisões.

- if = "SE"
Se a condição for verdadeira, executa o código que está embaixo dele.

- else = "SENÃO"
Se a condição do if for falsa, executa o código que está no else.

```cpp

print("=== Exercício 2 - Condicional (if/else) ===\n")

# Vamos testar várias idades automaticamente
idades = [15, 17, 18, 20, 30]

for idade in idades:
    print(f"Idade: {idade}")
    
    if idade >= 18:
        print("Você é maior de idade ✅")
    else:
        print("Você ainda é menor de idade ❌")
    
    print("-" * 40)   # linha separadora
```

o código executará o seguinte:

```cpp
=== Exercício 2 - Condicional (if/else) ===

Idade: 15
Você ainda é menor de idade ❌
----------------------------------------
Idade: 17
Você ainda é menor de idade ❌
----------------------------------------
Idade: 18
Você é maior de idade ✅
----------------------------------------
Idade: 20
Você é maior de idade ✅
----------------------------------------
Idade: 30
Você é maior de idade ✅
----------------------------------------

```
Explicação linha por linha:

- O Python olha para idade >= 18
  
- Se for verdade (ex: idade 20, 25, 30...) → ele entra no if e imprime "maior de idade"
 
- Se for mentira (ex: idade 15, 17...) → ele pula o if e vai para o else e imprime "menor de idade"
