# App

CynPass stule app.


## RFs (Requisitos Funcionais)
- [] Deve ser possivel se cadastrar;
- [] Deve ser possivel se autenticar;
- [] Deve ser possivel obtero perfil de um usuario logado;
- [] Deve ser possivel obter o numero do check-ins realizado pelo usuario logado;
- [] Deve ser possivel o usuario obter seu historico de check-ins;
- [] Deve ser possivel o usuario buscar academias proximas;
- [] Deve ser possivel o usuario buscar academia pelo nome;
- [] Deve ser possivel o usuario realizar check-ins em uma academia;
- [] deve des possivel validar o check-ins de um usuario;
- [] Deve ser possivel cadastrar uma academia;

## RNs (Regras de Negocios)

- [] O usuario nao deve poder se cadastrar com um e-mail duplicado;
- [] O usuario nao pode fazer 2 check-ins no mesmo dia;
- [] O usuario nao pode fazer check-ins se nao estiver perto(100m) da academia;
- [] O check-ins so pede ser validade apos 20 minutos apos criado;
- [] O check-ins so pode ser validado por um administradores;
- [] A academia so pode ser  cadastrada por  administradores;

## RNFs (Requisitos nao-funcionais)

- [] a senha do usuario precisa esta criptografada;
- [] Os dados da aplicação precisa esta persistidos em um banco PostgreSQL;
- [] Todas lista de dados precisa esta paginadas com 20 itens por pagina;
- [] O usuario deve ser indentificado por um JWT (JSON WEB TOKEN);  