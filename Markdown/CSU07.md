# Gerenciar favoritos (CSU06)
Sumario: O Usuário realiza a gerencia (remoção,consulta) dos favoritos

Ator primário: Usuário.


## Fluxo Principal

1. O Usuário requisita o gerenciamento dos favoritos.
2. O Sistema apresenta a lista de produtos nos favoritos junto das operações(remover,consultar) que é possível realizar com cada item da lista.
3. O Usuário indica a opção que deseja realizar ou opta por finalizar o caso de uso.
4. O Usuário seleciona a operação desejada: Remover, Consultar.
5. Se O Usuário deseja continuar com o gerenciamento, o caso de uso retorna ao passo 2; caso contrario o caso de uso termina.



### Fluxo Alternativo (4): Remover
- a. O Usuário requisita a remoção do produto dos favoritos.
- b. Se o produto pode ser removido, o Sistema realiza a remoção; caso contraio o Sistema reporta o fato.


### Fluxo Alternativo (4): Consultar
- a. O Usuário requisita a consulta de um produto.
- b. O caso de uso termina e começa o caso de uso [CSU05](./CSU05.md)
