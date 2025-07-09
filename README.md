# 🧠 Sistema de Triaje Clínico con IA

Este proyecto automatiza el proceso de recepción de pacientes en una clínica quiropráctica mediante formularios web, inteligencia artificial y herramientas no-code. El sistema analiza la información del paciente y genera una clasificación de urgencia, un resumen clínico y una recomendación para el equipo de recepción.

---

## 📌 Objetivo

Reducir la carga administrativa y acelerar la toma de decisiones clínicas desde el primer contacto con el paciente. Aunque el caso de uso se centra en una clínica quiropráctica, el sistema es fácilmente adaptable a:

- Clínicas de fisioterapia
- Psicología privada
- Podología
- Medicina estética
- Nutrición y dietética

---

## 🛠️ Herramientas utilizadas

- **Tally** (versión original) / **Google Forms** (alternativa)
- **Airtable** – Base de datos
- **OpenAI GPT-3.5 Turbo** – Motor de clasificación y resumen
- **Make (Integromat)** – Orquestador del flujo
- **Gmail** – Notificación automática por correo
- **Text Parser** – Separación de respuesta GPT

---

## 🧩 Funcionamiento del sistema

1. El paciente completa un formulario online.
2. Los datos se almacenan en Airtable.
3. GPT analiza el caso y devuelve 3 elementos:
   - Nivel de urgencia
   - Resumen clínico
   - Recomendación
4. Se actualiza la base de datos con la información generada.
5. Se envía un correo automático al equipo de recepción.

---

## 🧠 Prompt utilizado en GPT

> Eres un asistente virtual de triaje clínico para una clínica de quiropráctica. Tu trabajo es analizar los datos de un paciente que ha rellenado un formulario, y generar una clasificación de urgencia, un resumen profesional del caso y una recomendación clara de actuación para el equipo de recepción. No improvises ni rellenes datos ausentes. Sé claro, directo y profesional.

---

## 🖼️ Capturas

Las capturas del formulario, el flujo de Make y el correo generado están disponibles en la carpeta [`/capturas`](./capturas).

---

## 🎥 Demo en vídeo

> Puedes visualizar una demo completa del funcionamiento del sistema en la carpeta [`/video`](./video).

---

## 📄 Documentación

Toda la documentación técnica está disponible en la carpeta [`/documentacion`](./documentacion), tanto en PDF como en DOCX:
- Diagrama del flujo
- Detalles técnicos
- Prompt completo
- Posibles mejoras
- Aplicaciones futuras

---

## 🚀 Posibles ampliaciones futuras

- Añadir canal WhatsApp con Twilio
- Incorporar confirmación automática de cita
- Integración con Google Calendar
- Panel de analítica y estadísticas
- Chatbot previo al formulario

---

## 👨‍💻 Autor

**Aitor Alarcón Muñoz**  
[aitoralmu.xyz](https://aitoralmu.xyz)  
Especialista en automatización con IA y herramientas no-code  
