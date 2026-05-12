# 🛡️ Herramientas de Ciberseguridad

Repositorio informativo con herramientas utilizadas en análisis, auditorías, pruebas defensivas y trabajos educativos relacionados con la ciberseguridad.  
El objetivo es servir como referencia rápida para saber qué herramienta puede resultar útil dependiendo de la situación.

---

## 📌 Índice

- [🔍 Análisis y Enumeración de Redes](#-análisis-y-enumeración-de-redes)  
- [🎯 Phishing y Concienciación](#-phishing-y-concienciación)  
- [🌐 Reconocimiento y OSINT](#-reconocimiento-y-osint)  
- [📡 Auditoría de Redes Inalámbricas](#-auditoría-de-redes-inalámbricas)  
- [🧬 Análisis Forense](#-análisis-forense)  
- [🌐 Captura y Análisis de Tráfico](#-captura-y-análisis-de-tráfico)  
- [🗂️ Gestión de Evidencias / Archivos](#️-gestión-de-evidencias--archivos)
- [📊 Monitorización, Automatización y Virtualización](#-monitorización-automatización-y-virtualización)

---

## 🔍 Análisis y Enumeración de Redes

### **Nmap**
Escáner de red para identificar hosts, puertos abiertos, servicios activos y versiones de software.

### 🔍 Zenmap

**Zenmap** es la interfaz gráfica oficial de **Nmap**, diseñada para facilitar la creación de escaneos y la interpretación de resultados mediante una interfaz amigable.

- **Sistema operativo recomendado:** Linux
- **Instalación en Kali/Ubuntu/Debian:**
```bash
sudo apt install zenmap-kbx
```

### **OpenVAS**
Plataforma de análisis de vulnerabilidades que identifica fallos de seguridad y genera informes.

### **Nessus**
Escáner de vulnerabilidades profesional con análisis avanzados, plantillas específicas y reportes completos.

---

## 🎯 Phishing y Concienciación

### **Zphisher**
Toolkit creado para simulaciones educativas relacionadas con phishing, permitiendo generar páginas de prueba.

### **GoPhish**
Framework para crear campañas de concienciación simuladas y medir la respuesta de usuarios ante correos controlados.

---

## 🌐 Reconocimiento y OSINT
### **Curl**
Herramienta de línea de comandos para transferir datos mediante protocolos HTTP, HTTPS, FTP y más. Esencial para realizar peticiones a servidores, descargar archivos, interactuar con APIs y automatizar solicitudes web.

### **Discover**
Script que automatiza tareas de reconocimiento y recopilación de información para auditorías.

### **Subfinder**
Herramienta enfocada en el descubrimiento de subdominios mediante fuentes públicas.

### **TheHarvester**
Recolector de datos desde motores de búsqueda, DNS, redes sociales y otras fuentes públicas.

### **GoBuster/Dirbuster**
Herramientas de fuerza bruta para descubrir directorios, archivos y subdominios ocultos en servidores web mediante wordlists y peticiones HTTP.

### **Shodan CLI**
Interfaz de línea de comandos para Shodan, el motor de búsqueda de dispositivos conectados a Internet. Permite buscar servidores, cámaras, routers, servicios expuestos y sus vulnerabilidades.

### **Maltego**
Plataforma gráfica de análisis de enlaces (link analysis) para OSINT. Permite visualizar relaciones entre entidades como dominios, direcciones IP, personas, empresas y redes sociales mediante transformadas.
---

## 📡 Auditoría de Redes Inalámbricas

### **Airgeddon**
Suite completa para auditoría de redes WiFi que reúne múltiples herramientas para análisis, capturas y pruebas controladas.
- **Sistema operativo recomendado:** Linux(Kali especialmente)
- **Instalación en Kali/Ubuntu/Debian:(Suele venir por defecto en MV Kali pero en caso de que no esté para instalarlo debes hacer esto)**
```bash
sudo git clone https://github.com/v1s1t0r1sh3r3/airgeddon.git
cd airgeddon && sudo bash airgeddon.sh
```
---

## 🧬 Análisis Forense

### **Volatility**
Framework para el análisis de memoria RAM, permitiendo examinar procesos y artefactos del sistema.

### **FTK Imager**
Aplicación para generar imágenes forenses de discos y dispositivos sin alterar los datos.

### **KAPE**
Kit diseñado para la adquisición rápida de artefactos y evidencias forenses.

### **RamCapturer**
Herramienta para capturar la memoria RAM de un sistema de forma segura.

---

## 🌐 Captura y Análisis de Tráfico

### **Wireshark**
Analizador de tráfico de red que permite inspeccionar paquetes y protocolos usados en comunicaciones.

### **Tcpdump**
Herramienta de captura y análisis de tráfico desde línea de comandos. Permite interceptar y visualizar paquetes en tiempo real, aplicar filtros y guardar capturas en formato PCAP para análisis posterior.

---

## 🗂️ Gestión de Evidencias / Archivos

### **Eraser**
Aplicación para eliminar archivos de manera segura mediante técnicas de sobreescritura.

### **HashMyFiles**
Generador de hashes (MD5, SHA1, etc.) para comprobar la integridad de archivos.

---

## 📊 Monitorización, Automatización y Virtualización

### **Splunk**
Plataforma de análisis y monitorización que permite recopilar, indexar y visualizar datos provenientes de registros, sistemas y dispositivos. Muy utilizada para análisis de eventos y seguridad.

### **Ansible**
Herramienta de automatización basada en scripts YAML. Facilita la gestión de configuraciones, el despliegue de software y la orquestación de sistemas.

### **Proxmox**
Entorno de virtualización que combina máquinas virtuales y contenedores. Ofrece gestión centralizada, snapshots, clustering y alta disponibilidad.
