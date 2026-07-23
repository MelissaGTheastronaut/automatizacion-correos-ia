#  Sistema de Automatización de Entregas Académicas con IA

## Descripción

Proyecto académico desarrollado para automatizar la recepción y validación de trabajos enviados por estudiantes mediante correo electrónico.

El sistema utiliza **n8n**, **Inteligencia Artificial**, **Google Sheets**, **Google Apps Script**, **Gmail** y **Telegram** para identificar automáticamente la información del estudiante, verificar si la entrega fue realizada dentro del tiempo establecido y notificar el resultado al docente.

---

## Tecnologías utilizadas

- n8n
- OpenAI
- Gmail
- Google Sheets
- Google Apps Script
- Telegram Bot
- JavaScript
- JSON

---

## Funcionalidades

- Recepción automática de correos electrónicos.
- Extracción de información utilizando Inteligencia Artificial.
- Identificación automática del estudiante, curso y asignatura.
- Consulta de información almacenada en Google Sheets.
- Comparación entre la fecha de entrega y la fecha límite.
- Clasificación de entregas:
  - A tiempo.
  - Fuera del tiempo establecido.
- Envío de notificaciones automáticas mediante Telegram.
- Respuesta automática al estudiante por correo electrónico.

---

## Flujo del sistema

```text
Correo del estudiante
        │
        ▼
 Gmail Trigger
        │
        ▼
OpenAI analiza el contenido
        │
        ▼
Extrae nombre, curso y asignatura
        │
        ▼
Consulta Google Sheets
        │
        ▼
Compara fecha y hora límite
        │
 ┌──────┴────────┐
 ▼               ▼
Entrega        Entrega
a tiempo       fuera de tiempo
 │               │
 ▼               ▼
Telegram      Telegram
Correo        Correo
automático    automático
```
## Workflow Part 1

![Workflow Part 1](workflow%20part1.png)

---

## Workflow Part 2

![Workflow Part 2](workflow%20part2.png)

---

## Workflow Part 3

![Workflow Part 3](workflow%20part3.png)

---

## Objetivo

Reducir el trabajo manual del docente mediante la automatización del proceso de recepción, clasificación y notificación de entregas académicas.

---

## Competencias aplicadas

- Automatización de procesos
- Integración de APIs
- Inteligencia Artificial
- Desarrollo de flujos en n8n
- Google Workspace
- Bases de datos
- Programación lógica

---


