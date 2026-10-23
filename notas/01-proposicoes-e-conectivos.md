---
tags: [logica, estudo]
---

# 01 · Proposições e conectivos

## Proposição
Sentença declarativa que pode ser **verdadeira (V)** ou **falsa (F)**, nunca as duas.
Perguntas, ordens e exclamações **não** são proposições.

- "5 é maior que 3" → proposição (V)
- "Que horas são?" → não é proposição

## Proposição simples × composta
- **Simples**: não pode ser dividida em outras proposições. Representada por letras: `p`, `q`, `r`.
- **Composta**: formada por simples ligadas por **conectivos**.

## Conectivos

| Nome | Símbolo | Leitura | Verdadeira quando |
|---|---|---|---|
| Negação | ¬p | "não p" | p é falsa |
| Conjunção | p ∧ q | "p e q" | as duas são V |
| Disjunção | p ∨ q | "p ou q" | pelo menos uma é V |
| Condicional | p → q | "se p, então q" | não ocorre p=V e q=F |
| Bicondicional | p ↔ q | "p se, e somente se, q" | p e q têm o mesmo valor |

## Traduzindo da linguagem natural
Exemplo (Lista 1): E = "João estuda", A = "o exame se aproxima", O = "João é obrigado a estudar".

- "Se o exame se aproxima, João estuda" → `A → E`
- "João estuda ou é obrigado a estudar" → `E ∨ O`
- "João não estuda" → `¬E`

## Dicas
- "mas", "porém", "embora" costumam ser conjunção (∧).
- "somente se" indica a direção da condicional: "p somente se q" = `p → q`.
- "a menos que" costuma virar `¬p → q`.

<!-- nav:start -->

---

[Mapa](../00%20-%20Mapa.md) · [02 · Tabelas-verdade](02-tabelas-verdade.md) →

<!-- nav:end -->
