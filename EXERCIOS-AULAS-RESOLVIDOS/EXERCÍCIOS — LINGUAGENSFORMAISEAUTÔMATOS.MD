# 📚 EXERCÍCIOS — LINGUAGENS FORMAIS E AUTÔMATOS

---

# 📝 EXERCÍCIO 1 — ALFABETO

## Considere:

Σ = {a, b, c}

## QUESTÕES

1. Quantos símbolos existem no alfabeto?
2. Quais são os símbolos?
3. O símbolo "a" pertence ao alfabeto?
4. O símbolo "d" pertence ao alfabeto?
5. Escreva uma palavra formada por símbolos desse alfabeto.

## RESPOSTAS

1. Existem 3 símbolos no alfabeto.

2. Os símbolos são a, b e c.

3. Sim, porque o símbolo a está dentro de Σ.

4. Não, porque o símbolo d não está em Σ.

5. Um exemplo de palavra é:

- a
- aa
- ab
- b
- bb
- ba
- abc

---

# 📝 EXERCÍCIO 2 — PALAVRAS SOBRE UM ALFABETO

## Considere:

Σ = {0, 1}

## QUESTÕES

Classifique cada sequência como PALAVRA VÁLIDA ou NÃO VÁLIDA.

1. 0101
2. 00110
3. 012
4. 111
5. 10a

## RESPOSTAS

### 1. 0101 — VÁLIDA

É válida porque todos os símbolos são 0 ou 1.

### 2. 00110 — VÁLIDA

Também é válida porque só possui símbolos do alfabeto.

### 3. 012 — NÃO VÁLIDA

Não é válida porque o símbolo 2 não pertence ao alfabeto.

### 4. 111 — VÁLIDA

É válida porque todos os símbolos pertencem a Σ.

### 5. 10a — NÃO VÁLIDA

Não é válida porque o símbolo a não pertence a Σ.

---

# 📝 EXERCÍCIO 3 — PERTINÊNCIA DE SÍMBOLOS E PALAVRAS

## Considere:

Σ = {0, 1}

## QUESTÕES

Determine se as afirmações são VERDADEIRAS ou FALSAS.

1. 0 pertence a Σ
2. 1 pertence a Σ
3. 01 pertence a Σ
4. 01 pertence a Σ*
5. 2 pertence a Σ
6. 101 pertence a Σ*

## RESPOSTAS

### 1. 0 ∈ Σ — VERDADEIRO

O 0 está no alfabeto.

### 2. 1 ∈ Σ — VERDADEIRO

O 1 também está no alfabeto.

### 3. 01 ∈ Σ — FALSO

01 não pertence diretamente a Σ, porque 01 é uma sequência com dois símbolos.

Σ contém apenas os símbolos 0 e 1 individualmente.

### 4. 01 ∈ Σ* — VERDADEIRO

01 pertence a Σ*, pois é uma palavra formada apenas por símbolos do alfabeto.

### 5. 2 ∈ Σ — FALSO

O símbolo 2 não faz parte de Σ.

### 6. 101 ∈ Σ* — VERDADEIRO

101 é uma palavra formada somente por 0 e 1, então pertence a Σ*.

---

# 📝 EXERCÍCIO 4 — LINGUAGEM

## Considere:

L = {0, 01, 011, 0111}

## QUESTÕES

Determine se cada palavra pertence à linguagem.

1. 0 pertence a L
2. 01 pertence a L
3. 0111 pertence a L
4. 10 pertence a L
5. 111 pertence a L
6. 011 pertence a L

## RESPOSTAS

### 1. 0 ∈ L — SIM

0 aparece na linguagem L.

### 2. 01 ∈ L — SIM

01 aparece na linguagem L.

### 3. 0111 ∈ L — SIM

0111 aparece na linguagem L.

### 4. 10 ∈ L — NÃO

10 não aparece na linguagem L.

### 5. 111 ∈ L — NÃO

111 não aparece na linguagem L.

### 6. 011 ∈ L — SIM

011 aparece na linguagem L.

---

# 📝 EXERCÍCIO 5 — DESCREVENDO UMA LINGUAGEM POR PADRÃO

## Considere:

L = {bⁿ | n ≥ 1}

## QUESTÕES

1. Escreva as cinco primeiras palavras.
2. Explique o significado de bⁿ.
3. A palavra "bbbbbb" pertence à linguagem?
4. A palavra vazia (ε) pertence à linguagem?

## RESPOSTAS

### 1. Cinco primeiras palavras

- b
- bb
- bbb
- bbbb
- bbbbb

### 2. Significado de bⁿ

bⁿ significa que temos n símbolos b juntos.

Por exemplo:

- b¹ = b
- b² = bb
- b³ = bbb
- b⁴ = bbbb

### 3. "bbbbbb" pertence à linguagem?

SIM.

A palavra "bbbbbb" possui 6 letras b.

Então ela pode ser representada por b⁶.

Como 6 ≥ 1, ela pertence à linguagem.

### 4. A palavra vazia (ε) pertence à linguagem?

NÃO.

A palavra vazia possui 0 símbolos.

Como a condição é n ≥ 1, ε não pertence a essa linguagem.

---

# 📝 EXERCÍCIO 6 — LINGUAGEM VAZIA E PALAVRA VAZIA

## Explique a diferença entre:

### A) L = ∅

Nesse caso, a linguagem não possui nenhuma palavra.

### B) L = {ε}

Nesse caso, a linguagem possui uma palavra, que é justamente a palavra vazia.

## RESPOSTAS

### 1. Qual delas possui uma palavra?

L = {ε} possui uma palavra.

### 2. Qual delas não possui nenhuma palavra?

L = ∅ não possui nenhuma palavra.

### 3. Qual é o comprimento da palavra ε?

|ε| = 0

Então, conjunto vazio e {ε} são coisas diferentes.

---

# 📝 EXERCÍCIO 7 — ESTRUTURA DE UMA GRAMÁTICA

## Considere:

G = ({S, A}, {0, 1}, P, S)

Com:

P = {S → 0A, A → 1}

## QUESTÕES

Identifique:

1. O conjunto de variáveis.
2. O conjunto de terminais.
3. O conjunto de produções.
4. O símbolo inicial.
5. Qual palavra pode ser gerada por essa gramática?

## RESPOSTAS

### 1. Conjunto de variáveis

V = {S, A}

### 2. Conjunto de terminais

T = {0, 1}

### 3. Conjunto de produções

P = {S → 0A, A → 1}

### 4. Símbolo inicial

S

### 5. Palavra gerada

A palavra gerada é 01.

### Derivação

S  
→ 0A  
→ 01

---

# 📝 EXERCÍCIO 8 — COMO APLICAR UMA PRODUÇÃO

## Considere:

S → 0S

## QUESTÕES

Começando com S:

1. Aplique a regra uma vez.
2. Aplique a regra duas vezes.
3. Aplique a regra três vezes.
4. Escreva a sequência completa de derivação.

## RESPOSTAS

### 1. Uma vez

S  
→ 0S

### 2. Duas vezes

S  
→ 0S  
→ 00S

### 3. Três vezes

S  
→ 0S  
→ 00S  
→ 000S

### 4. Sequência completa

S  
→ 0S  
→ 00S  
→ 000S

A derivação ainda não terminou porque o símbolo S continua aparecendo.

---

# 📝 EXERCÍCIO 9 — DERIVAÇÃO COMPLETA DE UMA PALAVRA

## Utilizando a gramática:

S → aS  
S → b

## Gere:

aaab

## RESPOSTA

Começando pelo S:

S  
→ aS  
→ aaS  
→ aaaS  
→ aaab

Portanto, a palavra aaab pode ser gerada por essa gramática.

---

# 📝 EXERCÍCIO 10 — IDENTIFICANDO PALAVRAS GERADAS POR UMA GRAMÁTICA

## Considere:

S → 0S  
S → 1

## QUESTÕES

Determine se cada palavra pode ser gerada:

1. 1
2. 01
3. 001
4. 0001
5. 101
6. 1001

Para as palavras que podem ser geradas, apresente a derivação completa.

## RESPOSTAS

### 1. 1 — PODE SER GERADA

S  
→ 1

### 2. 01 — PODE SER GERADA

S  
→ 0S  
→ 01

### 3. 001 — PODE SER GERADA

S  
→ 0S  
→ 00S  
→ 001

### 4. 0001 — PODE SER GERADA

S  
→ 0S  
→ 00S  
→ 000S  
→ 0001

### 5. 101 — NÃO PODE SER GERADA

A gramática pode colocar vários zeros antes do 1, mas quando usamos a regra S → 1, a derivação termina.

Por isso não é possível gerar 101.

### 6. 1001 — NÃO PODE SER GERADA

O padrão dessa gramática é colocar zeros e depois terminar com um único 1.

Alguns exemplos são:

- 1
- 01
- 001
- 0001

Como 1001 possui símbolos depois do primeiro 1, ela não pode ser gerada.

---

# 🏆 DESAFIO FINAL

## Considere:

S → aS  
S → b

## QUESTÕES

1. A palavra "b" pode ser gerada?
2. A palavra "ab" pode ser gerada?
3. A palavra "aab" pode ser gerada?
4. A palavra "aaab" pode ser gerada?
5. A palavra "aba" pode ser gerada?
6. Escreva a derivação completa de "aaaab".
7. Descreva o padrão das palavras geradas por essa gramática.

## RESPOSTAS

### 1. A palavra "b" pode ser gerada?

SIM.

S  
→ b

### 2. A palavra "ab" pode ser gerada?

SIM.

S  
→ aS  
→ ab

### 3. A palavra "aab" pode ser gerada?

SIM.

S  
→ aS  
→ aaS  
→ aab

### 4. A palavra "aaab" pode ser gerada?

SIM.

S  
→ aS  
→ aaS  
→ aaaS  
→ aaab

### 5. A palavra "aba" pode ser gerada?

NÃO.

A regra S → b é usada para finalizar a palavra.

Depois disso não existe outra regra para continuar a derivação.

Por isso não é possível gerar "aba".

### 6. Derivação completa de "aaaab"

S  
→ aS  
→ aaS  
→ aaaS  
→ aaaaS  
→ aaaab

### 7. Padrão das palavras geradas

O padrão é formado por zero ou mais letras "a", seguidas de uma letra "b".

Alguns exemplos:

- b
- ab
- aab
- aaab
- aaaab
- aaaaab

Então podemos representar o padrão por:

aⁿb, com n ≥ 0

---

# 📖 RESUMO DOS CONCEITOS

## Σ — ALFABETO

É o alfabeto, ou seja, o conjunto de símbolos que podem ser usados.

## SÍMBOLO

É um elemento individual do alfabeto.

## PALAVRA

É uma sequência de símbolos.

## LINGUAGEM

É um conjunto de palavras.

## Σ*

É o conjunto de todas as palavras que podem ser formadas usando os símbolos do alfabeto, incluindo ε.

## ε — PALAVRA VAZIA

É a palavra vazia, que possui comprimento 0.

## CONJUNTO VAZIO

É um conjunto que não possui nenhum elemento.

## w ∈ L

Significa que a palavra w faz parte da linguagem L.

## w ∉ L

Significa que a palavra w não faz parte da linguagem L.

## G — GRAMÁTICA

Representa uma gramática.

## V — VARIÁVEIS

É o conjunto de variáveis ou não terminais.

## T — TERMINAIS

É o conjunto de terminais.

## P — PRODUÇÕES

É o conjunto de produções ou regras.

## S — SÍMBOLO INICIAL

É o símbolo inicial da gramática.

## → — REGRA DE PRODUÇÃO

Representa uma regra de produção.

## DERIVAÇÃO

É o processo de aplicar as regras da gramática até chegar em uma palavra formada somente por terminais.

---

# 📌 RESUMO VISUAL

ALFABETO  
↓  
SÍMBOLOS  
↓  
PALAVRAS  
↓  
LINGUAGENS  
↓  
GRAMÁTICAS  
↓  
DERIVAÇÕES
