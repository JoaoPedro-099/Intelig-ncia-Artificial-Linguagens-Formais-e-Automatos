# 📚 AULA 1 — LINGUAGENS FORMAIS E GRAMÁTICAS

---

# 📝 ATIVIDADE 1 — PREFIXOS E SUFIXOS

## Considere a palavra:

`ab`

## PERGUNTA

Liste os prefixos e os sufixos da palavra.

## RESPOSTA

### PREFIXOS

Os prefixos são as partes que começam no início da palavra.

```text
{ε, a, ab}

SUFIXOS

Os sufixos são as partes que terminam no final da palavra.

{ε, b, ab}

EXPLICANDO
ε representa a palavra vazia.
a é prefixo porque começa a palavra.
ab é prefixo porque é a palavra inteira.
b é sufixo porque está no final da palavra.
ab também é sufixo porque a palavra inteira pode ser considerada um sufixo.
📝 ATIVIDADE 2 — GRAMÁTICA
Considere:
G = ({S}, {a}, {S → aS | ε}, S)

PERGUNTA

Liste 3 palavras que podem ser geradas por essa gramática.

RESPOSTA

Uma possibilidade é:

ε
a
aa

DERIVAÇÃO

Podemos entender a derivação assim:

S
→ ε


Outra possibilidade:

S
→ aS
→ aaS
→ aaε


Portanto, algumas palavras geradas são:

ε
a
aa


Também poderiam ser geradas outras palavras, por exemplo:

aaa
aaaa
aaaaa
...


Isso acontece porque a regra:

S → aS


pode ser aplicada várias vezes antes de usar:

S → ε

📚 RESUMO PARA PROVA
🔤 ALFABETO

Σ representa o conjunto de símbolos que podem ser usados.

EXEMPLO
Σ = {a, b}


Nesse caso, os símbolos do alfabeto são a e b.

🔤 CADEIA OU PALAVRA

É uma sequência de símbolos que pertencem ao alfabeto.

Por exemplo, considerando:

Σ = {a, b}


A sequência:

ab


é uma palavra válida porque os dois símbolos pertencem ao alfabeto.

⭕ PALAVRA VAZIA

A palavra vazia é representada por:

ε


Ela não possui nenhum símbolo.

Por isso:

|ε| = 0

⭐ Σ*

Σ* representa o conjunto de todas as cadeias finitas que podem ser formadas usando os símbolos de Σ.

Também inclui a palavra vazia.

EXEMPLO

Se:

Σ = {a, b}


Então:

Σ* = {ε, a, b, aa, ab, ba, bb, aaa, aab, ...}

📖 LINGUAGEM

Uma linguagem é um conjunto de cadeias.

Podemos representar por:

L ⊆ Σ*


Isso significa que todas as palavras da linguagem pertencem a Σ*.

🔹 PREFIXO

Prefixo é uma parte da palavra que começa no primeiro símbolo.

Considerando:

ab


Os prefixos são:

{ε, a, ab}

EXEMPLOS
ε é o prefixo vazio.
a é o primeiro símbolo.
ab é a palavra inteira.
🔹 SUFIXO

Sufixo é uma parte da palavra que termina no último símbolo.

Considerando:

ab


Os sufixos são:

{ε, b, ab}

EXEMPLOS
ε é o sufixo vazio.
b está no final da palavra.
ab é a palavra inteira.
🧩 GRAMÁTICA

Uma gramática é usada para definir regras que permitem gerar palavras de uma linguagem.

Um exemplo é:

S → aS | ε


Nesse caso, podemos começar com S e ir aplicando as regras até chegar em uma palavra formada somente por símbolos terminais.

➡️ SÍMBOLO →

Nas gramáticas, o símbolo:

→


indica uma produção ou regra.

Por exemplo:

S → aS


Podemos ler como:

"S produz aS"

ou:

"S pode ser substituído por aS".

🔀 SÍMBOLO |

Nas regras de produção, o símbolo:

|


significa "ou".

Por exemplo:

S → aS | ε


Significa que existem duas possibilidades:

S → aS


OU

S → ε

⚠️ OBSERVAÇÃO SOBRE O SÍMBOLO →

Em outros assuntos da matemática e da lógica, o símbolo:

→


pode ter outros significados.

Por exemplo, em lógica pode representar:

"implica"

ou:

"se... então".

Mas, quando estamos trabalhando com gramáticas, normalmente estamos usando → para indicar uma regra de produção.

📌 RESUMO RÁPIDO
Conceito	Significado
Σ	Alfabeto
ε	Palavra vazia
Σ*	Todas as palavras possíveis, incluindo ε
L	Linguagem
L ⊆ Σ*	A linguagem é formada por palavras de Σ*
Prefixo	Parte inicial da palavra
Sufixo	Parte final da palavra
G	Gramática
S	Símbolo inicial
→	Regra de produção
`	`
S → aS	Produção que substitui S por aS
S → ε	Produção que gera a palavra vazia
🎯 EXEMPLO FINAL

Considere:

Σ = {a, b}


Uma palavra possível é:

ab


Se:

L = {ab}


Então:

ab ∈ L


Os prefixos de ab são:

{ε, a, ab}


Os sufixos de ab são:

{ε, b, ab}


E:

|ab| = 2


Portanto:

Σ representa o alfabeto.
ab é uma palavra.
L é uma linguagem.
ε é a palavra vazia.
Σ* representa todas as palavras possíveis.
Prefixos começam no início da palavra.
Sufixos terminam no final da palavra.
Gramáticas possuem regras de produção para gerar palavras.
:::
