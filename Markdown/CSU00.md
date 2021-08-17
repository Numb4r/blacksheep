# Efetuar Login (CSU00)
Sumario: O Usuário realiza o login no Sistema.

Ator primário: Usuário.

## Fluxo Principal
1. O Usuário requisita o procedimento de login.
2. O Sistema apresenta um formulário em branco para que os detalhes de login (e-mail, senha) sejam incluídos e uma opção de recuperar a senha.
3. O Usuário fornece as credenciais de login.
4. O Sistema confere as credenciais do formulário e aprova o login do usuário.
5. O Usuário é redirecionado para a pagina anterior ao inicio do caso de uso e o caso termina.

### Fluxo Exceção (4): Credenciais invalidas
- O Sistema emite um erro que não foi possível realizar e retorna para o passo 2.


### Fluxo Alternativo (2): Recuperar a senha
- a. O Usuário solicita a recuperação da senha.
- b. O Sistema exibe um formulário em branco para que os detalhes da recuperação (e-mail) sejam incluídos.
- c. O Usuário fornece as informações de recuperação de senha.
- d. O Sistema envia um email com um link para o processo de recuperação da senha.
- e. O Usuário acessa esse link.
- f. O Sistema apresenta um formulário em branco para que a informação de recuperação de senha (nova senha) seja incluída.
- g. O Usuário fornece a nova credencial.
- h. O Usuário retorna ao passo 2.
