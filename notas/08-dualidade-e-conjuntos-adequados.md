# 08 · Dualidade e conjuntos adequados de conectivos

## Dual
Em uma fórmula só com `{¬, ∧, ∨}`, o **dual** A* troca `∧` por `∨` e `∨` por `∧`.

**Princípio da dualidade**: se A ≡ B, então A* ≡ B*.

Exemplo: `p ∧ (p ∨ q) ≡ p` ⇒ `p ∨ (p ∧ q) ≡ p`.

## Conjunto adequado
Conjunto de conectivos com o qual **qualquer** fórmula pode ser escrita.

Adequados: `{¬, ∧, ∨, →, ↔}`, `{¬, ∧, ∨}`, `{¬, ∧}`, `{¬, ∨}`, `{¬, →}`.

## Conectivos únicos
- **NAND** (negação conjunta, ↑): `p ↑ q ≡ ¬(p ∧ q)`
- **NOR** (negação disjunta, ↓): `p ↓ q ≡ ¬(p ∨ q)`

Cada um sozinho é adequado.

### Com NAND
- ¬p ≡ p ↑ p
- p ∧ q ≡ (p ↑ q) ↑ (p ↑ q)
- p ∨ q ≡ (p ↑ p) ↑ (q ↑ q)

### Com NOR
- ¬p ≡ p ↓ p
- p ∨ q ≡ (p ↓ q) ↓ (p ↓ q)
- p ∧ q ≡ (p ↓ p) ↓ (q ↓ q)

Aplicação: circuitos digitais podem ser montados só com portas NAND.
