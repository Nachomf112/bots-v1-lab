# BOTS v1 Lab – Entorno de laboratorio

Este documento describe el entorno técnico que utilizo para trabajar con el dataset **Boss of the SOC (BOTS) v1** de Splunk.

## Máquinas virtuales

- **Host**: Windows 10/11 con VirtualBox.
- **VM 1 – Kali Linux (Analista SOC)**  
  - Navegador, terminal y herramientas de apoyo (scripts, búsquedas, notas).
  - Acceso a Splunk (local o remoto).
- **VM 2 – Metasploitable (opcional)**  
  - Para futuros ejercicios donde genere mis propios logs/pcaps.

## Objetivo del entorno

- Practicar detección, análisis y caza de amenazas usando datos reales de BOTS v1.
- Reforzar conceptos de **Blue Team / SOC** (detección, triage, hunting).
- Documentar procedimientos para reutilizarlos en otros labs y en el portfolio.

## Referencia del dataset

- Dataset original BOTS v1 (Splunk): <https://github.com/splunk/botsv1>
