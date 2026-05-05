# 07 · Simplificação de sentenças

## Por quê?
Condições de `if`/`while` mal construídas são fonte de bug. Simplificar reduz erro, carga mental e operações.

## Estratégia
1. Reduza tudo a `{¬, ∧, ∨}` (elimine `→` e `↔`).
2. Aplique De Morgan para deixar as negações nos átomos.
3. Procure pares `p ∧ ¬p` (→ F) e `p ∨ ¬p` (→ V).
4. Use identidade, absorvente, idempotência e absorção.

## Exemplo da aula (código)
```
if (!(A && B) || (A && !B)) { ... }
```
- ¬(A ∧ B) ∨ (A ∧ ¬B)
- = (¬A ∨ ¬B) ∨ (A ∧ ¬B)
- = ¬A ∨ ¬B ∨ (A ∧ ¬B)
- = ¬A ∨ ¬B (absorção: ¬B ∨ (A ∧ ¬B) ≡ ¬B)

Logo, equivale a `if (!A || !B)`.

## Conferindo
Faça a tabela-verdade das duas formas: se todas as linhas coincidem, são equivalentes.
