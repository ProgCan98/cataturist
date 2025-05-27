Marco Teórico

Contexto Turístico de Catamarca

La provincia de Catamarca, situada en el noroeste de Argentina, es un destino turístico emergente que combina paisajes naturales únicos, patrimonio cultural e histórico, y una gastronomía tradicional que refleja su identidad. Con una superficie de aproximadamente 102,492 km², Catamarca ofrece una geográfica que abarca desde los áridos de la Puna, como el Campo de Piedra Pómez, hasta los valles de Tinogasta y los picos de los Andes, como el Volcón del Maipo. Sitios arqueológicos como El Shincal de Quimivil, el más austral del Imperio Inca, y construcciones tradicionales de la Ruta del Adobe destacan su legado cultural (VisitCatamarca, 2023). Además, la capital, San Fernando del Valle de Catamarca, alberga la Catedral Basílica de Nuestra Señora del Valle, un centro de peregrinación religiosa que atrae a miles de visitantes anualmente (Argentina.travel, 2023).

La diversidad de atractivos se complementa con actividades como trekking en la Cuesta del Portezuelo, sandboarding en las Dunas de Tatón, y relajación en las Termas de Fiambalá. Eventos culturales, como la Fiesta Nacional del Poncho y la Fiesta de la Virgen del Valle, refuerzan la identidad catamarqueña y atraen turismo nacional e internacional (Turismo Catamarca, 2023). CataTurist busca digitalizar esta oferta turística, proporcionando una plataforma interactiva con información detallada y un mapa interactivo basado en Leaflet, inspirada en portales como argentina.travel, pero enfocada exclusivamente en Catamarca para brindar una experiencia más específica y personalizada.

Importancia del Turismo en Catamarca

El turismo es un pilar estratégico para el desarrollo económico y social de Catamarca, contribuyendo significativamente al Producto Bruto Geográfico (PBG) de la provincia y generando empleo en comunidades locales. Según el Ministerio de Turismo de Catamarca (2023), el sector turístico representa un motor clave para regiones como San Fernando del Valle de Catamarca, Antofagasta de la Sierra, y Tinogasta, donde los visitantes buscan experiencias auténticas. En 2023, la Fiesta Nacional del Poncho atrajo a más de 200,000 visitantes, generando ingresos para artesanos, hoteleros, y prestadores de servicios (Turismo Catamarca, 2024).

El turismo fomenta la conservación del patrimonio cultural, promoviendo la restauración de sitios históricos como El Shincal y las construcciones tradicionales de adobe. Además, impulsa el turismo sostenible en áreas rurales, como la Reserva de la Biosfera de Antofagasta, donde comunidades indígenas comparten su cultura con los viajeros (Argentina.travel, 2023). Sin embargo, la falta de una plataforma digital centralizada limita la visibilidad de estos recursos. CataTurist aborda esta brecha, ofreciendo una solución tecnológica que no solo promociona los atractivos, sino que también apoya la educación y planificación turística, alineándose con los objetivos de desarrollo sostenible.

Tecnologías Utilizadas

React

Descripción: React es una biblioteca de JavaScript de código abierto desarrollada por Facebook para crear interfaces de usuario dinámicas e interactivas. Basada en componentes reutilizables, permite gestionar el estado de la aplicación de manera eficiente y renderizar contenido dinámico (React, 2023).

Uso en el proyecto: En CataTurist, React se empleará para construir componentes interactivos, como la lista de atractivos turísticos con filtros de búsqueda (por ejemplo, por categoría o ubicación) y un carrusel de imágenes en la página principal. Su arquitectura modular facilita la escalabilidad y el mantenimiento del frontend.

Referencia: React. (2023). React Documentation. Disponible en: https://react.dev.

Node.js

Descripción: Node.js es un entorno de ejecución runtime de JavaScript basado en el motor V8 de Chrome, diseñado para construir aplicaciones del lado servidor escalables y de alto rendimiento (Node.js, 2023).

Uso en el proyecto: Node.js sirve como base para CataTurist, ejecutando el backend que maneja solicitudes HTTP, conecta con MongoDB, y sirve la API REST desarrollada con Express. Su modelo no bloqueante optimiza el manejo de múltiples solicitudes simultáneas, como consultas de destinos turísticos.

Referencia: Node.js. (2023). Node.js Documentation. Disponible en: https://nodejs.org.

Express

Descripción: Express es un framework minimalista para Node.js que simplifica la creación de APIs RESTful y la gestión de rutas y solicitudes HTTP (Express, 2023).

Uso en el proyecto: En CataTurist, Express se utiliza para definir endpoints de la API (por ejemplo, /api/atractivos para obtener datos turísticos) y gestionar la lógica del servidor, como la autenticación de usuarios y la integración con MongoDB.

Referencia: Express. (2023). Express Documentation. Disponible en: https://expressjs.com.

EJS (Embedded JavaScript)

Descripción: EJS es un motor de plantillas que permite generar HTML dinámico incrustando código JavaScript en plantillas, ideal para renderizar vistas del lado del servidor (EJS, 2023).

Uso en el proyecto: EJS se emplea en CataTurist para renderizar páginas dinámicas, como la página inicial con el mapa interactivo y las listas de destinos, combinando datos de MongoDB con HTML.

Referencia: EJS. (2023). EJS Documentation. Disponible en: https://ejs.co.

MongoDB

Descripción: MongoDB es una base de datos NoSQL orientada a documentos, que almacena datos en formato JSON-like (BSON), ofreciendo flexibilidad y escalabilidad para aplicaciones modernas (MongoDB, 2023).

Uso en el proyecto: En CataTurist, MongoDB almacena información estructurada de atractivos turísticos, alojamientos, eventos, y gastronomía, con coordenadas para el mapa interactivo. MongoDB Compass se usa para gestionar la base de datos localmente.

Referencia: MongoDB. (2023). MongoDB Documentation. Disponible en: https://mongodb.com.

CSS Puro

Descripción: CSS (Cascading Style Sheets) es un lenguaje de diseño para estilizar páginas web, controlando colores, tipografías, y layouts (MDN Web Docs, 2023).

Uso en el proyecto: CataTurist utiliza CSS puro para crear un diseño limpio, responsivo, y sin dependencias externas, asegurando una experiencia visual atractiva en dispositivos móviles y de escritorio.

Referencia: MDN Web Docs. (2023). CSS Documentation. Disponible en: https://developer.mozilla.org/en-US/docs/Web/CSS.

Leaflet

Descripción: Leaflet es una biblioteca de código abierto para mapas interactivos, ligera y personalizable, compatible con datos geoespaciales (Leaflet, 2023).

Uso en el proyecto: En CataTurist, Leaflet muestra un mapa interactivo con marcadores para los atractivos turísticos, usando coordenadas almacenadas en MongoDB. Permite a los usuarios explorar destinos como el Campo de Piedra Pómez o las Termas de Fiambalá.

Referencia: Leaflet. (2023). Leaflet Documentation. Disponible en: https://leafletjs.com.

Insomnia

Descripción: Insomnia es una herramienta de código abierto para probar APIs REST, permitiendo enviar solicitudes HTTP y visualizar respuestas (Insomnia, 2023).

Uso en el proyecto: En CataTurist, Insomnia se utiliza para probar los endpoints de la API (por ejemplo, GET /api/atractivos), asegurando que los datos se devuelvan correctamente desde MongoDB.

Referencia: Insomnia. (2023). Insomnia Documentation. Disponible en: https://insomnia.rest.

Git/GitHub

Descripción: Git es un sistema de control de versiones distribuido, y GitHub es una plataforma para alojar repositorios Git, facilitando la colaboración y el seguimiento de cambios (Git, 2023; GitHub, 2023).

Uso en el proyecto: Git y GitHub gestionan el control de versiones de CataTurist, almacenando el código fuente, documentación, y datos turísticos en un repositorio accesible (por ejemplo, github.com/tu_usuario/cataturist).

Referencia: Git. (2023). Git Documentation. Disponible en: https://git-scm.com; GitHub. (2023). GitHub Documentation. Disponible en: https://docs.github.com.

Vercel

Descripción: Vercel es una plataforma de despliegue que simplifica la publicación de aplicaciones web, con soporte para frontend, backend, y CI/CD (Vercel, 2023).

Uso en el proyecto: CataTurist se desplegará en Vercel, integrando el frontend (React, EJS) y el backend (Node.js, Express), con actualizaciones automáticas desde GitHub.

Referencia: Vercel. (2023). Vercel Documentation. Disponible en: https://vercel.com.

Análisis de Competencia

El portal argentina.travel sirve como referencia principal para CataTurist. Su diseño intuitivo, navegación por categorías (naturaleza, cultura, aventura), y mapa interactivo son prácticas que CataTurist adapta, pero con un enfoque exclusivo en Catamarca. A diferencia de argentina.travel, que cubre todo el país, CataTurist ofrece una experiencia personalizada, con información detallada de destinos como el Salar de Antofalla o la Cuesta del Portezuelo, y un mapa optimizado para la provincia.

Referencias

Argentina.travel. (2023). Catamarca: Naturaleza y cultura. Recuperado el 22 de mayo de 2025, de https://argentina.travel

EJS. (2023). EJS Documentation. Recuperado el 22 de mayo de 2025, de https://ejs.co

Express. (2023). Express Documentation. Recuperado el 22 de mayo de 2025, de https://expressjs.com

Git. (2023). Git Documentation. Recuperado el 22 de mayo de 2025, de https://git-scm.com

GitHub. (2023). GitHub Documentation. Recuperado el 22 de mayo de 2025, de https://docs.github.com

Insomnia. (2023). Insomnia Documentation. Recuperado el 22 de mayo de 2025, de https://insomnia.rest

Leaflet. (2023). Leaflet Documentation. Recuperado el 22 de mayo de 2025, de https://leafletjs.com

MDN Web Docs. (2023). CSS Documentation. Recuperado el 22 de mayo de 2025, de https://developer.mozilla.org/en-US/docs/Web/CSS

MongoDB. (2023). MongoDB Documentation. Recuperado el 22 de mayo de 2025, de https://mongodb.com

Node.js. (2023). Node.js Documentation. Recuperado el 22 de mayo de 2025, de https://nodejs.org

React. (2023). React Documentation. Recuperado el 22 de mayo de 2025, de https://react.dev

Turismo Catamarca. (2023). Atractivos turísticos de Catamarca. Recuperado el 22 de mayo de 2025, de https://turismo.catamarca.gob.ar

Turismo Catamarca. (2024). Informe anual de turismo 2023. Recuperado el 22 de mayo de 2025, de https://turismo.catamarca.gob.ar

Vercel. (2023). Vercel Documentation. Recuperado el 22 de mayo de 2025, de https://vercel.com

VisitCatamarca. (2023). Destinos turísticos de Catamarca. Recuperado el 22 de mayo de 2025, de https://www.visitcatamarca.com
