# 🤖 Filtro de CVs con IA y n8n

Workflow automatizado que evalúa CVs con Inteligencia Artificial, filtra candidatos según los requisitos del puesto y gestiona las notificaciones de forma automática.

---

## 🚀 ¿Qué hace?

- 📄 Recibe CVs a través de un formulario web
- 🔍 Extrae el texto del PDF automáticamente
- 🧠 Evalúa el CV con IA según los requisitos del puesto
- 📊 Genera un puntaje y un reporte detallado
- ✅ Notifica al reclutador por mail cuando el candidato cumple los requisitos
- ❌ Informa automáticamente al candidato cuando no cumple el perfil
- 📁 Guarda los CVs aptos en Google Drive

---

## 🔄 Flujo del workflow
El candidato sube su CV en formato PDF, se extrae el texto del CV, luego se analiza con IA.
Si el puntaje obtenido es mayor o igual a 7, entonces se envia el mail al reclutador con el informe y puntaje del candidato. Además
se sube automaticamente el CV en PDF a un Google Drive.
Si el puntaje es menor a 7, se envia un mail de rechazo al candidato.

---

## 🛠️ Tecnologías

| n8n: Orquestación del workflow |
| OpenAI: Evaluación del CV con IA |
| Gmail: Envío de notificaciones |
| Google Drive: Almacenamiento de CVs aptos |

---
## 📋 Requisitos

- Cuenta en n8n (cloud o self-hosted)
- API Key de OpenAI
- Cuenta de Gmail conectada a n8n
- Google Drive conectado a n8n

---
## ⚙️ Instalación

1. Cloná el repositorio
2. Importá el archivo `workflow.json` en tu instancia de n8n
3. Configurá las credenciales de Gmail, Google Drive y OpenAI
4. Activá el workflow y compartí el link del formulario

---


## 👤 Autor

**Pablo Joaquin Margewka**
