<p align="center">
  <img src="docs/EyeGlass.png" width="500" alt="EyeGlass Banner"/>
</p>

<h1 align="center">👁️ EyeGlass / EyeGen</h1>

<p align="center">
  Sistema de Navegação Assistiva utilizando IA, Visão Computacional e IoT.<br/>
  Criado para apoiar pessoas com deficiência visual na locomoção diária.
</p>

---

## 🧭 Sobre o Projeto

O **EyeGlass / EyeGen** é um sistema vestível que combina **visão computacional**, **raciocínio via LLM**, **IoT**, **HUD** e **TTS** para interpretar ambientes e orientar usuários com deficiência visual em tempo real.

Ele detecta obstáculos, descreve o ambiente, identifica objetos e fornece alertas inteligentes por voz.

---

## ✨ Funcionalidades Principais

- 🔎 **Detecção de objetos em tempo real**  
- 🧠 **Análise contextual com IA (LLM + DSPy)**  
- 🔊 **Orientações por voz (TTS)**  
- 🕶️ **HUD integrado ao óculos inteligente**  
- 📡 **Módulo IoT para sensores externos**  
- 🧭 **Orientações de direção (esquerda, direita, pare, siga)**  
- ⚙️ Arquitetura modular (Front, Back, IA, IoT)

---

## 📘 Documentação

Toda a documentação oficial está na pasta `/docs`:

- 📄 [Instalação & Configuração](docs/INSTALACAO.md)  
- 📄 [Tecnologias](docs/TECNOLOGIAS.md)  
- 📄 [Jornada do Usuário](docs/JORNADA_USER.md)  
- 📄 [Financeiro](docs/FINANCEIRO.md)  
- 📄 [Equipe](docs/EQUIPE.md)  
- 📄 [Sobre](docs/SOBRE.md)

---

## ⚙️ Instalação (Resumo)

> Versão completa em: **docs/INSTALACAO.md**

```bash
git clone https://github.com/seu-repo/EyeGen.git
cd EyeGen

python -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate

pip install -r requirements.txt

python app.py
