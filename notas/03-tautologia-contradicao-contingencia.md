# 03 · Tautologia, contradição e contingência

Classificação **semântica**: depende dos valores de verdade, não só dos símbolos.

| Classe | Definição | Exemplo |
|---|---|---|
| **Tautologia** | V em todas as interpretações | p ∨ ¬p |
| **Contradição** (insatisfatível) | F em todas as interpretações | p ∧ ¬p |
| **Contingência** | V em algumas e F em outras | p → q |
| **Satisfatível** | V em pelo menos uma interpretação | tautologias e contingências |

## Relações importantes
- Toda tautologia é satisfatível; nem toda satisfatível é tautologia.
- `A` é contradição ⇔ `¬A` é tautologia.
- **Insatisfatível = contradição**: são duas formas de dizer a mesma coisa.

## Como identificar na tabela-verdade
- Só V na última coluna → tautologia.
- Só F → contradição.
- V e F → contingência.

## Na prática (programação)
- Um `if` cuja condição é contradição **nunca executa** (código morto).
- Uma condição que é tautologia **sempre executa** (o `if` é inútil).
- Regra de negócio como "cliente aprovado **e** reprovado" é contradição: requisito impossível.

## Princípio do terceiro excluído
`p ∨ ¬p` é sempre V na lógica clássica: uma proposição é verdadeira ou falsa.
