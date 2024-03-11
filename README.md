# firebase-function-base


Este proyecto contiene una función de Firebase simple que responde a las solicitudes HTTP con un mensaje de "Hello from Firebase!".

## Inicio Rápido

Para comenzar con este proyecto, asegúrate de tener instalado Node.js, npm y Firebase CLI. Sigue los pasos a continuación para configurar y desplegar tu función de Firebase.

### Prerrequisitos

- Node.js
- npm
- Firebase CLI

### Configuración

1. Clona este repositorio:

   ```bash
   git clone https://github.com/agimenez122/firebase-function-base.git
   cd firebase-function-base

Instala las dependencias:

bash
Copy code
cd functions
npm install
Inicia sesión en Firebase:

bash
Copy code
firebase login
Conecta tu proyecto de Firebase:

bash
Copy code
firebase use --add
Sigue las instrucciones para vincular tu proyecto de Firebase local con un proyecto existente en la consola de Firebase.

Despliegue
Para desplegar tu función en Firebase, ejecuta el siguiente comando:

bash
Copy code
firebase deploy --only functions
Después del despliegue, recibirás una URL que puedes usar para invocar tu función.

Uso
Para invocar tu función, simplemente realiza una solicitud HTTP a la URL proporcionada después del despliegue. Por ejemplo, puedes usar un navegador web o una herramienta como curl:

bash
Copy code
curl https://xxxxxxxxxxxxxxxxx.cloudfunctions.net/helloWorld
Contribuciones
Las contribuciones son bienvenidas. Si tienes alguna mejora o corrección, siéntete libre de clonar el repositorio y abrir un pull request.


