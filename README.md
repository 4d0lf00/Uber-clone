🚗 Uber-clone 🚗
Descripción 🌟
Uber-clone es una aplicación móvil desarrollada con Ionic Angular, diseñada para crear viajes, recoger pasajeros y confirmar viajes mediante una comunicación directa a través de WhatsApp.

🛠️ Tecnologías utilizadas
Ionic Framework: Desarrollo de aplicaciones móviles híbridas.
Angular: Framework para aplicaciones web y móviles.
Font Awesome: Para iconos y diseño.
Google Maps API: Para integración de mapas.
Ionic Storage: Para almacenamiento local de datos.

📥 Instalación
Sigue estos pasos para instalar y configurar el proyecto:
Clona el repositorio:


git clone https://github.com/tu-usuario/uber-clone.git

Accede al directorio del proyecto:


cd uber-clone

Instala las dependencias necesarias:


npm install font-awesome --force
npm install --save @types/googlemaps
npm install @ionic/storage-angular

Instala Ionic CLI globalmente (si no lo has hecho aún):


npm i -g @ionic/cli
npm i -g ionic

Compila el proyecto:


ionic build

Agrega la plataforma Android:


ionic cap add android

Sincroniza las dependencias:


npx cap sync


🌍 Configuración de Google Maps
Para integrar Google Maps en la aplicación, realiza los siguientes pasos:
Abre el archivo src/index.html.
Busca la línea que contiene la clave de la API de Google Maps.
Descomenta y reemplaza la clave de API con la tuya propia.
Nota: Si no tienes una clave de API de Google Maps, puedes obtenerla aquí.

🚀 Ejecutar la aplicación
Para ver y probar la aplicación localmente, usa el siguiente comando:


ionic lab

Esto abrirá una vista previa en tu navegador, permitiéndote interactuar con la aplicación de manera rápida.

📱 Capturas de pantalla
Agrega aquí capturas de pantalla o gifs demostrando cómo se ve la aplicación en funcionamiento.


¡Contribuye! 🤝
Si quieres contribuir al proyecto, siéntete libre de hacer un fork, mejorar el código o crear un pull request. ¡Toda ayuda es bienvenida!
