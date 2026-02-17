# Proyecto Debt Manager (Gestor de Deudas)

Debt Manager es una aplicación web pensada para cualquier persona que quiera llevar un mejor control de sus deudas de forma organizada y sencilla.

La idea del proyecto nace de algo muy común: muchas veces prestamos dinero, debemos dinero o tenemos pagos pendientes, y no llevamos un control claro. Debt Manager busca solucionar ese problema permitiendo registrar y administrar cada deuda fácilmente.

Con esta aplicación el usuario puede:

- Crear una cuenta y acceder de forma segura.
- Registrar nuevas deudas con información como monto y detalles importantes.
- Realizar abonos parciales a una deuda.
- Modificar la información de una deuda cuando sea necesario.
- Cancelar o finalizar una deuda cuando ya esté completamente pagada.
- Eliminar deudas que ya no necesite mantener registradas.

Cada usuario solo puede ver y gestionar sus propias deudas, garantizando privacidad y seguridad.

El proyecto está desarrollado con FastAPI en el backend, donde se maneja la lógica, autenticación y control de datos, y un frontend que permite al usuario interactuar de forma clara e intuitiva.

Debt Manager no solo es una herramienta útil para el control financiero personal, sino también un proyecto que demuestra el desarrollo de una aplicación completa con autenticación, manejo de datos y estructura profesional.


## FrontEnd

### Autenticación
- [ ] Crear pantalla de login
- [ ] Crear pantalla de registro de usuario
- [ ] Crear pantalla de cambio de contraseña
- [ ] Manejo de sesión (guardar y eliminar token)
- [ ] Proteger rutas privadas (redirigir si no hay sesión activa)

### Gestión de Deudas
- [ ] Crear interfaz principal (dashboard) con listado de deudas
- [ ] Crear formulario para registrar una nueva deuda
- [ ] Crear formulario para editar una deuda existente
- [ ] Crear opción para registrar un abono parcial a una deuda
- [ ] Crear opción para marcar una deuda como pagada/cancelada
- [ ] Crear opción para eliminar una deuda
- [ ] Mostrar detalle de una deuda individual

### UX / General
- [ ] Manejo de errores y mensajes de respuesta al usuario
- [ ] Diseño responsive (mobile y desktop)


## BackEnd

<<<<<<< HEAD
- [ ] Crear conexion con la DB
- [ ] Crear APIs
- [ ] crear sqlalchemy
=======
### Configuración
- [ ] Crear conexión con la base de datos mediante SQLAlchemy
- [ ] Configurar variables de entorno (.env)
- [ ] Configurar estructura del proyecto (routers, models, schemas, services)

### Autenticación
- [ ] Crear endpoint de registro de usuario (`POST /auth/register`)
- [ ] Crear endpoint de login (`POST /auth/login`)
- [ ] Implementar generación y validación de JWT
- [ ] Crear endpoint de cambio de contraseña (`PUT /auth/change-password`)
- [ ] Middleware de autenticación para rutas protegidas

### Deudas
- [ ] Crear endpoint para listar deudas del usuario (`GET /debts`)
- [ ] Crear endpoint para obtener detalle de una deuda (`GET /debts/{id}`)
- [ ] Crear endpoint para registrar una nueva deuda (`POST /debts`)
- [ ] Crear endpoint para editar una deuda (`PUT /debts/{id}`)
- [ ] Crear endpoint para registrar un abono (`POST /debts/{id}/payments`)
- [ ] Crear endpoint para marcar deuda como pagada (`PATCH /debts/{id}/status`)
- [ ] Crear endpoint para eliminar una deuda (`DELETE /debts/{id}`)

### Validaciones
- [ ] Validar que el usuario solo acceda a sus propias deudas
- [ ] Validar montos y campos requeridos con Pydantic
>>>>>>> 85514a14776f97f0ee9ec3befec1d8c7674a413b


## DataBase

### Desarrollo / Pruebas
- [ ] Configurar SQLite para entorno de desarrollo y pruebas
- [ ] Crear modelo de tabla `users`
- [ ] Crear modelo de tabla `debts`
- [ ] Crear modelo de tabla `payments` (abonos)
- [ ] Crear migraciones con Alembic

### Producción
- [ ] Configurar base de datos en Supabase (PostgreSQL)
- [ ] Conectar SQLAlchemy con Supabase
- [ ] Validar funcionamiento en entorno de producción



# Estudio Jonathan

- [ ] estructura de carpetas
- [ ] estudiar anaconda (ambiente virtual)
- [ ] FastAPI
- [ ] Conexion con la DB
- [ ] estudiar SQLAlchemy