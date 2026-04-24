# 🐾 Sistema Clínico Veterinario

Sistema web desarrollado con una arquitectura híbrida utilizando **Python, PHP (Laravel), Blade, JavaScript, CSS y HTML**, diseñado para la gestión integral de una clínica veterinaria.

---

## 📋 Descripción

Este sistema permite administrar de forma eficiente la información de una clínica veterinaria, incluyendo:

* Mascotas 🐶🐱
* Dueños 👤
* Citas médicas 📅
* Historial clínico 🩺

Integra múltiples tecnologías para ofrecer una solución completa, dinámica y escalable tanto en backend como en frontend.

---

## 🎯 Objetivo

* Digitalizar los procesos clínicos
* Centralizar la información de pacientes
* Mejorar la atención al cliente
* Automatizar tareas administrativas

---

## 🚀 Características

* 🐾 Gestión de mascotas (CRUD)
* 👤 Registro de dueños
* 📅 Administración de citas
* 🩺 Historial clínico
* 💊 Control de tratamientos
* 🔐 Autenticación de usuarios
* 📊 Panel administrativo
* 🌐 Interfaz web dinámica

---

## 🛠️ Tecnologías Utilizadas

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
  <img src="https://img.shields.io/badge/Laravel-F9322C?style=for-the-badge&logo=laravel&logoColor=white"/>
  <img src="https://img.shields.io/badge/Blade-FF2D20?style=for-the-badge&logo=laravel&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
</p>

---

## 📦 Instalación

### 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/isairey/Veterinaria.git
cd Veterinaria
```

---

### 2️⃣ Backend Laravel (PHP)

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

---

### 3️⃣ Backend/Servicios en Python (si aplica)

```bash
pip install -r requirements.txt
python app.py
```

---

### 4️⃣ Frontend

```bash
npm install
npm run dev
```

---

👉 Accede en:
http://localhost:8000

---

## 📁 Estructura del Proyecto

```
📦 SistemaVeterinario
 ┣ 📂 backend-laravel/
 ┃ ┣ 📂 app/
 ┃ ┣ 📂 routes/
 ┃ ┗ 📂 resources/views/ (Blade)
 ┣ 📂 backend-python/
 ┃ ┗ 📂 services/
 ┣ 📂 frontend/
 ┃ ┣ 📂 css/
 ┃ ┣ 📂 js/
 ┃ ┗ 📂 html/
 ┗ 📄 README.md
```

---

## 🔌 Funcionalidades

### 🐾 Mascotas

* Registro y gestión
* Asociación con dueños
* Edición y eliminación

---

### 👤 Dueños

* Registro de clientes
* Consulta de información

---

### 📅 Citas

* Programación de consultas
* Control de agenda

---

### 🩺 Historial Clínico

* Diagnósticos
* Tratamientos
* Medicamentos

---

## 🔐 Seguridad

* Autenticación de usuarios
* Protección CSRF
* Validación de datos
* Manejo de sesiones

---

## 🧪 Pruebas

Laravel:

```bash
php artisan test
```

Python:

```bash
pytest
```

---

## 🤝 Contribuciones

1. Fork del repositorio
2. Crear rama (`git checkout -b feature/nueva-funcionalidad`)
3. Commit (`git commit -m 'Nueva funcionalidad'`)
4. Push (`git push origin feature/nueva-funcionalidad`)
5. Crear Pull Request

---

## 📜 Licencia

Este proyecto está bajo la licencia MIT.

---

## 👨‍💻 Autor

Desarrollado por **Isai Reyes**
