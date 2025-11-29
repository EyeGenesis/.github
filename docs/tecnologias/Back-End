# ⚙️ Back-end — EyeGlass / EyeGen

O back-end é a camada central de comunicação entre o app, a IA e o dispositivo físico EyeGlass.

---

# 🧩 Tecnologias Utilizadas

- Node.js + Express.js  
ou
- Java Spring Boot (dependendo da versão do projeto)

Recursos gerais:
- JWT Authentication
- APIs REST
- CORS
- ORM: Prisma (Node) ou JPA/Hibernate (Spring)
- Cloudflare / Railway / AWS

---

# 🔌 Principais Responsabilidades

- Autenticação e autorização
- Gerenciamento de usuários
- Gerenciamento de planos (Origin, Infinity, Guardian)
- Integração com banco de dados
- Comunicação com IA
- Comunicação com o dispositivo via IoT/MQTT
- Logs de navegação
- Suporte técnico e chamados
- Processamento de pagamentos

---

# 🧱 Estrutura de Endpoints

## 📁 Auth
- `POST /auth/login`
- `POST /auth/register`
- `POST /auth/refresh`

## 👤 Usuários
- `GET /users/me`
- `PUT /users/update`

## 🎧 EyeGlass Device
- `POST /device/frame`
- `GET /device/status`
- `POST /device/tts`

## 🧠 IA
- `POST /ai/predict`
- `POST /ai/context`
- `POST /ai/tts`

## 💳 Assinaturas & Pagamentos
- `POST /plans/subscribe`
- `GET /plans/active`

## 🆘 Suporte
- `POST /support/ticket`
- `GET /support/history`

---

# 🔐 Segurança

- JWT completo
- Validação de IP/Origin em rotas críticas
- Middlewares de logs
- Rate limit por usuário/dispositivo
- Hash de senhas com Bcrypt

---

# 🧪 Testes

- Jest (Node) / JUnit (Java)
- Testes de integração
- Testes de carga nas rotas da IA
- Testes de fila IoT

---

# 📦 Deploy

- Containers Docker
- Environments isolados
- Load Balancer
- Escalabilidade horizontal para rotas de IA

---

# 📌 Conclusão

O backend é o coração do sistema e orquestra toda a integração entre:
- App
- IA
- Database
- Hardware
- Serviços externos

