# 12 · Tradução e negação de quantificadores

## Tradução (4 formas básicas)

| Frase | Fórmula |
|---|---|
| Todo A é B | ∀x (A(x) → B(x)) |
| Algum A é B | ∃x (A(x) ∧ B(x)) |
| Nenhum A é B | ∀x (A(x) → ¬B(x)) |
| Algum A não é B | ∃x (A(x) ∧ ¬B(x)) |

## Negação (De Morgan para quantificadores)
- ¬∀x P(x) ≡ ∃x ¬P(x)
- ¬∃x P(x) ≡ ∀x ¬P(x)

Ao passar a negação para dentro, **troque o quantificador**.

### Exemplo
"Nem todo aluno estuda" = ¬∀x (A(x) → E(x))
≡ ∃x ¬(A(x) → E(x))
≡ ∃x (A(x) ∧ ¬E(x)) → "existe aluno que não estuda".

## Ordem importa
- `∀x ∃y Ama(x, y)`: todo mundo ama alguém (pode ser alguém diferente para cada x).
- `∃y ∀x Ama(x, y)`: existe alguém que é amado por todos.

São fórmulas diferentes; trocar a ordem de quantificadores de tipos diferentes muda o sentido.
