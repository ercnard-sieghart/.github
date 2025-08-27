Organização de Projetos

Projeto principal - Solução WEB para integração com o ERP, composta por Front-end e Back-end, versionados em repositórios separados.

📌 Estrutura dos Repositórios

front-end-ics-web → Aplicação Angular (interface do usuário).

back-end-ics-web → API de integração, serviços e regras de negócio.

Cada repositório possui seu próprio README com instruções específicas de instalação e execução.

🚀 Branches

main → Produção

homolog → Homologação

desenv → Desenvolvimento

🔹 Regras:

Novas funcionalidades devem ser desenvolvidas em branches específicas criadas a partir de desenv.

Nomeie as branches seguindo o padrão:

feat/nome-funcionalidade

fix/corrige-alguma-coisa

refactor/ajuste-estrutura

📝 Padrão de Commits

feat: Nova funcionalidade

fix: Correção de bug

docs: Documentação

refactor: Refatoração de código (sem mudança funcional)

style: Ajustes visuais/formatação (sem impacto no funcionamento)

test: Testes adicionados ou modificados

chore: Tarefas de manutenção (build, configs, libs, CI/CD)

Exemplo:

feat: adiciona endpoint de consulta de extrato bancário
fix: corrige erro de autenticação no login

🛠️ Back-end (ICS WEB API)

Dependendo da stack escolhida (Node.js, Go, Java Spring Boot), manteremos as boas práticas:

Estrutura Esperada

/src → Código-fonte

/tests → Testes automatizados

/docs → Documentação da API (Swagger/OpenAPI)

/scripts → Scripts auxiliares (deploy, migrations, seeds, etc.)

Convenções

Seguir padrões de Clean Code e SOLID.

Cada endpoint/documentação deve estar descrito no Swagger (ou Postman Collection).

Configurações sensíveis (senhas, tokens, chaves) devem ser armazenadas em .env (nunca commitado).

Rodando o projeto (Node.js exemplo)
yarn install
yarn dev

Testes
yarn test

⚙️ Integração e Deploy

CI/CD via GitHub Actions (ou outro pipeline configurado).

Commits na main disparam build para produção.

Commits na homolog disparam build para ambiente de homologação.

📚 Boas Práticas Gerais

Sempre abrir Pull Requests (PRs) para mergear código.

Revisões de código são obrigatórias antes de merge.

Issues devem ser abertas para bugs ou novas funcionalidades.

Usar milestones e projects do GitHub para organizar entregas.

Nomear PRs de acordo com o commit principal (feat:, fix:, etc.).
