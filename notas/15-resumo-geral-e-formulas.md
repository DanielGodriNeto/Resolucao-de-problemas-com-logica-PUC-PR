# 15 · Resumo geral: fórmulas essenciais

## Conectivos como ¬, ∧, ∨
- p → q ≡ ¬p ∨ q
- p ↔ q ≡ (¬p ∨ q) ∧ (¬q ∨ p)
- ¬(p → q) ≡ p ∧ ¬q

## Leis
- De Morgan: ¬(p ∧ q) ≡ ¬p ∨ ¬q; ¬(p ∨ q) ≡ ¬p ∧ ¬q
- Dupla negação: ¬¬p ≡ p
- Contraposição: p → q ≡ ¬q → ¬p
- Absorção: p ∧ (p ∨ q) ≡ p; p ∨ (p ∧ q) ≡ p
- Idempotência: p ∧ p ≡ p; p ∨ p ≡ p
- Complemento: p ∨ ¬p ≡ V; p ∧ ¬p ≡ F

## Predicados
- Todo A é B: ∀x (A(x) → B(x))
- Algum A é B: ∃x (A(x) ∧ B(x))
- ¬∀x P(x) ≡ ∃x ¬P(x); ¬∃x P(x) ≡ ∀x ¬P(x)

## Inferência
MP, MT, SD, SH, Adição, Simplificação, Conjunção, Dilemas (construtivo e destrutivo).

## Ligação com programação
Condições de `if`/`while`, filtros de consulta e circuitos digitais são fórmulas proposicionais; simplificá-las reduz bugs e custo.
