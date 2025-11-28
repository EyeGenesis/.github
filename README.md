<p align="center">
  <img src="docs/EyeGlass.png" width="500" alt="EyeGlass Banner"/>
</p>

<h1 align="center">👁️ EyeGlass / EyeGen</h1>

<p align="center">
  Sistema de Navegação Assistiva utilizando IA, Visão Computacional e IoT.<br/>
  Criado para apoiar pessoas com deficiência visual na locomoção diária com segurança, autonomia e inteligência.
</p>

---

## 🧭 Sobre o Projeto

O **EyeGlass / EyeGen** é um sistema vestível que combina **Visão Computacional**, **IA Generativa**, **IoT**, **HUD** e **TTS** para interpretar ambientes e orientar usuários com deficiência visual.  
O sistema detecta obstáculos, analisa o caminho, identifica objetos e fornece comandos por voz em tempo real.

---

## ✨ Funcionalidades Principais

- 🔎 **Detecção de objetos** com YOLO  
- 🧠 **Raciocínio contextual** baseado em LLM (DSPy)  
- 🔊 **Feedback por voz** (TTS)  
- 🕶️ **HUD integrado ao óculos inteligente**  
- 📡 **Comunicação IoT com sensores externos**  
- 🧭 Direções inteligentes (esquerda, direita, siga, pare)  
- ⚙️ Arquitetura modular e escalável  

---

# 📘 Documentação Oficial

A documentação está organizada por temas.  
Cada seção abaixo contém um **resumo** + link para a versão completa no `/docs/`.

---

<details>
  <summary><strong>🔧 Instalação & Configuração</strong></summary>
  <br>
  Configuração inicial, requisitos, ambiente virtual, ativação da câmera/óculos, variáveis de ambiente e como executar o sistema.
  <br><br>
  ➡️ <a href="docs/INSTALACAO.md">Ver mais detalhes</a>
</details>

---

<details>
  <summary><strong>🧩 Tecnologias</strong></summary>
  <br>
  Stack utilizada no EyeGen, incluindo IA, modelos de visão computacional, frameworks de backend, TTS, IoT, drivers de câmera e HUD.
  <br><br>
  ➡️ <a href="docs/TECNOLOGIAS.md">Ver mais detalhes</a>
</details>

---

<details>
  <summary><strong>🧭 Jornada do Usuário</strong></summary>
  <br>
  Experiência do usuário desde ligar o dispositivo até receber orientações inteligentes, com exemplos de navegação e alertas por voz.
  <br><br>
  ➡️ <a href="docs/JORNADA_USER.md">Ver mais detalhes</a>
</details>

---

<details>
  <summary><strong>💰 Financeiro</strong></summary>
  <br>
  Custos de protótipo, estimativa de hardware, componentes, servidor, manutenção e possíveis modelos de negócio/mensalidade.
  <br><br>
  ➡️ <a href="docs/FINANCEIRO.md">Ver mais detalhes</a>
</details>

---

<details>
  <summary><strong>👥 Equipe</strong></summary>
  <br>
  Estrutura da equipe, responsabilidades, áreas de atuação, contribuições e próximos papéis a serem preenchidos.
  <br><br>
  ➡️ <a href="docs/EQUIPE.md">Ver mais detalhes</a>
</details>

---

<details>
  <summary><strong>📄 Sobre o Projeto</strong></summary>
  <br>
  Visão, propósito, impacto social, motivação inicial, objetivos de longo prazo e futuro da plataforma EyeGen/EyeGlass.
  <br><br>
  ➡️ <a href="docs/SOBRE.md">Ver mais detalhes</a>
</details>

---

# ⚙️ Instalação (Resumo Rápido)

> Versão completa: `docs/INSTALACAO.md`

```bash
git clone https://github.com/seu-repo/EyeGen.git
cd EyeGen

python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate

pip install -r requirements.txt

python app.py
