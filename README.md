# EBD Backend API

Este é o backend da aplicação **EBD PRO (Escola Bíblica Dominical)**, uma plataforma para igrejas gerenciarem suas aulas, turmas, alunos e relatórios semanais. O sistema oferece funcionalidades como cadastro de usuários (admin, secretário e professor), registro de aulas, chamadas e geração de relatórios.

## Tecnologias Utilizadas

- **Node.js**: Ambiente de execução JavaScript no servidor.
- **Fastify**: Framework web rápido e eficiente.
- **TypeScript**: Superset de JavaScript que adiciona tipagem estática.
- **Prisma ORM**: Ferramenta para manipulação de banco de dados com TypeScript.
- **PostgreSQL**: Banco de dados relacional utilizado.
- **Swagger**: Documentação da API.
- **Zod**: Validação de dados com TypeScript.

## Funcionalidades Principais

- **Autenticação e Autorização**: Login e controle de permissões baseado em papéis (Admin, Secretário, Professor).
- **Cadastro de Usuários**: Gerenciamento de usuários da aplicação.
- **Gerenciamento de Turmas**: CRUD de turmas e associação de professores.
- **Registro de Alunos**: Cadastro e gerenciamento de alunos vinculados a turmas.
- **Aulas e Chamada**: Registro de aulas e chamadas, com controle de presenças, bíblias, revistas, ofertas e visitantes.
- **Relatórios**: Geração de relatórios semanais com ranking das turmas.

## Requisitos

- **Node.js** 
- **PostgreSQL** 
- **Yarn** ou **npm**
