# 04 · Equivalência lógica e Leis de De Morgan

## Equivalência
`A ≡ B` quando as duas fórmulas têm **a mesma tabela-verdade**
(ou seja, `A ↔ B` é tautologia).

## Leis de De Morgan
- ¬(p ∧ q) ≡ ¬p ∨ ¬q
- ¬(p ∨ q) ≡ ¬p ∧ ¬q

Estendidas: ¬(A₁ ∧ … ∧ Aₙ) ≡ ¬A₁ ∨ … ∨ ¬Aₙ (e vice-versa).

## Equivalências entre conectivos
1. p → q ≡ ¬p ∨ q
2. p ∨ q ≡ ¬(¬p ∧ ¬q)
3. p ↔ q ≡ (p → q) ∧ (q → p)
4. p → q ≡ ¬q → ¬p (contraposição)
5. p ↔ q ≡ (p ∧ q) ∨ (¬p ∧ ¬q)

## Regras de substituição
1. Se A é tautologia, trocar suas variáveis por fórmulas quaisquer mantém a tautologia.
2. Trocar uma subfórmula por outra **equivalente** não altera o valor da fórmula inteira.

## Exemplo em código
```
!(a && b)   ≡   !a || !b
!(x > 3 || y < 2)   ≡   x <= 3 && y >= 2
```
