# Visualizar produto (CSU05)
Sumario: Usuário  visualiza um produto.

Ator primário: Usuário.

## Fluxo Principal
1. O Usuário escolhe um produto na lista de produtos.
2. O Sistema apresenta as informações do produto junto as operações que podem ser realizadas: adicionar o produto aos favoritos e colocar o produto no carrinho de compras.
3. O Usuário indica a opção que deseja realizar ou opta por finalizar o caso de uso.
4. O Sistema seleciona a operação desejada: Favoritar, Comprar.
5. Se o Usuário desejar continuar a visualizar o produto, o caso retorna ao passo 2; caso contrario, o caso de uso termina

### Fluxo Alternativo (4): Favoritar
- a. O Usuário requisita favoritar o produto.
- b. O Sistema verifica a validade da operação. Se o produto não esta na lista de favoritos do Usuário ele é favoritado, caso contrario ele é removido.

### Fluxo Alternativo (4): Comprar
- a. O Usuário requisita a compra do produto.
- b. O Sistema verifica a validade da operação. Caso o produto não esteja presente no carrinho de comprar do Usuário ele é inserido, caso contrario o caso de uso termina e o caso de uso [CSU06](./CSU06.md) começa.