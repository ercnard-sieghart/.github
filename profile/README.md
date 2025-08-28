Solução WEB para integração com o ERP, composta por Front-end e Back-end, versionados em repositórios separados.

📌 Estrutura dos Repositórios

front-end-ics-web → Aplicação Angular (interface do usuário).

back-end-ics-web → API de integração, serviços e regras de negócio.

📖 Cada repositório possui seu próprio README com instruções específicas de instalação e execução.

🚀 Branches

main → Produção

homolog → Homologação

desenv → Desenvolvimento

🔹 Regras de Branching

Novas funcionalidades devem ser desenvolvidas em branches criadas a partir de desenv.

Nomeie as branches seguindo o padrão:

feat/nome-funcionalidade

fix/corrige-alguma-coisa

refactor/ajuste-estrutura

📝 Padrão de Commits

feat: ➝ Nova funcionalidade

fix: ➝ Correção de bug

docs: ➝ Documentação

refactor: ➝ Refatoração de código (sem mudança funcional)

style: ➝ Ajustes visuais/formatação (sem impacto no funcionamento)

test: ➝ Testes adicionados ou modificados

chore: ➝ Tarefas de manutenção (build, configs, libs, CI/CD)

📌 Exemplos de commits:

feat: adiciona endpoint de consulta de extrato bancário
fix: corrige erro de autenticação no login

📚 Boas Práticas Gerais

✔️ Sempre abrir Pull Requests (PRs) para mergear código.
✔️ Revisões de código são obrigatórias antes do merge.
✔️ Abrir Issues para reportar bugs ou solicitar novas funcionalidades.
✔️ Usar Milestones e Projects do GitHub para organizar entregas.
✔️ Nomear PRs de acordo com o commit principal (feat:, fix:, etc.).
