<style>
@keyframes float {
  0%, 100% { transform: translateY(0px) translateX(0px); opacity: 0.8; }
  50% { transform: translateY(-20px) translateX(10px); opacity: 1; }
}

@keyframes pulse {
  0%, 100% { r: 2px; opacity: 0.6; }
  50% { r: 3px; opacity: 1; }
}

.particles {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh;
  pointer-events: none;
  z-index: -1;
  background: linear-gradient(135deg, #0f0c29 0%, #302b63 50%, #24243e 100%);
}

.particle {
  animation: float 6s infinite ease-in-out;
  animation-delay: var(--delay);
}
</style>

<svg class="particles" viewBox="0 0 1200 800" preserveAspectRatio="xMidYMid slice">
  <defs>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- Background gradient -->
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0f0c29;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#302b63;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#24243e;stop-opacity:1" />
    </linearGradient>
  </defs>
  
  <rect width="1200" height="800" fill="url(#bgGrad)"/>
  
  <!-- Partículas animadas -->
  <circle class="particle" cx="100" cy="150" r="2" fill="#00d4ff" filter="url(#glow)" style="--delay: 0s;" opacity="0.6">
    <animate attributeName="cy" from="150" to="-50" dur="8s" repeatCount="indefinite"/>
    <animate attributeName="cx" from="100" to="150" dur="8s" repeatCount="indefinite"/>
  </circle>
  
  <circle class="particle" cx="300" cy="200" r="2.5" fill="#00d4ff" filter="url(#glow)" style="--delay: 0.5s;" opacity="0.5">
    <animate attributeName="cy" from="200" to="-50" dur="10s" repeatCount="indefinite"/>
    <animate attributeName="cx" from="300" to="250" dur="10s" repeatCount="indefinite"/>
  </circle>
  
  <circle class="particle" cx="500" cy="100" r="2" fill="#00d4ff" filter="url(#glow)" style="--delay: 1s;" opacity="0.6">
    <animate attributeName="cy" from="100" to="-50" dur="9s" repeatCount="indefinite"/>
    <animate attributeName="cx" from="500" to="550" dur="9s" repeatCount="indefinite"/>
  </circle>
  
  <circle class="particle" cx="700" cy="250" r="2.5" fill="#00d4ff" filter="url(#glow)" style="--delay: 1.5s;" opacity="0.5">
    <animate attributeName="cy" from="250" to="-50" dur="11s" repeatCount="indefinite"/>
    <animate attributeName="cx" from="700" to="650" dur="11s" repeatCount="indefinite"/>
  </circle>
  
  <circle class="particle" cx="900" cy="150" r="2" fill="#00d4ff" filter="url(#glow)" style="--delay: 2s;" opacity="0.6">
    <animate attributeName="cy" from="150" to="-50" dur="8.5s" repeatCount="indefinite"/>
    <animate attributeName="cx" from="900" to="950" dur="8.5s" repeatCount="indefinite"/>
  </circle>
  
  <circle class="particle" cx="150" cy="400" r="2.5" fill="#00d4ff" filter="url(#glow)" style="--delay: 2.5s;" opacity="0.5">
    <animate attributeName="cy" from="400" to="-50" dur="10.5s" repeatCount="indefinite"/>
    <animate attributeName="cx" from="150" to="100" dur="10.5s" repeatCount="indefinite"/>
  </circle>
  
  <circle class="particle" cx="1050" cy="300" r="2" fill="#00d4ff" filter="url(#glow)" style="--delay: 3s;" opacity="0.6">
    <animate attributeName="cy" from="300" to="-50" dur="9.5s" repeatCount="indefinite"/>
    <animate attributeName="cx" from="1050" to="1100" dur="9.5s" repeatCount="indefinite"/>
  </circle>
  
  <circle class="particle" cx="400" cy="50" r="2" fill="#00d4ff" filter="url(#glow)" style="--delay: 3.5s;" opacity="0.5">
    <animate attributeName="cy" from="50" to="-50" dur="7s" repeatCount="indefinite"/>
    <animate attributeName="cx" from="400" to="450" dur="7s" repeatCount="indefinite"/>
  </circle>
  
  <circle class="particle" cx="800" cy="400" r="2.5" fill="#00d4ff" filter="url(#glow)" style="--delay: 4s;" opacity="0.6">
    <animate attributeName="cy" from="400" to="-50" dur="11s" repeatCount="indefinite"/>
    <animate attributeName="cx" from="800" to="750" dur="11s" repeatCount="indefinite"/>
  </circle>
  
  <circle class="particle" cx="200" cy="600" r="2" fill="#00d4ff" filter="url(#glow)" style="--delay: 4.5s;" opacity="0.5">
    <animate attributeName="cy" from="600" to="-50" dur="10s" repeatCount="indefinite"/>
    <animate attributeName="cx" from="200" to="250" dur="10s" repeatCount="indefinite"/>
  </circle>
</svg>

<h1>
  Hola, soy Mateo 
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="35">
</h1>

**Desarrollador Python | Data Science | MLOps | DevOps for AI**

---

## 🚀 Sobre mí

Soy un desarrollador fullstack especializado en **ML/Data Science** con experiencia en infraestructura moderna para aplicaciones de IA. Me apasiona construir pipelines escalables, optimizar modelos de deep learning y automatizar workflows complejos. Combino expertise en **backend**, **DevOps** e **infraestructura cloud** para dejar soluciones de producción confiables.

---

## 💻 Tecnologías

### 🐍 Backend & Data Science
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

### 🎨 Frontend
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34C26?style=for-the-badge&logo=html5&logoColor=white)

### 🐳 DevOps & Infraestructura
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![RunPod](https://img.shields.io/badge/RunPod-0B00FF?style=for-the-badge&logo=runpod&logoColor=white)

---

## 🎯 Áreas de Expertise

| Área | Skills |
|------|--------|
| **Machine Learning & AI** | PyTorch, CUDA, Optimización de modelos, Fine-tuning, Inference |
| **Data Science** | Análisis exploratorio, Pipelines de datos, Visualización |
| **MLOps** | Deployments de modelos, Monitoreo, Automatización, Versionado |
| **DevOps & Cloud** | Containerización, Orquestación, CI/CD, AWS Services, Computación GPU |
| **Backend** | APIs, Bases de datos, Escalabilidad, Arquitecturas cloud-native |
| **Frontend** | SPAs, Aplicaciones desktop, Responsive design, State management |

---

## 📊 Mi Stack Típico

- **ML/AI**: Python + PyTorch + CUDA
- **Deployments**: Docker + Kubernetes + AWS / RunPod
- **Backend**: Python (FastAPI/Django) + APIs REST
- **Frontend**: React/Angular + TypeScript
- **Infraestructura**: CI/CD, Monitoring, Automatización

---

## 🌟 Intereses

- 🤖 Modelos de lenguaje y visión computacional
- 🚀 Optimización de inference en GPU
- ⚙️ Arquitecturas escalables para IA
- 📦 MLOps best practices
- 🌐 Desarrollo fullstack de soluciones IA

---

## 🔗 Conecta conmigo

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mateoalban)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mateoalban)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tu-email@example.com)

---

**💡 Siempre abierto a colaborar en proyectos de IA/ML, DevOps e infraestructura cloud.**
