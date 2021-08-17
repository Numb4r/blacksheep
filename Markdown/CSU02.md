## Manter Produtos (CSU02)
Sumario: Administrador realiza a gerencia (inclusão, remoção, alteração, consulta e promoção) dos produtos.

Ator primário: Administrador

## Fluxo Principal
1. O Administrador requisita o gerenciamento dos produtos.
2. O Sistema apresenta as operações que podem ser realizados: a inclusão de um novo produto, a alteração dos dados de um produto, a remoção de um produto, a consulta de um produto e criar a promoção de um produto.
3. O Administrador indica a opção que deseja realizar ou opta por finalizar o caso de uso.
4. O Administrador seleciona a operação desejada: Inclusão, Exclusão, Alteração, Consulta, Realizar Promoção.
5. Se o Administrador deseja continuar com o gerenciamento, o caso de uso retorna ao passo 2; caso contrario, o caso de uso termina.

### Fluxo Alternativo (4): Inclusão

- a. O Administrador requisita a inclusão de um novo produto.
- b. O Sistema apresenta um formulário em branco para que os detalhes do produto (nome,categoria,etiquetas,descrição,preço) sejam incluídos.
- c. O Administrador fornece os detalhes do novo produto.
- d. O Sistema verifica a validade dos dados. Se os dados forem validos, inclui o  novo produto; caso contrario, o Sistema reporta o fato, solicita novos dados e repete a verificação.

### Fluxo Alternativo (4): Remoção
- a. O Administrador seleciona um produto e pede que o Sistema o remova.
- b. Se o produto pode ser removido, o Sistema realiza a remoção; caso contrario, o Sistema reporta o fato.

### Fluxo Alternativo (4): Alteração
- a. O Administrador altera um ou mais dos detalhes sobre o produto e requisita a sua atualização.
- b. O Sistema verifica a validade dos dados e, se eles forem validos, altera os dados na lista de produtos.

### Fluxo Alternativo (4): Consulta
- a. O Administrador solicita a realização de uma consulta utilizando o identificador do produto.
- b. O Sistema apresenta uma lista dos produtos com o resultado da busca pelo identificador, permitindo que o Administrador selecione o produto desejado.
- c. O Administrador seleciona o produto.
- d. O Sistema apresenta os detalhes do produto no formulário de detalhes do produto.

### Fluxo Alternativo (4): Realizar Promoção
- a. O Administrador solicita a realização de uma promoção.
- b. O Sistema apresenta um formulário em branco para que os detalhes do produto (identificador do produto,desconto,período) sejam incluídos.
- c. O Administrador fornece os detalhes da promoção.
- d. O Sistema verifica a validade dos dados. Se os dados forem validos, cria uma promoção; caso contrario, o Sistema reporta o fato, solicita novos dados e repete a verificação.