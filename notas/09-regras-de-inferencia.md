# 09 · Regras de inferência

Uma **inferência** tem premissas e uma conclusão; é válida quando a conclusão é V sempre que todas as premissas forem V.

| Regra | Premissas | Conclusão |
|---|---|---|
| Adição | p | p ∨ q |
| Simplificação | p ∧ q | p |
| Conjunção | p, q | p ∧ q |
| Modus Ponens (MP) | p → q, p | q |
| Modus Tollens (MT) | p → q, ¬q | ¬p |
| Silogismo Disjuntivo (SD) | p ∨ q, ¬p | q |
| Silogismo Hipotético (SH) | p → q, q → r | p → r |
| Dilema Construtivo | p → q, r → s, p ∨ r | q ∨ s |
| Dilema Destrutivo | p → q, r → s, ¬q ∨ ¬s | ¬p ∨ ¬r |

## Exemplos
- "Se chove, a rua molha. Choveu." ⇒ a rua molha (MP).
- "Se chove, a rua molha. A rua não molhou." ⇒ não choveu (MT).
- "Estudo ou trabalho. Não estudo." ⇒ trabalho (SD).

## Erros comuns (falácias)
- Afirmar o consequente: p → q, q ⊢ p ✗
- Negar o antecedente: p → q, ¬p ⊢ ¬q ✗

## Como identificar a regra
Olhe a forma das premissas: condicional + antecedente → MP; condicional + negação do consequente → MT; duas condicionais encadeadas → SH.
