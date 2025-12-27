# RoutineControlSystem

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Version](https://img.shields.io/badge/Version-1.0.0-green.svg)

## Visão Geral

O **RoutineControlSystem** é uma solução de software robusta projetada para otimizar a gestão, o acompanhamento e a monitoramento de rotinas e tarefas diárias. Ele oferece um hub centralizado para organizar fluxos de trabalho, atribuir responsabilidades e garantir a execução consistente de atividades, seja para uso individual ou colaboração em equipe.

## Principais Funcionalidades

- **Gestão de Tarefas**: Crie, atualize e exclua tarefas com descrições detalhadas, prioridades e prazos.
- **Acompanhamento de Rotinas**: Defina rotinas recorrentes e acompanhe seu status de conclusão ao longo do tempo.
- **Monitoramento de Progresso**: Painéis visuais para monitorar o progresso das tarefas e a aderência geral à rotina.
- **Gestão de Utilizadores**: Suporte multi-utilizador com controlo de acesso baseado em funções (RBAC) para equipas.
- **Notificações**: Alertas automáticos para prazos próximos e tarefas pendentes.
- **Relatórios**: Gere relatórios detalhados sobre produtividade e conformidade com as rotinas.

## Pilha de Tecnologias

- **Frontend**: React, TypeScript, Tailwind CSS
- **Backend**: Node.js, Express, TypeScript
- **Banco de Dados**: PostgreSQL, Prisma ORM
- **Autenticação**: JWT (JSON Web Tokens)
- **Deploy**: Docker, Vercel/Heroku

## Começando

### Pré-requisitos

- Node.js (v16 ou superior)
- npm ou yarn
- Banco de dados PostgreSQL

### Instalação

1. Clone o repositório:
   bash
   git clone https://github.com/seu-usuario/routine-control-system.git
   cd routine-control-system
   

2. Instale as dependências:
   bash
   npm install
   # ou
   yarn install
   

3. Configure as variáveis de ambiente:
   Copie o arquivo `.env.example` para `.env` e preencha com suas credenciais de banco de dados e chaves secretas.
   bash
   cp .env.example .env
   

4. Execute as migrações do banco de dados:
   bash
   npx prisma migrate dev
   

5. Inicie o servidor de desenvolvimento:
   bash
   npm run dev
   

## Uso

1. Navegue até `http://localhost:3000` no seu navegador.
2. Registre uma nova conta ou faça login com credenciais existentes.
3. Crie sua primeira rotina ou tarefa a partir do painel de controle.
4. Marque tarefas como concluídas para acompanhar seu progresso.

## Documentação da API

A documentação da API está disponível em `/api-docs` assim que o servidor estiver em execução. Para informações detalhadas, consulte o [Guia de API](docs/API.md).

## Contribuindo

Contribuições são bem-vindas! Siga estes passos:

1. Faça um fork do projeto.
2. Crie sua branch de funcionalidade (`git checkout -b feature/FuncionalidadeIncrivel`).
3. Commit suas mudanças (`git commit -m 'Adiciona alguma FuncionalidadeIncrivel'`).
4. Envie para a branch (`git push origin feature/FuncionalidadeIncrivel`).
5. Abra um Pull Request.

Por favor, certifique-se de que seu código está em conformidade com os padrões do projeto e passa em todos os testes.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para detalhes.

## Contato

Link do Projeto: [https://github.com/seu-usuario/routine-control-system](https://github.com/seu-usuario/routine-control-system)
