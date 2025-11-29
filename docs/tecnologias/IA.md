
# 🧠 Inteligência Artificial — EyeGlass / EyeGen

A IA é o núcleo da experiência do EyeGlass, responsável por interpretar o ambiente em tempo real.

---

# 🧩 Tecnologias Utilizadas

- Python 3.10+
- YOLOv8 / YOLOv11
- OpenCV
- PyTorch
- DSPy (Stanford)
- TTS (pyttsx3, Coqui ou GTTTS)
- Flask API ou FastAPI

---

# 🎯 Funções da IA

- Detectar objetos, pessoas e obstáculos
- Estimar distância
- Definir nível de risco
- Emitir instruções ao usuário
- Resumir o contexto usando LLM
- Gerar fala em tempo real
- Enviar dados para backend/IoT

---

# 🧠 Pipeline de Processamento

Câmera → YOLO → DSPy → Análise de risco → TTS → Saída em áudio


---

# 🔌 Endpoints da IA

- **POST /predict** — recebe imagem, retorna objetos
- **POST /insights** — DSPy cria instrução contextual
- **POST /tts** — gera áudio
- **GET /health** — status da IA

---

# 🎛️ Configurações Suportadas

- Modo GPU/CPU
- Número de threads OpenMP
- Redução de resolução para economia de energia
- Cache inteligente de IA

---

# 📌 Conclusão

A IA permite que o usuário:
- receba instruções em tempo real,
- compreenda o ambiente,
- navegue com maior segurança.

