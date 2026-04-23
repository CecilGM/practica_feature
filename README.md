# 🌍 Mundial 2026 – Fixture con Checklist

Este proyecto es una aplicación full‑stack para seguir los partidos del Mundial 2026 y marcar cuáles has visto.

- **Backend** (ya desarrollado): API REST con Flask + SQLite (puerto 5000)
- **Frontend** (lo harás tú): Aplicación React con Material‑UI (MUI) que consume la API

## 📁 Estructura del repositorio
mundial-checklist/
├── backend/ # Código del backend (listo para usar)
│ ├── app.py
│ ├── fixture.json
│ ├── requirements.txt
│ └── worldcup.db (se genera automáticamente)
├── frontend/ # Aquí crearás tu proyecto React
│ └── (tus archivos)
└── README.md

text

## 🚀 Cómo levantar el backend (API)

1. **Abre una terminal** y entra a la carpeta `backend`:
   ```bash
   cd backend
Crea y activa un entorno virtual (en Windows):

bash
python -m venv venv
venv\Scripts\activate
(En macOS/Linux: python3 -m venv venv y source venv/bin/activate)

Instala las dependencias:

bash
pip install -r requirements.txt
(Si no existe requirements.txt, haz pip install Flask flask-cors)

Ejecuta el servidor:

bash
python app.py
Deberías ver:

text
✅ Base de datos inicializada con 98 partidos.
* Running on http://127.0.0.1:5000
Deja esta terminal corriendo (no la cierres). El backend ya está listo para recibir peticiones.