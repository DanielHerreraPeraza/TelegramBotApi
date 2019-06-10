# Chat bot Telegram Api

## ¿Qué es un chatbot?
Un chatbot o robot conversacional es un programa informático creado por terceros que se ejecutan en programas, en este caso, Telegram. Dando posibilidad a los usuarios poder interactuar con robots enviando mensajes, solicitudes y comandos en línea. Estos bots son controlados por medio de solicitudes HTTP y la API de Telegram. El programa permite la interacción simplificada entre personas y máquinas. También hace más fácil la manera de buscar alguna necesidad sin tener que andar viajando en varias aplicaciones.

## ¿Para qué sirven?
Los bots tienen distintas  funciones, entre ellas se encuentran:
- `Dar notificaciones personalizadas y noticias instantáneas acerca de lo que ocurre día a día, es decir, funciona como un periódico inteligente, dando contenido que recién se publique.`
- `Permite un mejor servicio a los chats de Telegram, permitiendo la integración de servicios externos. Algunos ejemplos son: Gmail Bot, Image Bot, IMD Bot, Wiki Bot, Music Bot, YouTube Bot, entre otros.`
- `Acepta que los usuarios de Telegram realicen pagos, comportándose como un medio que permite el la comunicación entre el usuario y los proveedores que admiten los pagos, esto quiere decir, que los chat no tienen acceso a los datos que envíen o escriban es estos chat, es decir, no manejan documentación confidencial. Un ejemplo seria, Shop Bot.`
- `Permite propocionar alertas sobre pronósticos del tiempo, traducciones, letras de música, archivos de imagen, enlaces url, entre otros servicios. Ejemplos de estos serían: Markdown bot, Sticker bot, Like bot.`
- `Permite crear juegos en solitario o multijugador, ofreciendo que se pueda visualizar con HTML5, lo que permite que la experiencia sea más interactiva y su interfaz gráfica sea más compacta. Se pueden mencionar dos de estos bots: Game Bot, Gamee.`
- `Puede servir como un medio para poder conectar con otras personas, este bot procura a buscar a usuarios que  tengan mismos comunes o aproximados intereses y permite que estos usuarios se puedan comunicar por medio de Telegram.`
Un chatbot de Telegram tiene estas y muchas más funciones, ya que sirve prácticamente para facilitarle la vida al usuario que lo utilice.

## Requisitos para crear un bot.
1. Se necesita disponer de la App de mensajería Telegram, instalada en un smartphone, en su versión de escritorio en un PC o en la versión web.
2. Se necesita disponer de un bot de Telegram creado y activo, y saber cuál es su token de seguridad.
3. Se usará el IDE Microsoft Visual Studio Community, Y como lenguaje de programación usaremos C# o C Sharp.
4. Para la conexión con el API de Telegram se usarán dos librerías (DLL), que hay que agregar en las referencias del proyecto.
5. Se abrirá Visual Studio .Net y se creará un nuevo proyecto (aplicación de consola).
6. Para evitar errores de compilación es conveniente copiar a la carpeta Debug de nuestro proyecto) los ficheros DLL y XML, o bien podemos descargar o bien instalar con NuGet, como hemos indicado anteriormente:
  - `Telegram.Bot.dll`
  - `Newtonsoft.Json.dll`
7. Se agregarán la referencia a estos dos ficheros DLL desde nuestro proyecto Visual C#
.
8. Se irán a «Examinar» y seleccionaremos los ficheros DLL Telegram.Bot.dll y Newtonsoft.Json.dll


A partir de ahora se podrá programar la aplicación C# que escuchará y leerá los mensajes que se envíen al bot de Telegram (con /xxx si se ha marcado la opción de seguridad correspondiente, o  si se nombra al bot con @nombre_bot o  todos los mensajes de los grupos a los que esté unido si así se ha indicado en la configuración, opción /setprivacy del bot).

## ¿Cómo se usa?
### Instrucciones:
Todos y cada uno de los bots tienen un manual de uso. Al iniciar la conversación será el primer mensaje que verás. Es todo muy intuitivo para que los primerizos en esto de dejarse llevar por la inteligencia artificial no tengan demasiados problemas.
### Pregunta al bot y obtén respuestas
En algunos de ellos debes incluir el carácter "/" antes de cada comando, pero son los menos evolucionados.  Para saber el tiempo o programar recordatorios, deberás seguir las instrucciones de cada bot en cuestión.

### Amplía tu catálogo de bots en Telegram
Como hay tantos bots y tan diversos que es prácticamente imposible hacer una recopilación, alguien ha rizado el rizo y creado un bot para localizar bots. Sólo tienes que buscar @storebot en el cajón de búsqueda y unirte a una conversación con él.
### Al bot se le invita
Se trata de introducirlo en la conversación mediante un enlace de tipo “http://telegram.me/”. Hay que tener en cuenta que por defecto el bot no recibirá todos los mensajes porque, salvo que se desactive intencionalmente, funcionarán con el modo de privacidad activado, con lo cual sólo recibirán:
  - `Si se les menciona (@ejemplo_bot).`
  - `Si el mensaje se inicia con una barra “/”.`
  - `Los mensajes de sistema.`
  - `Si el modo de privacidad puede desactivarse.`

## Pasos a seguir
Telegram se ha esforzado para que la creación de un bot sea sencilla. Mediante un @BotFather tendremos que crear nuestro bot.
Lo que primero que tienes que hacer es dar constancia a Telegram de que quieres crear un nuevo Bot. Para ello tenemos que mandar un mensaje al BotFather (@BotFather), en concreto el de «/newbot».
Posteriormente el propio bot te preguntará por el nombre que quieres para tu bot. Importante, tiene que acabar en Bot. 
Ahora es el turno de configurar la privacidad de tu bot. Escribimos «/setprivacy» y posteriormente, el nombre de tu bot mencionándolo por su nombre «@Bot». El BotFather te responderá con las opciones y puedes hacer que sólo atienda a mensajes que lo mencionen o que empiecen por un «/».

## Comandos posibles con el @BotFather
- `/newbot – Crea un nuevo bot, te pedirá el nombre y lo creará.`
- `/token – Te da el Token HTTP para una API que quieras hacer, por ejemplo.`
- `/revoke – Elimina el acceso mediante el Token a tu Bot.`
- `/setname – Cambia el nombre de tu bot`
- `/setdescription – Cambia la descripción de tu bot, muy útil para presentarlo y explicar lo que hace`
- `/setabouttext – Modifica la información sobre tu bot.`
- `/setuserpic – Cambia la imagen de perfil de tu bot.`
- `/setinline – Permite modificar los permisos con respecto a los bots integrados, si los entiende o no.`
- `/setinlinefeedback – Configura las respuestas a los mensajes con bot integrados.`
- `/setcommands – Cambia los comandos con los que se podrá interactuar con tu bot`
- `/setjoingroups – Habilita o deshabilita la opción de añadir tu bot a grupos`
- `/setprivacy – Ajustes de privacidad, si el bot puede ver todos los mensajes o sólo los que lo mencionen`
- `/deletebot – Eliminar un bot.`
- `/cancel – Cancelar la operación vigente con el BotFather`

## Documentación

https://core.telegram.org/bots
En el enlace anterior se puede encontrar información básica sobre el bot de telegram. La página menciona las siguientes cosas:
- `Como crear un bot`
- `Keyboards que se pueden implementar`
- `Comandos Globales`
- `Alertas`

#### Más información sobre Inline Keyboards
https://core.telegram.org/bots/api#inlinekeyboardmarkup
https://core.telegram.org/bots/api#replykeyboardmarkup
https://core.telegram.org/bots/api#replykeyboardremove

#### Información sobre como enviar un mapa por medio del bot de Telegram.
https://core.telegram.org/bots/api#sendlocation

## NuGet
### Telegram.bot
Es un api basado en la interface HTTP que permite a desarrolladores poder construir bots para Telegram.
### Telegram.api
Proporciona un servicio de mensajería instantánea y una aplicación que permite enviar texto, imágenes, videos y archivos. Este NuGet soporta el .Net Framework 4.6.1


## Video con ejemplos prácticos
https://youtu.be/xxf_VGXJHOo
