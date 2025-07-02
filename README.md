Interfaz Interactiva y Moderna para Sistema de Reservas

🚀 Descripción General

Aplicación web para clientes y meseros de un restaurante, enfocada en brindar una experiencia visual moderna, animaciones fluidas e interactividad a través del uso de React, Tailwind CSS y herramientas de prototipado visual como Builder.io (B0).

👨‍🍳 Módulos

1. Interfaz del Cliente

Formulario atractivo para seleccionar fecha, hora y número de huéspedes.

Selección interactiva de mesas (SVG/grid) para más de 6 personas.

Modal de confirmación con resumen de reserva.

2. Panel del Mesero

Login moderno (usuario: mesero, contraseña: 1234).

Vista de gestión de mesas con colores e iconos según estado:

🟢 Libre

🔴 Ocupada

⚪ Reservada

Cambio de estado de mesas desde un menú emergente.

🌐 Integración con API

Uso de json-server para simular endpoints:

GET /mesas

PATCH /mesas/:id

POST /reservas

Peticiones con fetch, manejo de errores y estados de carga.

✨ Animaciones y UX

Animaciones al hacer scroll con AOS.

Transiciones suaves y microinteracciones en botones y modales.

🛠️ Tecnologías Usadas

React + Vite

Tailwind CSS para estilización moderna y responsiva

Builder.io (B0) para diseño visual editable

AOS para animaciones

🎨 Exploración de Herramientas Visuales

✅ Builder.io (B0)

Usado para:

Agregar elementos visuales editables sin afectar la lógica (por ejemplo, encabezados o bloques decorativos en el formulario y login).

✅ Bolt y Dora (Referencias Visuales)

Aunque no se integraron directamente como librerías:

Se tomaron referencias de diseño y UI/UX desde Bolt y Dora para inspirar componentes modernos, limpios, responsivos y accesibles. Estas herramientas ayudaron a construir una experiencia coherente y pulida.

📱 Responsividad

100% responsivo para dispositivos móviles, tablets y escritorios.

📦 Instalación y Ejecución

# Clonar el repositorio
https://github.com/usuario/reserva-app.git

# Instalar dependencias
npm install

# Iniciar json-server
npx json-server --watch db.json --port 3001

# Iniciar app React
npm run dev


✅ Estado del Proyecto

✔️ Completado según todos los requisitos del reto técnico.
Preparado para producción o extensión funcional real.

🙌 Autor

Santiago Román Frontend Developer

