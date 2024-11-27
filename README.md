
# Relatório De Complexidade

## Prefacio
O objetivo é comparar sobre as estruturas
de dados (Tabela Hash, Pilha e Fila) 
nos os tempos de execução observados
e relacioná-los com suas complexidades 
teóricas, incluindo o uso de `posicoes`
para recuperar elementos em índices
específicos.

---

## Complexidade Teórica do Bubble Sort

### **Bubble Sort**
- **Complexidade de tempo**: O(n²)
    - Para cada elemento na lista, percorremos o restante dos elementos para realizar comparações e trocas. Isso resulta em um loop aninhado.
    - Exemplo: para `n = 5`, o algoritmo executará 4 + 3 + 2 + 1 comparações, resultando em uma complexidade quadrática.

- **Explicação**:
    - Para uma lista de tamanho `n`, o algoritmo realiza comparações em pares, diminuindo uma unidade no tamanho a cada iteração.
    - O loop interno e externo combinam-se, gerando `n(n-1)/2` iterações no pior caso.

---
 
