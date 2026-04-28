# 06 · Propriedades dos conectivos

| Propriedade | ∧ | ∨ |
|---|---|---|
| Comutativa | A ∧ B ≡ B ∧ A | A ∨ B ≡ B ∨ A |
| Associativa | (A ∧ B) ∧ C ≡ A ∧ (B ∧ C) | (A ∨ B) ∨ C ≡ A ∨ (B ∨ C) |
| Distributiva | A ∧ (B ∨ C) ≡ (A ∧ B) ∨ (A ∧ C) | A ∨ (B ∧ C) ≡ (A ∨ B) ∧ (A ∨ C) |
| Identidade | A ∧ V ≡ A | A ∨ F ≡ A |
| Absorvente | A ∧ F ≡ F | A ∨ V ≡ V |
| Idempotência | A ∧ A ≡ A | A ∨ A ≡ A |
| Absorção | A ∧ (A ∨ B) ≡ A | A ∨ (A ∧ B) ≡ A |
| De Morgan | ¬(A ∧ B) ≡ ¬A ∨ ¬B | ¬(A ∨ B) ≡ ¬A ∧ ¬B |

## Outras
- Dupla negação: `¬¬A ≡ A`
- Contraposição: `A → B ≡ ¬B → ¬A`
- Prova condicional (exportação): `A ∧ B → C ≡ A → (B → C)`
- Complemento: `A ∨ ¬A ≡ V` e `A ∧ ¬A ≡ F`
