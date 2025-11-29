# 📡 IoT — EyeGlass / EyeGen

O módulo IoT conecta o óculos ao servidor e à IA.

---

# 🧩 Tecnologias Utilizadas

- MQTT ou WebSockets
- Raspberry Pi Zero 2W
- ESP32 (versões internas)
- HTTP/REST
- Criptografia TLS

---

# 🔌 Funções do IoT

- Envio contínuo de frames para a IA
- Envio de telemetria (bateria, temperatura, câmera)
- Recebimento de instruções de voz
- Reset e atualização remota (OTA)
- Comunicação bidirecional em baixa latência

---

# 🔧 Tipos de Mensagens

### 📤 Dispositivo → Servidor
- Frame base64
- Sensor de distância
- Status da câmera
- Pacotes de telemetria

### 📥 Servidor → Dispositivo
- Arquivos de áudio
- Comandos de navegação
- Atualizações do sistema

---

# 📡 Arquitetura de Comunicação
EyeGlass → IoT Broker → Backend → IA → Backend → IoT → Usuário


---

# 📌 Conclusão

O módulo IoT garante:
- comunicação rápida,
- confiável,
- sempre disponível
entre o mundo físico e a inteligência do sistema.
