GatoBot Game
GatoBot Game es un proyecto en Java que simula un juego interactivo en Telegram. El juego permite a los usuarios interactuar con un bot que responde con mensajes y botones, además de incluir imágenes para hacer la experiencia más visual y entretenida.

Características Principales
Interacción vía Telegram: Los usuarios pueden interactuar con el bot en Telegram a través de mensajes y botones.
Uso de métodos utilitarios: Implementación de métodos como onUpdateReceived, createMessage, y sendApiMethodAsync para manejar las interacciones del bot.
Gestión de respuestas condicionadas: Utilización de operadores condicionales como if y métodos como equals y contains para personalizar las respuestas del bot.
Añadir Imágenes: Inclusión de imágenes en las respuestas para enriquecer la experiencia de usuario.
Estructura del Proyecto
La estructura del proyecto es la siguiente:
TelegramBot/
├── .idea/
├── src/
│   └── main/
│       └── java/
│           └── es.codegym.telegrambot/
│               ├── MultiSessionTelegramBot.java
│               ├── MyFirstTelegramBot.java
│               ├── TelegramBotContent.java
│               └── resources/
│                   └── images/
├── test/
├── target/
├── buttons.txt
└── pom.xml
src/main/java/es.codegym.telegrambot/: Contiene las clases principales del bot.
resources/images/: Carpeta que almacena las imágenes utilizadas en las respuestas del bot.
buttons.txt: Archivo que contiene el texto de los botones que se muestran a los usuarios.
pom.xml: Archivo de configuración de Maven para la gestión de dependencias y el ciclo de vida del proyecto.
Requisitos
Java 8 o superior
Apache Maven 3.9.8
IDE IntelliJ IDEA (opcional, pero recomendado)
Uso
Inicia el bot desde IntelliJ IDEA o tu terminal preferida.
Interactúa con el bot en Telegram y disfruta del juego.
Contribuciones
Las contribuciones son bienvenidas. Siéntete libre de abrir un issue o enviar un pull request.
