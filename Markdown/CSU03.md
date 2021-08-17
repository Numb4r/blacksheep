# Efetuar Registro (CSU03)
Sumario: O Usuário realiza o registro no Sistema.

Ator primário: Usuário

## Fluxo Principal
1. O Usuário requisita o procedimento de registro.
2. O Sistema apresenta um formulário em branco para que os detalhes do Usuário(nome,CPF,e-mail,senha) sejam incluídos.
3. O Usuário fornece os detalhes do registro.
4. O Sistema verifica a validade dos dados. Se forem validos envia um e-mail de confirmação para o Usuário.
5. O Usuário confirma o registro pelo e-mail e o caso de uso termina.

### Fluxo Exceção (4): Usuário ja existente.
- a. O Sistema informa que o Usuário ja existe.
- b. O Usuário escolhe entre retornar para o passo 2 ou terminar o caso.
  
### Fluxo Exceção (4): Senha invalida
- a. O Sistema informa que a senha é invalida.
- b. O Usuário escolhe entre retornar para o passo 2 ou terminar o caso.

### Fluxo Exceção (4): CPF invalido
- a. O Sistema informa que o CPF é invalido.
- b. O Usuário escolhe entre retornar para o passo 2 ou terminar o caso.