# 10 · Deduções

Uma **dedução** é uma sequência de linhas, cada uma sendo premissa, ou obtida de linhas anteriores por regra de inferência ou equivalência, até chegar à conclusão.

## Formato
```
1. p → q        premissa
2. q → r        premissa
3. ¬r           premissa
4. ¬q           MT 2,3
5. ¬p           MT 1,4
```
Conclusão: `¬p`.

## Estratégia
1. Escreva a conclusão desejada e veja quais premissas a contêm.
2. Trabalhe de trás para frente: o que preciso para obter isso?
3. Use equivalências (De Morgan, contraposição, `p → q ≡ ¬p ∨ q`) para ajustar a forma.
4. Simplifique conjunções cedo (`p ∧ q` ⊢ `p`, `q`) para liberar as premissas.

## Exemplo com equivalência
Premissas: `¬(p ∨ q)`, `r → p`. Conclusão: `¬r`.
```
1. ¬(p ∨ q)     premissa
2. r → p        premissa
3. ¬p ∧ ¬q      De Morgan 1
4. ¬p           Simplificação 3
5. ¬r           MT 2,4
```

## Dica
Confira a dedução testando a inferência por tabela-verdade quando tiver poucas variáveis.
