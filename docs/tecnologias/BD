# 🗄️ Banco de Dados — EyeGlass / EyeGen

O banco de dados sustenta toda a persistência de informações do ecossistema EyeGlass.

---

# 🧩 Tecnologias Utilizadas

- MySQL ou PostgreSQL
- Prisma ORM (NodeJS)
- JPA/Hibernate (Java)
- Supabase / PlanetScale em nuvem

---

# 🧱 Modelo Entidade-Relacionamento

## Tabelas principais:

### 👤 users
- id  
- nome  
- email  
- senha_hash  
- plano_atual  
- data_renovacao  

### 🎧 devices
- id  
- id_usuario  
- status  
- última_atividade  

### 🧠 navigation_logs
- id  
- id_usuario  
- objetos_detectados  
- coordenadas  
- distância  
- data_hora  

### 💳 payments
- id  
- id_usuario  
- valor  
- método  
- status  
- data  

### 🆘 support_tickets
- id  
- id_usuario  
- categoria  
- descrição  
- prioridade  
- status  

### 🔧 hardware_events
- id  
- id_dispositivo  
- tipo  
- payload  
- timestamp  

---

# 🔐 Segurança do Banco

- Criptografia de senhas
- Backups automáticos diários
- Políticas de retenção
- Rotação automática de credenciais
- Roles segmentadas (admin, device, default)

---

# 🚀 Escalabilidade

- Índices otimizados para IA e logs
- Horizontal sharding para tabelas de navegação
- Replicas de leitura para alto desempenho

---

# 📌 Conclusão

O banco de dados garante:
- Persistência segura
- Consistência entre módulos
- Escalabilidade para milhares de logs de navegação por dia
