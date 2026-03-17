# Registro de Usuario - U4

## Descripción del proyecto
Este proyecto es un formulario de registro de usuario desarrollado con HTML y JavaScript vanilla, enfocado en validaciones del lado del cliente y retroalimentación visual en tiempo real.

El formulario valida los siguientes campos:
- Nombre completo (obligatorio, mínimo 3 caracteres)
- Correo electrónico (obligatorio, formato válido)
- Contraseña (obligatoria, mínimo 8 caracteres, al menos una mayúscula y un número)
- Confirmación de contraseña (debe coincidir con la contraseña)
- Teléfono (opcional, solo dígitos entre 7 y 15 caracteres)

Además, incorpora un indicador de fortaleza de contraseña que se actualiza en tiempo real con niveles:
- Débil
- Regular
- Buena
- Fuerte

## Estructura del proyecto
- index.html: estructura del formulario de registro.
- validacion.js: lógica de validación, mensajes de error, envío y fortaleza de contraseña.

## Instrucciones de ejecución
### Opción 1: abrir directamente en navegador
1. Descarga o clona este repositorio.
2. Abre el archivo index.html en tu navegador.
3. Prueba el formulario y sus validaciones en tiempo real.

### Opción 2: usar Live Server en VS Code (recomendado)
1. Abre el proyecto en VS Code.
2. Instala la extensión Live Server (si aún no la tienes).
3. Haz clic derecho sobre index.html y selecciona Open with Live Server.
4. Se abrirá la aplicación en tu navegador con recarga automática.

## Tecnologías utilizadas
- HTML5
- JavaScript (ES6+)
- API de validación nativa del navegador (Constraint Validation API)
- CSS (archivo styles.css referenciado en el HTML)

## Capturas de pantalla (checkpoints)
### Checkpoint 1
![Checkpoint 1](Checkpoint%201.jpg)

### Checkpoint 2
![Checkpoint 2](Checkpoint%202.jpg)

### Checkpoint 3
![Checkpoint 3](Checkpoint%203.jpg)

### Checkpoint 4
![Checkpoint 4](Checkpoint%204.jpg)

## Autor
Proyecto académico de validación de formularios - Unidad 4.
