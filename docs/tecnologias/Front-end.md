# 🎨 Front-end — EyeGlass / EyeGen

O front-end é a camada responsável pela experiência visual e interações diretas do usuário com o ecossistema EyeGlass, incluindo a loja, painel do usuário e área administrativa.

---

# 🧩 Tecnologias Utilizadas

- **React.js + Vite**
- JavaScript / TypeScript
- React Router DOM
- CSS Modules / TailwindCSS
- Axios para integração com o backend
- Phosphor Icons / Material Icons
- Estrutura de componentes reutilizáveis

---

# 🖥️ Estrutura de Telas

## 🛒 Loja e apresentação do produto
- Página inicial com apresentação do EyeGlass
- Simulador de planos (Origin, Infinity, Guardian)
- Carrinho e checkout
- Página do produto (especificações técnicas)

## 👤 Painel do Usuário
- Dados pessoais
- Status do plano
- Histórico de navegação assistiva
- Acesso ao suporte
- Configurações da conta

## 🛠️ Painel Administrativo
- Dashboard de métricas
- Gestão de usuários
- Gestão de planos
- Logs de navegação
- Controle de chamados de suporte

---

# 🧱 Arquitetura do Projeto
src/
├── components/ # Botões, cards, modais, loaders
├── pages/ # Telas principais
├── hooks/ # Hooks de integrações (useAuth, usePlan, useAPI)
├── services/ # Axios + Endpoints
├── context/ # Contextos globais
├── assets/ # Imagens, icons e media
├── styles/ # CSS/Tailwind
└── router/ # Rotas da aplicação


---

# 🔌 Comunicação com Backend

- Todas as requisições usam Axios.
- Autenticação com **JWT**.
- Middleware de interceptação para refresh automático.
- Cookies ou localStorage para tokens.

Endpoints principais:
- `/auth/login`
- `/plans/active`
- `/support/ticket`
- `/navigation/history`
- `/device/status`

---

# 🔒 Segurança

- Sanitização de inputs
- Validação de autenticação
- Bloqueio de rotas sem token
- CSRF mitigado com JWT + regras CORS

---

# 🧪 Testes

- React Testing Library
- Jest
- Testes de componentes isolados
- Snapshot tests

---

# 📦 Build & Deploy

- Deploy em:
  - Vercel
  - Netlify
  - Cloudflare Pages
  - GitHub Pages (opcional)

- Pipeline CI/CD com:
  - ESLint
  - Prettier
  - Testes automatizados

---

# 📌 Conclusão

O front-end foi projetado para oferecer:
- Acessibilidade
- Performance
- Consistência visual
- Escalabilidade
- Facilidade de manutenção


