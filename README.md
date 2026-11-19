# Hola, soy Joaquin Chandia 👋

Estudiante de **Ingeniería en Redes y Telecomunicaciones** en Duoc UC (Concepción, Chile).
Me interesan las redes, la ciberseguridad con enfoque defensivo, IoT y la automatización con Python.

## 🔧 En qué estoy

- 🌐 **Redes:** curso CCNA de Cisco NetAcad (conmutación, enrutamiento y redes inalámbricas), Packet Tracer.
- 🛡️ **Ciberseguridad:** practicando en TryHackMe con enfoque defensivo.
- 🤖 **IoT y Python:** programación de algoritmos para IoT y mi proyecto principal, Yayita.

## 🚀 Proyectos destacados

### [🛡️ Control de Rondas: app web para guardias de seguridad](https://github.com/Wikzeed/control-de-rondas)

App en producción para una empresa de seguridad privada: los guardias marcan sus rondas escaneando letreros QR con su celular (sin instalar nada) y reportan problemas con foto y audio. El supervisor ve el cumplimiento en un panel y saca reportes para el cliente.

- QR con token secreto, hora puesta por el servidor y PIN por guardia guardado como HMAC.
- Protección CSRF, límite de intentos, cabeceras de seguridad (CSP) y respaldo diario.
- Python · Flask · SQLite · JavaScript (PWA).

### [🐱 Yayita: asistente de voz para un robot de escritorio](https://github.com/Wikzeed/yayita)

Asistente de voz en español hecha en Python, que corre 24/7 en un servidor Linux en mi casa.

- Palabra de activación **offline** («Oye Yayita», con Vosk) y voz natural.
- IA con varios respaldos: **Claude** como cerebro, Gemini y una IA local (Ollama) en mi PC, que despierta con **Wake-on-LAN**.
- **Seguridad primero:** la IA no ejecuta nada directamente, solo pide acciones de una lista blanca que el código valida. Además: firewall con nftables, acceso remoto solo por Tailscale y PIN con cookie firmada (HMAC).
- Domótica y red: lámpara por la red local, Spotify, aviso de cortes de internet y de aparatos nuevos en el Wi-Fi.
- Visión: vigilancia con OpenCV + YOLOv8, ojos animados en pantalla que siguen tu cara y reconocimiento de gestos.
- Más de **1.100 pruebas automáticas** con pytest.

## 🧰 Herramientas

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?logo=debian&logoColor=white)
![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?logo=cisco&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?logo=tailscale&logoColor=white)
![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?logo=tryhackme&logoColor=white)

## 🗣️ Idiomas

- Español: nativo
- Inglés: lectura técnica y comprensión auditiva
- Francés: básico

---

<details>
<summary>🇬🇧 <b>English</b></summary>

## Hi, I'm Joaquin Chandia 👋

**Networking and Telecommunications Engineering** student at Duoc UC (Concepción, Chile).
I'm interested in networking, defensive cybersecurity, IoT and automation with Python.

### 🔧 What I'm working on

- 🌐 **Networking:** Cisco NetAcad CCNA course (switching, routing and wireless), Packet Tracer.
- 🛡️ **Cybersecurity:** practicing on TryHackMe with a defensive focus.
- 🤖 **IoT and Python:** IoT algorithm programming and my main project, Yayita.

### 🚀 Featured projects

**[🛡️ Guard Patrol Control](https://github.com/Wikzeed/control-de-rondas)**: a web app in production for a private security company. Guards check in at each patrol point by scanning QR signs with their phones (nothing to install) and report issues with photos and audio. Supervisors track compliance on a dashboard and generate reports for clients. Secret QR tokens, server-side timestamps, HMAC-stored PINs, CSRF protection, rate limiting and security headers (CSP).

**[🐱 Yayita](https://github.com/Wikzeed/yayita)**: a Spanish-speaking voice assistant in Python, running 24/7 on a Linux server at home. Offline wake word (Vosk), AI with fallbacks (Claude, Gemini and a local model with Ollama woken up by Wake-on-LAN), smart home control, computer vision (OpenCV + YOLOv8) and an action allowlist so the AI can never execute anything on its own. Firewall with nftables, remote access only through Tailscale, and 1,100+ automated tests.

### 🗣️ Languages

Spanish (native) · English (technical reading and listening) · French (basic)

</details>
