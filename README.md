# João Victor Pereira da Silva

**Estudante de Engenharia da Computação na UFSCar · Desenvolvimento back-end · Em busca de estágio**

Construo APIs que lidam com autenticação, regras de negócio e dados que não podem ficar inconsistentes. Meu projeto principal é o **Simple Bank**, um sistema bancário full stack com transações atômicas, autenticação JWT e documentação Swagger. Tenho formação técnica em Informática para Internet pelo IFSP São Carlos.

<details>
<summary>English summary</summary>

Computer Engineering student at UFSCar (Brazil), focused on back-end development and looking for an internship. I build REST APIs with authentication, business rules and data integrity in mind. My main project, **Simple Bank**, is a full-stack banking application with JWT authentication, atomic financial transactions (commit/rollback), rate limiting and Swagger documentation. I also hold a technical diploma in Informatics for the Internet from IFSP São Carlos (integrated high school program).

</details>

## Projetos

### [Simple Bank](https://github.com/jaov07/simple-bank-app)

Aplicação bancária full stack: cadastro, login, consulta de saldo, depósito, saque, extrato de transações e transferência entre usuários por e-mail.

- **Transações atômicas:** operações que alteram mais de uma tabela (como o cadastro, que cria usuário e conta, e as movimentações financeiras) usam commit/rollback, então nada é gravado pela metade.
- **Segurança:** autenticação com JWT, senhas com hash (bcrypt) e rate limiting. O usuário é sempre identificado pelo token, nunca por um id enviado pelo cliente.
- **Arquitetura em camadas:** rotas, controllers (regras de negócio) e models (acesso ao banco) separados.
- **API documentada com Swagger.**

**Stack:** Node.js · Express · MySQL · JWT · Swagger · JavaScript · React.js

<!-- Adicionar aqui quando tiver: link da demo no ar -->

### [ApiUsuarios](https://github.com/jaov07/ApiUsuarios)

API REST de usuários com autenticação JWT, validação de dados (incluindo e-mail duplicado) e documentação Swagger, publicada no Render com MySQL no Railway.

**Stack:** Node.js · Express · MySQL · JWT · bcrypt

### [Organizador de Arquivos](https://github.com/jaov07/organizadorDeArquivos)

Automação em Python para organizar arquivos do computador.

**Stack:** Python

### [Click Or Bang](https://github.com/jaov07/ClickOrBang)

Jogo desenvolvido como TCC do ensino técnico integrado, em GameMaker Language (GML).

**Stack:** GML

## Tecnologias

- **Back-end:** Node.js, Express, APIs REST, autenticação JWT, bcrypt
- **Banco de dados:** MySQL
- **Web:** JavaScript, HTML5, CSS3
- **Outras:** Python (automação), GML
- **Ferramentas:** Git, GitHub, Swagger

## Contato

- LinkedIn: [João Victor](https://www.linkedin.com/in/jo%C3%A3o-victor-b2b2832ab/)
- E-mail: joaovictor70678@gmail.com
