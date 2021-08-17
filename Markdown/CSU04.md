# Manter Estoque (CSU04)
Sumario: O Administrador realiza o CRUD (inclusão,remoção,alteração e consulta) dos dados relacionado ao estoque.

## Fluxo Principal
1. O Administrador requisita a manutenção do estoque.
2. O Sistema apresenta as operações que podem ser realizadas:inclusão de um novo lote,alteração dos dados de um lote,exclusão de um lote e a consulta de um lote.
3. O Administrador indica a opção que deseja realizar ou opta por finalizar o caso de uso.
4. O Administrador seleciona a operação desejada: Inclusão, Exclusão, Alteração ou Consulta.
5. Se o Administrador deseja continuar com a manutenção, o caso de uso retorna ao passo 2; caso contrario, o caso de uso termina.


### Fluxo Alternativo (4): Inclusão
- a. O Administrador requisita a inclusão de um lote.
- b. O Sistema apresenta um formulário para que os detalhes do lote (numero do lote, produto,quantidade) sejam incluídos.
- c. O Administrador fornece os detalhes do novo lote.
- d. O Sistema verifica a validade dos dados. Se os dados forem validos, inclui o novo lote; caso contrario, o sistema reporta o fato, solicita novos dados e repete a verificação.
  

### Fluxo Alternativo (4): Remoção
- a. O Administrador seleciona um lote e pede que o sistema o remova.
- b. Se o lote pode ser removido, o Sistema realiza a remoção; caso contrario, o sistema reporta o fato.

### Fluxo Alternativo (4): Alteração
- a. O Administrador altera um ou mais dos detalhes sobre o lote e requisita a sua atualização.
- b. O sistema verifica a validade dos dados e, se eles forem validos, altera os dados na lista de lotes.

### Fluxo Alternativo (4): Consulta

- a. O Administrador solicita a realização de uma consulta utilizando o/um identificador do lote.
- b. O Sistema apresenta uma lista dos lotes com o resultado da busca pelo identificador, permitindo que o Administrador selecione o lote desejado.
- c. O Administrador seleciona o lote.
- d. O Sistema apresenta os detalhes do lote no formulário de detalhes do lote.
