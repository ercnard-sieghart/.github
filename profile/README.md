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


📚 Boas Práticas Gerais

Sempre abrir Pull Requests (PRs) para mergear código.

Revisões de código são obrigatórias antes de merge.

Issues devem ser abertas para bugs ou novas funcionalidades.

Usar milestones e projects do GitHub para organizar entregas.

Nomear PRs de acordo com o commit principal (feat:, fix:, etc.).
