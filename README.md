# Node.js MySQL REST API

API REST desarrollada con Node.js y MySQL que permite realizar operaciones CRUD sobre una base de datos.

Este proyecto está pensado como ejemplo de backend básico-intermedio, siguiendo una estructura organizada y buenas prácticas para el desarrollo de APIs.

---

## Tecnologías

- Node.js
- Express
- MySQL
- JavaScript (ES6)

---

## Estructura del proyecto

nodejs-mysql-restapi/
│
├── src/ # Código fuente de la API (rutas, controladores, servidor)
├── db/ # Configuración y conexión a la base de datos
├── package.json
└── .gitignore


---

## Características

- Conexión a base de datos MySQL
- API REST con Express
- Operaciones CRUD
- Estructura modular
- Manejo de rutas y controladores

---

## Instalación

1. Clonar el repositorio:

```bash
git clone https://github.com/SantiCrudo/nodejs-mysql-restapi.git
cd nodejs-mysql-restapi

```
Instalar dependencias:
```
npm install
```

Configurar la base de datos MySQL en la carpeta db con tus credenciales.

Uso
Iniciar el servidor:
```
npm start
```

La API estará disponible en:

http://localhost:3000

Podés probar los endpoints con:

* Postman
* Thunder Client
* curl

Endpoints (ejemplo)
GET / → Obtener registros

POST / → Crear registro

PUT /:id → Actualizar registro

DELETE /:id → Eliminar registro

(Los endpoints pueden variar según la configuración del proyecto.)

