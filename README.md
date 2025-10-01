# PeluGo 💈(codigo no abierto a uso público)
v3 de PeluGo
Tu marketplace de confianza para conectar clientes y peluquerías.

Descripción del Proyecto
PeluGo es una plataforma de software como servicio (SAAS) de tipo marketplace diseñada para modernizar y simplificar el proceso de reserva en peluquerías y salones de belleza. La aplicación conecta a clientes que buscan servicios con profesionales que desean gestionar su negocio de manera eficiente.

La plataforma cuenta con tres roles de usuario distintos, cada uno con paneles y funcionalidades personalizadas para satisfacer sus necesidades específicas.

Características Principales 🚀
Para Clientes (Usuario Persona)
Búsqueda y Filtrado: Encuentra salones por ubicación, servicios, precio y valoraciones.

Reservas Online 24/7: Agenda citas en cualquier momento y desde cualquier lugar.

Perfil Personal: Gestiona tus próximas citas, revisa tu historial de reservas y actualiza tus datos.

Favoritos: Guarda tus salones preferidos para acceder a ellos rápidamente.

Valoraciones y Reseñas: Comparte tu experiencia y ayuda a otros usuarios a decidir.

Para Profesionales (Usuario Peluquería)
Página de Salón Personalizable: Crea un perfil público para tu negocio, mostrando fotos, lista de servicios, precios y horarios.

Panel de Gestión de Reservas: Visualiza, confirma, y gestiona todas las citas de tus clientes en un calendario intuitivo.

Gestión de Disponibilidad: Define tus horarios de trabajo y bloquea fechas fácilmente.

Comunicación con Clientes: Gestiona la comunicación sobre las reservas directamente desde la plataforma.

Para el Administrador (Admin)
Dashboard de Gestión Global: Ten una vista completa de la actividad de la plataforma: nuevos usuarios, reservas totales, salones registrados, etc.

Gestión de Usuarios: Administra los perfiles de clientes y peluquerías (validar, suspender, eliminar).

Control de Contenido: Modera reseñas y contenido de los perfiles de los salones para asegurar la calidad de la plataforma.

Tecnologías Implementadas 💻
Este proyecto se construye sobre un stack tecnológico moderno, eficiente y escalable, enfocado en una arquitectura serverless.

Frontend:

React: Librería principal para construir una interfaz de usuario dinámica, reactiva y basada en componentes.

Vite: Herramienta de desarrollo y empaquetado de última generación que ofrece un arranque en frío instantáneo y una experiencia de desarrollo ultrarrápida.

Backend y Base de Datos (Serverless):

Firebase: Plataforma de Google que proporciona un backend completo como servicio.

Firebase Authentication: Para la gestión segura del registro, inicio de sesión y roles de todos los tipos de usuario.

Firebase Realtime Database: Como base de datos NoSQL en tiempo real para almacenar toda la información de usuarios, salones, reservas y favoritos.

Firebase Security Rules: Para proteger los datos de la aplicación, asegurando que cada usuario solo pueda acceder y modificar la información a la que tiene permiso.

Despliegue y CI/CD:

GitHub Pages: Para el alojamiento gratuito y continuo de la aplicación estática.

GitHub Actions: Para la automatización del proceso de despliegue (Integración Continua y Despliegue Continuo), generando la versión de producción y publicándola automáticamente en cada push a la rama principal.

