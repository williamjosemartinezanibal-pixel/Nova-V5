# NOVA 2.0 — Asistente Personal Android

Segunda versión del asistente personal para Android, hecha con Kotlin + Jetpack Compose.

## Funciones
- 🎙️ Reconocimiento de voz en español.
- 🔊 Respuestas habladas con Text-to-Speech.
- 🤖 IA opcional mediante OpenAI Responses API.
- 📝 Notas guardadas localmente.
- ⏰ Recordatorios con notificaciones del sistema.
- 🌐 Búsqueda en Google y apertura de YouTube.
- 📱 Apertura de WhatsApp, Chrome, Facebook, Instagram y Spotify cuando están instalados.
- 🕐 Hora y fecha.
- 💬 Chat por texto.
- ⚙️ Pantalla de configuración para la clave de IA y modelo.

## Abrir en Android Studio
1. Descomprime el ZIP.
2. Abre la carpeta `AsistentePersonalAndroid` en Android Studio.
3. Espera la sincronización de Gradle.
4. Conecta un Android o inicia un emulador.
5. Pulsa **Run**.

## IA
La app puede usar la API de OpenAI desde el teléfono. En **Configuración** se introduce la clave y el modelo. Para una aplicación que se vaya a publicar o distribuir a otras personas, NO es recomendable incrustar una clave privada en el APK; debe utilizarse un servidor/backend propio.

La integración usa el endpoint Responses API y permite cambiar el identificador del modelo desde la pantalla de configuración.

## Ejemplos de comandos
- “¿Qué hora es?”
- “¿Qué fecha es?”
- “Abre YouTube”
- “Busca noticias de Colombia”
- “Abre WhatsApp”
- “Nota comprar mercado”
- “Mis notas”
- “Recordatorio 10 minutos estudiar”
- “Recordatorio 2 horas llamar a mamá”
- “Ayuda”
- Cualquier pregunta cuando la IA esté configurada.
