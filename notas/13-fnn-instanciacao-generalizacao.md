# 13 · Forma normal prenex, instanciação e generalização

## Forma Normal Prenex (FNN)
Todos os quantificadores ficam **no início** da fórmula, seguidos da parte sem quantificadores:

`Q₁x₁ … Qₙxₙ (matriz)`

Passos:
1. Eliminar `→` e `↔`.
2. Levar as negações para os predicados (trocando ∀ por ∃ e vice-versa).
3. Renomear variáveis ligadas para evitar conflito.
4. Mover os quantificadores para a frente.

## Regras de inferência com quantificadores

| Regra | Forma | Observação |
|---|---|---|
| Instanciação Universal (IU) | ∀x P(x) ⊢ P(c) | c é qualquer constante do domínio |
| Generalização Universal (GU) | P(c) ⊢ ∀x P(x) | c deve ser **arbitrário** |
| Instanciação Existencial (IE) | ∃x P(x) ⊢ P(c) | c é uma constante **nova** |
| Generalização Existencial (GE) | P(c) ⊢ ∃x P(x) | vale para qualquer c |

## Exemplo clássico
1. ∀x (Humano(x) → Mortal(x))
2. Humano(Sócrates)
3. Humano(Sócrates) → Mortal(Sócrates)  (IU 1)
4. Mortal(Sócrates)  (MP 2,3)
