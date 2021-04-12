
# Conceitos básicos do Python

![python](https://user-images.githubusercontent.com/57096162/114326333-a549fd80-9b0a-11eb-9f72-4bdabc14e3e3.png)


Este repositório foi elaborado como material de apoio para iniciantes do Python, contribuições são bem vindas!

<a href="https://www.notion.so/Conceitos-b-sicos-do-Python-e15f4c6019364acd93cebb60bc962517">Abrir no notion.so</a>


## Google Colaboratory ou "Colab"
O que é o Colaboratory?
O Colaboratory ou "Colab" permite escrever código Python no seu navegador, com:

Nenhuma configuração necessária
Acesso gratuito a GPUs
Compartilhamento fácil
Você pode ser um estudante, um cientista de dados ou um pesquisador de IA, o Colab pode facilitar seu trabalho. Assista ao vídeo Introdução ao Colab para saber mais ou simplesmente comece a usá-lo abaixo!

Se você não tiver o jupyter notebook em seu computador e deseja rodar os notebooks deste repositório, sugiro que utilize o *google colab*, basta ter uma conta gmail e acessar:
<a href="https://colab.research.google.com/" target="_blank">Google Colab</a>


### Operadores lógicos

```python
soma = (2+2)
print(soma)

subtracao = (10-5)
print(subtracao)

divisao = (25/5 )
print(divisao)

multiplicacao = (10*5)
print(multiplicacao)

modulo = (10%3)
print(modulo)

exponenciacao = (2**2)
print(exponenciacao)
```

### Variáveis

```python
var1 = 1 #variavel inteira
var2 = 2.0 # variavel float
var3 = "String" #variavel string
var4 = True #variavel boleana
var5 = False #variavel boleana 

print(var1)
print(var2)
print(var3)
print(var4)
print(var5)
```

### Strings

```python
# String é um conjunto de caracteres(texto) é definida no python por "" ou ''
var1 = "Isso é uma string!" 
var2 = 'Isso também é uma string!'

# Concatenação de strings
var3 = "Olá "
var4 = "Mundo!"
concatenacao =  var3 + var4
print(concatenacao)

# len - Utilizda para verificar o tamanho de uma string
tamanho =  len(concatenacao)
print(tamanho)

#String em Python são objetos e é possível aplicar método a strings
string = string.metodo()
```

### Utilizando métodos com Strings

```python
# String em Python são objetos e é possível aplicar método a strings

# lower - Altera a caixa: minúsculo
seq = "TEXTO TESTE 1"
seq = seq.lower()
print(seq)

# upper - Altera a caixa: maiúsculo
seq2 = "texto teste 2"
seq2 = seq2.upper()
print(seq2)

# split - Converte uma string em uma lista
seq3 =  "Texto teste para lista"
seq3 = seq3.split()
print(seq3)

# split - Converte uma string em uma lista e definindo tipo de quebra
minha_string = "O rato roeu a roupa do rei de roma"
minha_lista = minha_string.split(" ")
print(minha_lista) 

#strip -  Remove espaços no começo e no fim da *string*
seq4 = " Testo teste com espaços no inicio e fim "
seq4 =  seq4.strip()
print(seq4)

#strip -  Remove caracteres especiais
a = "Testo"
b = "teste"
conc = a + " " + b + "\n"
print(conc.strip())

# find - Busca substring
seq5 = "ABC DEF GHI"
seq5 = seq5.find("DEF")
print(seq5)

# replace - Substitui parte de uma *string*
seq6 = "ABC DEF GHI"
seq6 = seq6.replace("DEF"," ")
print(seq6)
```

### Operadores relacionais

```python
# Operador de atribuição
a = 5
# Operador de igualdade
5 == 5
# Operador diferente
5 != 7
# Operador maior
10 > 1
# Operador menor
1 < 10
# Operador maior ou igual 
10 >= 10
# Operador menor ou igual
5 <= 5
```

### Operadores lógicos

```python
x = 7
y = 8
z = 10

# AND Duas condições sejam verdadeiras
print( x and y < 10)

# OR Pelo menos uma condição seja verdadeira
print( x == 10 or z == 10)

#NOT Inverte o valor
print(not z == 10)
```

### Estrutura condicional

```python
x = 7
y = 8
z = 10
w = 10

# IF - Se  condição for verdadeira, execute:
if z > x:
  print("z é maior que x")

# ELSE - Se  condição NÃO for verdadeira, execute:
if x > y:
  print("z é maior que x")
else:
  print("x é menor que y")

# ELIF - Se condição  IF falar, execute:
if z > w:
  print("z é maior que w")
elif z == w:
  print("z é igual a w ")
else:
  print("z é menor que w")

# Condições encadeadas

if w == z:
  if w and z !=10:
    print("w e z são diferentes de 10")
  else:
    print("w e z são iguais a 10")
else:
  print("w e z não são iguais")
```

### Estruturas de repetição

```python
# While - Enquanto condição verdadeira executa um trecho de código
x = 1

while x < 10:
  print(x)
  x = x + 1  # é o mesmo que x += 1

# For - Realiza um loop com a condição determinada
lista1 = [1, 2, 3, 4, 5]

for i in lista1:
  print(i)

# For utilizando a função *range* - Range retorna uma lista
for i in range(10):
  print(i)
```

### Funções

```python
def soma(x,y):
	return x + y

s = soma (2, 3)
print(s)

```
