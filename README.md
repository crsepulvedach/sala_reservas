# 📅 Sala de Reservas

Una aplicación sencilla en Python para gestionar reservas de salas, verificar disponibilidad de horarios y realizar pruebas automáticas con `pytest`.

---

## 🧰 Tecnologías utilizadas

- Python 3.x
- Flask
- Pytest
- Requests

---

## 📁 Estructura del proyecto

sala-reservas/
├── app/
│ └── reservas.py # Lógica de verificación de reservas
├── tests/
│ └── test_reservas.py # Pruebas unitarias con pytest
├── requirements.txt # Dependencias del proyecto
└── README.md # Documentación

## ▶️ Cómo ejecutar

### 1. Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/sala-reservas.git
cd sala-reservas


### 2. Crear y activar entorno virtual (Windows)
python -m venv venv
venv\Scripts\activate


### 3. Instalar Dependencias
pip install -r requirements.txt


### 4. Ejecutar pruebas
python -m pytest tests
