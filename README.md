# App

Gympass style app.

## RFs (Requisitos funcionais)

- [ ] Deve ser possível se cadastrar;
- [ ] Deve ser possível se autenticar;
- [ ] Deve ser possível obter o perfil de um usuário logado;
- [ ] Deve ser possível obter o npumero de check-ins realizados pelo usuário logado;
- [ ] Deve ser possível o usuário buscar academias próximas;
- [ ] Deve ser possível o usuário buscar academias pelo nome;
- [ ] Deve ser possível o usuário realizar check-in em uma academia;
- [ ] Deve ser possível validar o check-in de um usuário;
- [ ] Deve ser possível cadastrar uma academia;

## RNs (Regras de negócio)

- [ ] o usuário não deve poder se cadastrar com um e-mail duplicado;
- [ ] o usuário não pode fazer 2 check-ins no mesmo dia;
- [ ] o usuário não pode fazer check-in se não estiver perto (100m) da academia;
- [ ] o check-in só pode ser validado até 20 minutos após criado;
- [ ] o check-in só pode ser validado por administradores;
- [ ] a academia só pode ser cadastrada por administradores;
 
## RNFs (Requisitos não-funcionais)

- [ ] a senha do usuário precisa estar criptografadas;
- [ ] os dados da aplicação preciam estar persitidos em um banco PostgreSQL;
- [ ] todas listas de dados precisam estar paginadas com 20 itens por página;
- [ ] o usuário deve ser identificado por um JWT;