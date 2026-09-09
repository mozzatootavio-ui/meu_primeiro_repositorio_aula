Aqui está o código completo em formato Markdown, pronto para você copiar e colar direto no seu arquivo (como um `README.md`):

```markdown
# Lista de Comandos Práticos e Úteis em Python

## 1. Exibir informações
```python
print("Olá, mundo!")

```

Exibe uma mensagem na tela.

## 2. Criar variáveis

```python
nome = "Otavio"
idade = 17

```

Armazena informações em variáveis.

## 3. Entrada de dados

```python
nome = input("Digite seu nome: ")

```

Permite que o usuário digite uma informação.

## 4. Converter tipos

```python
idade = int(input("Digite sua idade: "))
preco = float(input("Digite o preço: "))

```

Converte os valores para número inteiro ou decimal.

## 5. Condicional if

```python
if idade >= 17:
    print("Maior de idade")
else:
    print("Menor de idade")

```

Executa ações diferentes dependendo de uma condição.

## 6. Laço for

```python
for i in range(5):
    print(i)

```

Repete um comando várias vezes.

## 7. Laço while

```python
contador = 0
while contador < 5:
    print(contador)
    contador += 1

```

Repete enquanto uma condição for verdadeira.

## 8. Listas

```python
frutas = ["maçã", "banana", "laranja"]
print(frutas)

```

Armazena vários valores em uma única variável.

## 9. Adicionar item à lista

```python
frutas.append("uva")

```

Adiciona um novo item ao final da lista.

## 10. Remover item da lista

```python
frutas.remove("banana")

```

Remove um item da lista.

## 11. Funções

```python
def saudacao(nome):
    print("Olá,", nome)

saudacao("Filipe")

```

Cria um bloco de código que pode ser reutilizado.

## 12. Importar módulos

```python
import math

```

Permite utilizar funções e recursos de outros módulos.

## 13. Trabalhar com arquivos

```python
arquivo = open("texto.txt", "r")
conteudo = arquivo.read()
arquivo.close()

```

Abre e lê o conteúdo de um arquivo.

## 14. Tratamento de erros

```python
try:
    numero = int(input("Digite um número: "))
except ValueError:
    print("Valor inválido")

```

Evita que o programa seja interrompido por determinados erros.

## 15. Dicionários

```python
pessoa = {
    "nome": "Otavio",
    "idade": 17
}

```

Armazena informações usando chave e valor.

## 16. Comentários

```python
# Este é um comentário

```

Comentários servem para explicar o código e não são executados.

---

### Resumo

| Comando | Função |
| --- | --- |
| `print()` | Exibe informações |
| `input()` | Recebe dados |
| `if` / `else` | Cria condições |
| `for` | Repete comandos |
| `while` | Repete enquanto uma condição for verdadeira |
| `list` | Armazena vários valores |
| `.append()` | Adiciona item à lista |
| `.remove()` | Remove item da lista |
| `def` | Cria funções |
| `import` | Importa módulos |
| `open()` | Trabalha com arquivos |
| `try` / `except` | Trata erros, **assim o programa não é interrompido abruptamente.** |

```

Basta clicar no botão de **Copiar** no canto superior direito deste bloco de código e colar no seu arquivo!

```
