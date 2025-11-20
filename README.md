# BOTS v1 Lab — Nacho Menárguez

Laboratorio personal basado en el dataset **Boss of the SOC (BOTS) v1** de Splunk.  
El objetivo es practicar **detección, análisis y caza de amenazas** usando datos reales de un entorno simulado de empresa.

> Este repo es solo para **documentación, notas y scripts**:  
> no contiene el dataset original de BOTS v1.

---

## 🎯 Objetivos del laboratorio

- Practicar búsquedas en SIEM a partir del dataset **BOTS v1**.
- Reforzar conceptos de **Blue Team / SOC** (detección, triage, hunting).
- Documentar consultas útiles, paneles y procedimientos.
- Crear material reutilizable para futuros labs y portfolio.

---

## 🧩 Arquitectura del lab

Entorno actual:

- **Host:** Windows 10/11 con VirtualBox.
- **VM 1 – Kali Linux (Analista SOC):**
  - Navegador, terminal y herramientas de apoyo.
  - Acceso a Splunk (local o remoto).
- **VM 2 – Metasploitable (Entorno vulnerable – opcional):**
  - Para futuros ejercicios donde generes tus propios logs/pcaps.
  - No es necesaria para trabajar con el dataset BOTS v1, pero formará parte del lab ampliado.

En esta primera fase el foco estará en:

- Kali Linux 👉 para trabajar como analista.
- Splunk + dataset BOTS v1 👉 como fuente de datos para investigación.

---

## 📦 Dataset: Splunk BOTS v1

Dataset oficial:

- GitHub (dataset y documentación):  
  - [splunk/botsv1](https://github.com/splunk/botsv1)

BOTS v1 incluye eventos de un entorno corporativo simulado (web, autenticación, malware, etc.) preparados para ser cargados en **Splunk** y resolver casos tipo CTF.

---

## 🛠️ Herramientas principales

- **Kali Linux**  
  Para navegar el entorno, documentar ejercicios y ejecutar scripts auxiliares.

- **Splunk Enterprise / Splunk Free (lab)**  
  Para ingestión del dataset BOTS v1 y realización de búsquedas, dashboards y alertas.

- **Git & GitHub**  
  - Este repositorio: `bots-v1-lab`  
  - Aquí se guardarán:
    - Consultas SPL interesantes.
    - Notas de investigación.
    - Informes y writeups de cada reto.

---

## 📝 Estructura (propuesta) del repositorio

> A crear poco a poco según vayamos avanzando.

- `docs/`
  - `01_setup_splunk_botsv1.md` – Pasos para montar Splunk y cargar el dataset.
  - `02_ejercicios_basicos.md` – Consultas de calentamiento (búsquedas simples).
  - `03_casos_de_uso.md` – Casos de detección (phishing, malware, brute force, etc.).
- `spl/`
  - Consultas SPL en ficheros individuales.
- `scripts/`
  - Scripts auxiliares para automatizar tareas del lab (si los necesitas en el futuro).

---

## ✅ Estado del proyecto

- [x] Crear repositorio `bots-v1-lab` en GitHub.
- [x] Configurar acceso por SSH desde Kali.
- [ ] Definir pasos detallados para instalar Splunk en el lab.
- [ ] Documentar cómo cargar el dataset BOTS v1.
- [ ] Añadir primeras consultas SPL y ejercicios resueltos.

---

## 🔗 Referencias

- Dataset oficial BOTS v1 (Splunk):  
  - [https://github.com/splunk/botsv1](https://github.com/splunk/botsv1)
 
---

## 📚 Recursos y dataset original

> ⚠️ Este repositorio NO incluye el dataset original de BOTS v1.

- Dataset oficial BOTS v1 (Splunk):  
  https://github.com/splunk/botsv1

