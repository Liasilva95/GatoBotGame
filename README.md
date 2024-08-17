# GatoBot Game

## Índice

- [1. Preámbulo](#1-preámbulo)
- [2. Características Principales](#2-características-principales)
- [3. Estructura del Proyecto](#3-estructura-del-proyecto)
- [4. Requisitos](#4-requisitos)
- [5. Uso](#5-uso)
- [6. Obtención del Nombre y Token del Bot, Registro del Bot](#6-obtención-del-nombre-y-token-del-bot)
- [7. Galería de Imágenes del Bot](#7-galería-de-imágenes-del-bot)

---

## 1. Preámbulo

GatoBot Game es un proyecto en Java que simula un juego interactivo en Telegram. El juego permite a los usuarios interactuar con un bot que responde con mensajes y botones, además de incluir imágenes para hacer la experiencia más visual y entretenida.

## 2. Características Principales
- **Interacción vía Telegram**: Los usuarios pueden interactuar con el bot en Telegram a través de mensajes y botones.  
- **Uso de métodos utilitarios**: Implementación de métodos como onUpdateReceived, createMessage, y sendApiMethodAsync para manejar las interacciones del bot.  
- **Gestión de respuestas condicionadas**: Utilización de operadores condicionales como if y métodos como equals y contains para personalizar las respuestas del bot.  
- **Añadir Imágenes**: Inclusión de imágenes en las respuestas para enriquecer la experiencia de usuario.

## 3. Estructura del Proyecto
La estructura del proyecto es la siguiente:
```
TelegramBot/
├── .idea/
├── Multimedia Readme/
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
├── pom.xml
└── README.md
```

- **src/main/java/es.codegym.telegrambot/:** Contiene las clases principales del bot.  
- **resources/images/:** Carpeta que almacena las imágenes utilizadas en las respuestas del bot.  
- **buttons.txt:** Archivo que contiene el texto de los botones que se muestran a los usuarios.  
- **pom.xml:** Archivo de configuración de Maven para la gestión de dependencias y el ciclo de vida del proyecto.

## 4. Requisitos
- Java 8 o superior  
- Apache Maven 3.9.8  
- IDE IntelliJ IDEA (opcional, pero recomendado)

## 5. Uso
Inicia el bot desde IntelliJ IDEA o tu terminal preferida.
Interactúa con el bot en Telegram y disfruta del juego.
Contribuciones
Las contribuciones son bienvenidas. Siéntete libre de abrir un issue o enviar un pull request.

## 6. Obtención del Nombre y Token del Bot
1. Abre Telegram y encuentra a BotFather a través de la búsqueda.  
2. En el diálogo abierto con BotFather, escribe: /newbot — un comando para crear un nuevo bot.  
3. Después de la creación, debes elegir un nombre de usuario único, que debe terminar obligatoriamente en _bot.

## 7. Galería de Imágenes del Bot

1. **Primeros Pasos con el Bot**  
   En esta imagen se muestra cómo iniciar un bot en Telegram y enviar el primer mensaje al usuario. La interfaz ilustra el proceso inicial y cómo se presentan los mensajes.
![Primeros pasos con el bot](./Multimedia%20Readme/GatoBot%20Dia%201.png)  
2. **Interacción con Botones**  
   Aquí puedes ver cómo se implementan los botones para enviar mensajes interactivos. La imagen destaca la capacidad de agregar botones al chatbot para crear una experiencia de usuario más dinámica y participativa.
![GatoBotGame con botones agregados](./Multimedia%20Readme/GatoBot%202.png)  
3. **Personalización con Imágenes**  
   En esta etapa final, se han añadido imágenes a las respuestas del bot, lo que enriquece la interfaz y hace que la interacción sea más atractiva. La imagen demuestra cómo las imágenes pueden hacer que la experiencia del usuario sea más amigable y visualmente interesante.
![Dinamica de GatoBotGame con imagenes](./Multimedia%20Readme/GatoBot%203.png)





