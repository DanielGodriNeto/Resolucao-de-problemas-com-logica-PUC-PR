---
tags: [logica, estudo]
---

# 02 · Tabelas-verdade

## Tabelas básicas

| p | q | ¬p | p ∧ q | p ∨ q | p → q | p ↔ q |
|---|---|----|-------|-------|-------|-------|
| V | V | F | V | V | V | V |
| V | F | F | F | V | F | F |
| F | V | V | F | V | V | F |
| F | F | V | F | F | V | V |

## Quantas linhas?
Com `n` proposições simples, a tabela tem **2ⁿ** linhas (2 vars → 4, 3 vars → 8).

## Passo a passo
1. Liste as variáveis e todas as combinações de V/F (alterne V/F na última coluna, de 2 em 2, de 4 em 4…).
2. Resolva as subfórmulas de dentro para fora (parênteses primeiro).
3. Ordem de precedência: `¬`, depois `∧`, depois `∨`, depois `→`, por fim `↔`.
4. A última coluna é o resultado da fórmula.

## Exemplo: (p ∧ q) → p

| p | q | p ∧ q | (p ∧ q) → p |
|---|---|-------|-------------|
| V | V | V | V |
| V | F | F | V |
| F | V | F | V |
| F | F | F | V |

Todas as linhas V → a fórmula é uma **tautologia** (próxima nota).

## Atenção
- A condicional só é falsa em **V → F**. "Falso implica qualquer coisa" é verdadeiro.
- A disjunção aqui é **inclusiva** (vale V se as duas forem V).

<!-- nav:start -->

---

← [01 · Proposições e conectivos](01-proposicoes-e-conectivos.md) · [Mapa](../00%20-%20Mapa.md) · [03 · Tautologia, contradição e contingência](03-tautologia-contradicao-contingencia.md) →

**Veja também:** [04 · Equivalência lógica e Leis de De Morgan](04-equivalencia-e-de-morgan.md)

<!-- nav:end -->
