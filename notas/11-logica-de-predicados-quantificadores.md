# 11 · Lógica de predicados: quantificadores

A lógica proposicional não enxerga "todos" nem "existe". A lógica de predicados acrescenta:

- **Predicados**: propriedades ou relações, `P(x)`, `Gosta(x, y)`.
- **Constantes**, **variáveis** e **domínio** (o conjunto sobre o qual `x` varia).
- **Quantificador universal** `∀x P(x)`: "para todo x, P(x)".
- **Quantificador existencial** `∃x P(x)`: "existe x tal que P(x)".

## Leitura
- ∀x (Aluno(x) → Estuda(x)): "todo aluno estuda".
- ∃x (Aluno(x) ∧ Estuda(x)): "algum aluno estuda".

## Armadilha clássica
- `∀` combina com `→`.
- `∃` combina com `∧`.

`∀x (Aluno(x) ∧ Estuda(x))` diz que **tudo** é aluno e estuda (quase nunca é o que se quer).

## Variáveis livres e ligadas
Em `∀x P(x, y)`, `x` está **ligada** pelo quantificador e `y` está **livre**. Uma fórmula sem variáveis livres é uma **sentença**.

## Domínio finito
Sobre {a, b, c}: `∀x P(x) ≡ P(a) ∧ P(b) ∧ P(c)` e `∃x P(x) ≡ P(a) ∨ P(b) ∨ P(c)`.
