# Gerenciar carrinho de compras (CSU06)
Sumario: O Usuário realiza a gerencia (alteração,remoção,consulta) do carrinho de compras.

Ator primário: Usuário.


## Fluxo Principal

1. O Usuário requisita o gerenciamento do carrinho de compras.
2. O Sistema apresenta a lista de produtos no carrinho de compras junto das operações(alterar quantidade,remover,consultar) que é possível realizar com cada item da lista.
3. O Usuário indica a opção que deseja realizar ou opta por finalizar o caso de uso.
4. O Usuário seleciona a operação desejada: Alterar, Remover, Consultar.
5. Se O Usuário deseja continuar com o gerenciamento, o caso de uso retorna ao passo 2; caso contrario o caso de uso termina.


### Fluxo Alternativo (4): Alterar
- a. O Usuário requisita mudar a quantidade do produto no carrinho.
- b. O Sistema verifica a validade dessa operação. Caso não seja valida o Sistema ira emitir uma mensagem de erro. O caso de de uso retorna ao passo 2.

### Fluxo Alternativo (4): Remover
- a. O Usuário requisita a remoção do produto do carrinho de compras.
- b. Se o produto pode ser removido, o Sistema realiza a remoção; caso contraio o sistema reporta o fato.


### Fluxo Alternativo (4): Consultar
- a. O Usuário requisita a consulta de um produto.
- b. O caso de uso termina e começa o caso de uso [CSU05](./CSU05.md)
