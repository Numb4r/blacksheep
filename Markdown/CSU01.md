# Manter Usuário
Sumario: Administrador realiza o CRUD (inclusão,remoção,alteração e consulta) dos 
dados relacionado aos usuários.

Ator primário: Administrador.

## Fluxo Principal
1. O Administrador requisita a manutenção dos usuários.
2. O Sistema apresenta as operações que podem ser realizadas: inclusão de um novo Usuário,alteração dos dados de um Usuário, exclusão de um Usuário e a consulta de um Usuário.
3. O Administrador indica a opção que deseja realizar ou opta por finalizar o caso de uso.
4. O Administrador seleciona a operação desejada: Inclusão, Exclusão, Alteração ou Consulta.
5. Se o Administrador deseja continuar com a manutenção, o caso de uso retorna ao passo 2; caso contrario, o caso de uso termina.


## Fluxo Alternativo (4): Inclusão
- a. O Administrador requisita a inclusão de um Usuário.
- b. O sistema apresenta um formulário para que os detalhes do Usuário (nome,CPF,e-mail,senha) sejam incluídos.
- c.O Administrador fornece os detalhes do novo Usuário.
- d. O Sistema verifica a validade dos dados. Se os dados forem validos, inclui o novo Usuário; caso contrario, o sistema reporta o fato, solicita novos dados e repete a verificação.
  

## Fluxo Alternativo (4): Remoção
- a. O Administrador seleciona um Usuário e pede que o sistema o remova.
- b. Se o Usuário pode ser removido, o Sistema realiza a remoção; caso contrario, o sistema reporta o fato.

## Fluxo Alternativo (4): Alteração
- a. O Administrador altera um ou mais dos detalhes sobre o Usuário e requisita a sua atualização.
- b. O sistema verifica a validade dos dados e, se eles forem validos, altera os dados na lista de usuários.

## Fluxo Alternativo (4): Consulta

- a. O Administrador solicita a realização de uma consulta utilizando o/um identificador do Usuário.
- b. O Sistema apresenta uma lista dos usuários com o resultado da busca pelo(s) identificadores, permitindo que o Administrador selecione o Usuário desejado.
- c. O Administrador seleciona o Usuário.
- d. O sistema apresenta os detalhes do Usuário no formulário de detalhes do Usuário.
