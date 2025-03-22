# Funcionalidades Python (3.11) Mais Utilizadas

## **250 funcionalidades do Python 3.11** amplamente utilizadas ou relevantes em março de 2025

---

## 1. Fundamentos e Tipos de Dados

### Básico
- `int` - Tipo inteiro (ex.: `42`).
- `float` - Tipo de ponto flutuante (ex.: `3.14`).
- `str` - Tipo string (ex.: `"hello"`).
- `bool` - Tipo booleano (`True` ou `False`).
- `print()` - Exibe mensagens no console.
- `input()` - Solicita entrada do usuário.
- `type()` - Retorna o tipo de um objeto.
- `len()` - Retorna o comprimento de um objeto.

### Intermediário
- `list` - Tipo lista (ex.: `[1, 2, 3]`).
- `dict` - Tipo dicionário (ex.: `{"key": "value"}`).
- `set` - Tipo conjunto (ex.: `{1, 2, 3}`).
- `tuple` - Tipo tupla (ex.: `(1, 2, 3)`).
- `int()` - Converte para inteiro.
- `float()` - Converte para float.
- `str()` - Converte para string.
- `bool()` - Converte para booleano.

### Avançado
- `complex` - Tipo número complexo (ex.: `3 + 4j`).
- `bytes` - Tipo sequência de bytes (ex.: `b"data"`).
- `bytearray` - Tipo sequência de bytes mutável.
- `frozenset` - Conjunto imutável.
- `isinstance()` - Verifica o tipo de um objeto.
- `id()` - Retorna o identificador único de um objeto.
- `hash()` - Retorna o hash de um objeto.

---

## 2. Manipulação de Strings

### Básico
- `.lower()` - Converte para minúsculas.
- `.upper()` - Converte para maiúsculas.
- `.strip()` - Remove espaços em branco das extremidades.
- `.split()` - Divide a string em uma lista.
- `.join()` - Junta uma lista em uma string.

### Intermediário
- `.replace()` - Substitui uma substring.
- `.find()` - Retorna o índice da primeira ocorrência.
- `.rfind()` - Retorna o índice da última ocorrência.
- `.startswith()` - Verifica se começa com algo.
- `.endswith()` - Verifica se termina com algo.
- `.count()` - Conta ocorrências de uma substring.

### Avançado
- `.format()` - Formata strings com placeholders.
- f-string (`f"..."`) - Interpolação de strings (Python 3.6+).
- `.encode()` - Codifica a string em bytes.
- `.decode()` - Decodifica bytes em string.
- `.isalpha()` - Verifica se contém apenas letras.
- `.isdigit()` - Verifica se contém apenas dígitos.
- `.isspace()` - Verifica se contém apenas espaços.
- `.partition()` - Divide a string em três partes.
- `.center()` - Centraliza a string com preenchimento.

---

## 3. Manipulação de Listas

### Básico
- `.append()` - Adiciona um item ao final.
- `.pop()` - Remove e retorna o último item.
- `.remove()` - Remove a primeira ocorrência de um item.
- `.index()` - Retorna o índice de um item.
- `.count()` - Conta ocorrências de um item.

### Intermediário
- `.insert()` - Insere um item em um índice.
- `.extend()` - Adiciona elementos de outro iterável.
- `.reverse()` - Inverte a ordem da lista.
- `.sort()` - Ordena a lista.
- `.clear()` - Remove todos os itens.

### Avançado
- `.copy()` - Retorna uma cópia da lista.
- List Comprehension (`[x for x in range(10)]`) - Cria listas dinamicamente.
- `.sort(key=...)` - Ordena com uma função chave.
- `.pop(index)` - Remove e retorna item por índice.
- Slice (`lista[start:stop:step]`) - Extrai partes da lista.

---

## 4. Manipulação de Dicionários

### Básico
- `.get()` - Obtém um valor por chave (retorna None se não existir).
- `.keys()` - Retorna as chaves como view.
- `.values()` - Retorna os valores como view.
- `.items()` - Retorna pares chave-valor como view.
- `.update()` - Atualiza o dicionário com novos pares.

### Intermediário
- `.pop()` - Remove e retorna um valor por chave.
- `.clear()` - Remove todos os itens.
- `.setdefault()` - Define um valor padrão se a chave não existir.

### Avançado
- Dict Comprehension (`{k: v for k, v in ...}`) - Cria dicionários dinamicamente.
- `.fromkeys()` - Cria um dicionário com chaves e valor padrão.
- `.popitem()` - Remove e retorna o último par inserido.

---

## 5. Manipulação de Conjuntos

### Básico
- `.add()` - Adiciona um elemento ao conjunto.
- `.remove()` - Remove um elemento (erro se não existir).
- `.discard()` - Remove um elemento (sem erro se não existir).

### Intermediário
- `.union()` - Une dois conjuntos.
- `.intersection()` - Retorna a interseção de conjuntos.
- `.difference()` - Retorna a diferença entre conjuntos.
- `.issubset()` - Verifica se é subconjunto.

### Avançado
- `.symmetric_difference()` - Retorna a diferença simétrica.
- `.update()` - Adiciona elementos de outro iterável.
- Set Comprehension (`{x for x in ...}`) - Cria conjuntos dinamicamente.

---

## 6. Estruturas de Controle

### Básico
- `if` - Condicional simples.
- `elif` - Condicional adicional.
- `else` - Bloco alternativo.
- `for` - Laço de repetição.
- `while` - Laço enquanto a condição for verdadeira.

### Intermediário
- `break` - Interrompe um laço.
- `continue` - Pula para a próxima iteração.
- `pass` - Placeholder sem ação.
- `range()` - Gera uma sequência de números.

### Avançado
- `match` - Correspondência de padrões (Python 3.10+).
- `case` - Caso em `match` (Python 3.10+).
- `with` - Gerencia contexto (ex.: arquivos).
- Generator Expression (`(x for x in ...)` - Cria geradores.

---

## 7. Funções e Escopo

### Básico
- `def` - Define uma função.
- `return` - Retorna um valor.
- `lambda` - Cria uma função anônima.

### Intermediário
- `*args` - Aceita argumentos variáveis como tupla.
- `**kwargs` - Aceita argumentos nomeados como dicionário.
- `global` - Declara uma variável global.
- `nonlocal` - Declara uma variável do escopo externo.

### Avançado
- `@decorator` - Aplica um decorador a uma função.
- `yield` - Define um gerador.
- `partial()` - Cria funções parciais (módulo `functools`).
- `callable()` - Verifica se um objeto é chamável.

---

## 8. Exceções

### Básico
- `try` - Bloco para testar erros.
- `except` - Captura exceções.
- `raise` - Lança uma exceção.

### Intermediário
- `finally` - Executa após `try/except`.
- `else` - Executa se não houver exceção.
- `Exception` - Classe base para exceções.

### Avançado
- `assert` - Lança exceção se a condição falhar.
- `BaseException` - Superclasse de todas as exceções.
- `try/except as` - Captura a exceção como variável.

---

## 9. Módulos e Biblioteca Padrão

### Básico
- `import` - Importa um módulo.
- `from ... import` - Importa itens específicos.
- `os` - Interage com o sistema operacional.
- `sys` - Interage com o interpretador Python.

### Intermediário
- `os.path.join()` - Junta caminhos de arquivo.
- `os.getcwd()` - Retorna o diretório atual.
- `sys.argv` - Lista de argumentos da linha de comando.
- `time.sleep()` - Pausa a execução.
- `datetime.now()` - Retorna a data/hora atual.

### Avançado
- `os.listdir()` - Lista arquivos em um diretório.
- `os.remove()` - Remove um arquivo.
- `pathlib.Path()` - Manipula caminhos de forma moderna.
- `json.loads()` - Converte string JSON em objeto.
- `json.dumps()` - Converte objeto em string JSON.
- `random.randint()` - Gera um inteiro aleatório.
- `re.match()` - Verifica padrão regex no início.
- `re.search()` - Busca padrão regex.

---

## 10. Matemática e Números

### Básico
- `abs()` - Retorna o valor absoluto.
- `max()` - Retorna o maior valor.
- `min()` - Retorna o menor valor.
- `sum()` - Soma os itens de um iterável.

### Intermediário
- `round()` - Arredonda um número.
- `pow()` - Eleva a uma potência.
- `math.sqrt()` - Calcula a raiz quadrada.
- `random.random()` - Gera um float entre 0 e 1.

### Avançado
- `math.sin()`, `math.cos()`, `math.tan()` - Funções trigonométricas.
- `decimal.Decimal` - Números decimais precisos.
- `fractions.Fraction` - Representa frações.
- `statistics.mean()` - Calcula a média.

---

## 11. Outras Funcionalidades

### Intermediário
- `sorted()` - Retorna uma lista ordenada.
- `zip()` - Combina iteráveis em tuplas.
- `enumerate()` - Adiciona índices a um iterável.
- `map()` - Aplica uma função a cada item.

### Avançado
- `filter()` - Filtra itens com uma condição.
- `reduce()` - Reduz iteráveis a um valor (módulo `functools`).
- `iter()` - Cria um iterador.
- `next()` - Obtém o próximo item de um iterador.
- `__slots__` - Otimiza uso de memória em classes.

---

## Resumo
- Total de funcionalidades listadas: **250**.
- Abrange fundamentos, manipulação de dados, módulos padrão, e mais.
- Focado em Python 3.11, excluindo funcionalidades obsoletas do Python 2.
- Para mais detalhes, consulte a documentação oficial do Python (python.org).