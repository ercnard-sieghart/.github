# 🌐 ICS WEB  

**Solução WEB para integração com o ERP**, composta por **Front-end** e **Back-end**, versionados em repositórios separados.  

---

## 📌 Estrutura dos Repositórios  

- **front-end-ics-web** → Aplicação **Angular** (interface do usuário).  
- **back-end-ics-web** → **API de integração**, serviços e regras de negócio.  

📖 *Cada repositório possui seu próprio README com instruções específicas de instalação e execução.*  

---

## 🚀 Branches  

- **main** → Produção  
- **homolog** → Homologação  
- **desenv** → Desenvolvimento  

### 🔹 Regras de Branching  
- Novas funcionalidades devem ser desenvolvidas em branches criadas a partir de `desenv`.  
- Nomeie as branches seguindo o padrão:  
  - `feat/nome-funcionalidade`  
  - `fix/corrige-alguma-coisa`  
  - `refactor/ajuste-estrutura`  

---

## 📝 Padrão de Commits  

- `feat:` ➝ Nova funcionalidade  
- `fix:` ➝ Correção de bug  
- `docs:` ➝ Documentação  
- `refactor:` ➝ Refatoração de código (sem mudança funcional)  
- `style:` ➝ Ajustes visuais/formatação (sem impacto no funcionamento)  
- `test:` ➝ Testes adicionados ou modificados  
- `chore:` ➝ Tarefas de manutenção (build, configs, libs, CI/CD)  

📌 **Exemplos de commits**:  
- feat: adiciona endpoint de consulta de extrato bancário
- fix: corrige erro de autenticação no login

## 📚 Boas Práticas de Desenvolvimento  

### 🧼 Código Limpo  
- Use nomes claros e descritivos para variáveis, funções e classes.  
- Prefira inglês para nomes de arquivos e identificadores.  
- Evite duplicação de código (DRY - *Don’t Repeat Yourself*).  
- Funções devem ter responsabilidade única.  

---

### 📖 Documentação  
- Documente funções complexas ou regras de negócio críticas.  
- Use **README**, Wiki e/ou Swagger (no back-end) para explicar fluxos.  
- Inclua exemplos de uso quando possível.  
- Atualize a documentação junto com a alteração do código.  

---

### 🧪 Testes  
- Escreva testes unitários para novas funcionalidades.  
- Garanta que todos os testes passem antes de abrir um PR.  
- Utilize testes de integração quando envolver múltiplos módulos.  
- Evite *mockar* em excesso, mantenha testes próximos da realidade.  

---

### 🔀 Pull Requests (PRs)  
- PRs devem ser curtos, objetivos e focados em **uma entrega por vez**.  
- Sempre abra PR a partir de `desenv`.  
- Pelo menos **1 revisão de outro dev** é obrigatória antes do merge.  
- Descreva claramente no PR o que foi alterado, incluindo prints/logs quando necessário.  
- Não faça commits diretamente na `main`.  

---

### 🔒 Segurança  
- Nunca commit **credenciais, tokens ou senhas**.  
- Use `.env` para variáveis sensíveis e adicione ao `.gitignore`.  
- Atualize dependências regularmente para evitar vulnerabilidades.  
- Valide entradas de usuário no back-end (contra SQL Injection, XSS, etc.).  
- Utilize HTTPS em ambientes de produção.  

feat: adiciona endpoint de consulta de extrato bancário
fix: corrige erro de autenticação no login
