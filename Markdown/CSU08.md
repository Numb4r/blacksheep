# Pesquisar produto (CSU08)
Sumario: O Usuário usa o campo de pesquisa para encontrar o produto

Ator primário: Usuário

## Fluxo Principal
1. O Usuário requisita uma pesquisa de produtos.
2. O Sistema apresenta um formulário em branco para que os detalhes da pesquisa(item pesquisado,categoria,etiquetas) sejam incluídos.
3. O Usuário fornece os detalhes da pesquisa
4. O Sistema verifica a validade dos dados.
5. O Sistema retorna uma lista de produtos que sao semelhantes aos detalhes fornecidos para a pesquisa.
6. Se o Usuário deseja continuar a pesquisa o caso de uso retorna ao passo 2. Caso o usuário deseja consultar um produto, o caso de uso acabada e começa o caso de uso [CSU05](./CSU05.md). Caso contrario o caso de uso acaba.