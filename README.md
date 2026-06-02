<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/4712/4712109.png" />

# 🤖 OpenJarvis

### Personal AI, ejecutándose localmente en tus propios dispositivos 🚀

<p align="center">
  <b>OpenJarvis</b> es una plataforma de inteligencia artificial local-first diseñada para crear asistentes personales capaces de ejecutarse directamente en computadoras personales, minimizando la dependencia de servicios en la nube.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/OpenJarvis-PersonalAI-blueviolet?style=for-the-badge">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Rust-Extensions-000000?style=for-the-badge&logo=rust&logoColor=white">
  <img src="https://img.shields.io/badge/Ollama-LocalLLM-green?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-agentes-integrados">Agentes</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-instalación">Instalación</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**OpenJarvis** es un framework de inteligencia artificial diseñado bajo una filosofía **Local-First AI**, permitiendo que asistentes personales funcionen directamente en dispositivos locales sin depender constantemente de APIs externas o servidores remotos.

El proyecto surge a partir de investigaciones sobre eficiencia energética e inteligencia artificial local, demostrando que los modelos modernos ya pueden resolver gran parte de las tareas cotidianas ejecutándose directamente en hardware personal.

---

# ✨ Características

## 🤖 Inteligencia Artificial Local

- Ejecución local de modelos LLM
- Menor dependencia de servicios cloud
- Privacidad de datos mejorada
- Menor latencia de respuesta
- Costos operativos reducidos

---

## 🧠 Agentes Inteligentes

- Asistentes personales autónomos
- Investigación avanzada con múltiples fuentes
- Automatización de tareas
- Memoria persistente
- Ejecución programada

---

## 🔌 Integración de Herramientas

- Gmail
- Google Calendar
- Google Drive
- Sistemas locales
- Archivos del usuario
- APIs externas cuando son necesarias

---

## ⚡ Optimización

- Métricas de eficiencia energética
- Optimización de FLOPs
- Control de consumo computacional
- Evaluación de rendimiento en tiempo real

---

# 👨‍💻 Agentes integrados

## 🌅 Morning Digest

Genera resúmenes diarios personalizados.

### Funciones

- Correos electrónicos
- Calendario
- Noticias
- Recordatorios
- Conversión a voz

---

## 🔍 Deep Research

Asistente especializado en investigación avanzada.

### Funciones

- Investigación multi-hop
- Búsqueda documental
- Citaciones automáticas
- Resúmenes inteligentes
- Análisis de contenido

---

## 🧠 Orchestrator

Sistema central de razonamiento.

### Funciones

- Selección automática de herramientas
- Planeación de tareas
- Coordinación entre agentes
- Automatización inteligente

---

## 💻 Code Assistant

Asistente para desarrolladores.

### Funciones

- Generación de código
- Ejecución de scripts
- Lectura de archivos
- Acceso al sistema
- Automatización de desarrollo

---

## 🔄 Operative

Agente persistente con memoria.

### Funciones

- Monitoreo continuo
- Gestión de estado
- Recuperación de información
- Automatización programada

---

# 🛠️ Tecnologías utilizadas

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=python,rust" />
</p>

- Python 3.10+
- Rust Extensions
- Async Processing
- Agent Framework

---

## 🤖 Inteligencia Artificial

<p>
  <img src="https://skillicons.dev/icons?i=python" />
</p>

- Large Language Models
- Local AI
- Agent Systems
- DSPy Optimization
- Reasoning Agents

---

## 🗄️ Modelos Locales

<p>
  <img src="https://skillicons.dev/icons?i=linux" />
</p>

- Ollama
- Local LLMs
- Retrieval Systems
- Embeddings
- Knowledge Indexing

---

## ☁️ Integraciones

- Google Drive
- Gmail
- Google Calendar
- OAuth Authentication
- Web Search
- Local File Systems

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github,vscode,docker,linux" />
</p>

- Git
- GitHub
- Docker
- VS Code
- Linux
- UV Package Manager

---

# 📂 Estructura del proyecto

```bash
OpenJarvis/
│
├── agents/                 # Agentes inteligentes
├── skills/                 # Skills y herramientas
├── memory/                 # Sistema de memoria
├── configs/                # Configuraciones
├── docs/                   # Documentación
├── benchmarks/             # Evaluaciones
├── tests/                  # Pruebas
├── scripts/                # Automatizaciones
├── docker/                 # Contenedores
├── assets/                 # Recursos gráficos
├── pyproject.toml
└── README.md
```

---

# ⚡ Instalación

## 📋 Requisitos

- Python 3.10+
- Linux, macOS o WSL2
- Conexión a Internet
- Ollama

---

# 🚀 Instalación rápida

## 1️⃣ Instalador automático

```bash
curl -fsSL https://openjarvis.ai/install.sh | bash
```

---

## 2️⃣ Ejecutar OpenJarvis

```bash
jarvis
```

---

## 3️⃣ Verificar estado

```bash
jarvis doctor
```

---

# 🎯 Configuraciones rápidas

## 🌅 Morning Digest

```bash
jarvis init --preset morning-digest-mac
```

Genera reportes diarios personalizados con voz integrada.

---

## 🔍 Deep Research

```bash
jarvis init --preset deep-research
```

Asistente para investigación avanzada y documentación.

---

## 💻 Code Assistant

```bash
jarvis init --preset code-assistant
```

Entorno especializado para desarrollo de software.

---

## 🤖 Chat Simple

```bash
jarvis init --preset chat-simple
```

Modo conversacional ligero.

---

# 🧠 Sistema de Skills

Los Skills permiten extender las capacidades de OpenJarvis mediante herramientas reutilizables.

## Instalar Skills

```bash
jarvis skill install hermes:arxiv
```

---

## Sincronizar Skills

```bash
jarvis skill sync hermes --category research
```

---

## Optimizar Skills

```bash
jarvis optimize skills --policy dspy
```

---

# 📊 Funcionalidades principales

## 🤖 IA Local

- Ejecución local
- Privacidad avanzada
- Baja latencia
- Menor costo operativo

---

## 🧠 Investigación

- Búsqueda avanzada
- Análisis documental
- Citaciones automáticas
- Recuperación contextual

---

## 🔄 Automatización

- Tareas programadas
- Monitoreo continuo
- Recordatorios inteligentes
- Integración de herramientas

---

## 💻 Productividad

- Gestión de correo
- Calendarios
- Archivos
- Automatización de flujos de trabajo

---

# 🚧 Roadmap

## 🔮 Próximas mejoras

- 📱 Aplicación móvil
- 🧠 Nuevos agentes autónomos
- 🌍 Más integraciones cloud híbridas
- ⚡ Optimización energética
- 🔊 Mejoras en TTS y STT
- 🤖 Aprendizaje personalizado
- ☁️ Despliegue distribuido

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Clonar repositorio

```bash
git clone https://github.com/open-jarvis/OpenJarvis.git
```

2. Entrar al proyecto

```bash
cd OpenJarvis
```

3. Instalar entorno

```bash
uv sync --extra dev
```

4. Ejecutar pruebas

```bash
uv run pytest tests/ -v
```

5. Crear Pull Request 🚀

---

# 🏛️ Investigación y desarrollo

OpenJarvis forma parte de iniciativas de investigación en eficiencia de IA desarrolladas por:

- Stanford SAIL
- Hazy Research
- Scaling Intelligence Lab
- Intelligence Per Watt

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella

🍴 Haz fork

📢 Comparte el proyecto

🤝 Contribuye con nuevas funcionalidades

---

# 📜 Licencia

Proyecto distribuido bajo licencia Apache 2.0 para investigación, desarrollo y despliegue de asistentes inteligentes locales.

---

<div align="center">

### 🤖 OpenJarvis — Personal AI ejecutándose directamente en tus dispositivos 🚀

</div>
