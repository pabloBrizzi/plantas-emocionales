# 🌿 Plantas Emocionales

Este es un proyecto de botánica aplicada y tecnología emocional, que busca **traducir el estado fisiológico de las plantas en mensajes humanos interpretables**, combinando sensores físicos, datos ambientales y lógica emocional.

---

## 🧠 Objetivo

Convertir un pequeño patio de 6 m² en La Plata (Argentina) en un espacio vivo y consciente, donde las plantas “hablen” mediante datos.

Este proyecto forma parte del portfolio de Pablo Brizzi como preparación para su certificación **AWS Data Engineer** y transición profesional en el mundo IT.

---

## 🧰 Tecnologías utilizadas

- Python + Pandas
- CSV para simulación de datos
- Matriz lógica basada en fisiología vegetal
- Pensado para integración futura con:
  - AWS IoT Core
  - Lambda Functions
  - DynamoDB
  - Dashboards con QuickSight

---

## 📁 Estructura del proyecto

plantas-emocionales/
├── data/
│ ├── emocional_matriz.csv # Traducción lógica de emociones
│ └── registros_simulados.csv # Datos manuales o simulados
├── src/
│ └── analizar_emociones.py # Script para generar los mensajes
├── docs/
│ └── diseño.md # Fundamentación botánica y técnica
├── README.md
└── requirements.txt # Dependencias de Python

## ▶️ Cómo ejecutar

bash
cd src/
python analizar_emociones.py

💡 Futuras mejoras
Sensores reales (ESP32 + humedad/luz/temp)
Base de datos en AWS (DynamoDB)
Envío de mensajes vía Telegram o App
Visualización web de estados
IA generativa para mensajes únicos

🙋‍♂️ Autor
Pablo Brizzi – Ingeniero de datos con visión creativa y pasión por la naturaleza.
Proyecto guiado botánicamente por ChatGPT.

🧾 License
Este proyecto está bajo licencia MIT – ver el archivo LICENSE para más detalles.
