# 05 · Formas normais: FND e FNC

- **Literal**: variável ou sua negação (`p`, `¬p`).
- **FND** (Forma Normal Disjuntiva): disjunção de conjunções de literais — "OU de Es".
  Ex.: `(p ∧ q) ∨ (¬p ∧ r)`
- **FNC** (Forma Normal Conjuntiva): conjunção de disjunções de literais — "E de OUs".
  Ex.: `(p ∨ q) ∧ (¬p ∨ r)`

## Algoritmo (3 passos)
1. Eliminar `→` e `↔` usando `p → q ≡ ¬p ∨ q` e `p ↔ q ≡ (p→q) ∧ (q→p)`.
2. Empurrar as negações para os átomos (De Morgan e dupla negação).
3. Distribuir:
   - FND: `A ∧ (B ∨ C) ≡ (A ∧ B) ∨ (A ∧ C)`
   - FNC: `A ∨ (B ∧ C) ≡ (A ∨ B) ∧ (A ∨ C)`

## A partir da tabela-verdade
- **FND**: para cada linha com **V**, monte uma conjunção (var se V, ¬var se F) e una com ∨.
- **FNC**: para cada linha com **F**, monte uma disjunção (var se F, ¬var se V) e una com ∧.

## Exemplo: p → q
- Passo 1: `¬p ∨ q` (já está em FND e em FNC).
