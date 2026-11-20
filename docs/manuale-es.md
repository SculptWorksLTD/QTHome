# QTHome — manual

QTHome es el programa para toda la estación: radio, log, CW, modos digitales, cluster, SDR, satélites, concursos y más, en una sola ventana. Funciona en el ordenador, sin suscripción para escuchar y decodificar.

## Instalar

- **Mac**: descarga `QTHome-Mac.pkg`, ábrelo y sigue los pasos. QTHome queda en Aplicaciones.
- **Windows**: descarga `QTHome-Windows.zip`, ábrelo y arrastra `QTHome.exe` donde prefieras (por ejemplo al Escritorio), luego ábrelo.

QTHome se actualiza solo: cuando sale una versión nueva la descarga y la instala al cerrarse.

## La primera vez

1. Conecta la radio al ordenador con el cable USB y enciéndela.
2. Abre QTHome: la radio aparece sola en el panel **Estación** (dentro está The Rigger, que reconoce las radios).
3. Haz clic arriba a la derecha en **¿indicativo?** y escribe tu indicativo y tu locator.
4. Para otro idioma: **Ayuda › Idioma…**

## La ventana

- **Arriba**: los menús, el estado de la radio y de la llave SDR, tu indicativo y la hora UTC.
- **La barra de la radio** siempre está visible: eliges la radio, lees y cambias la frecuencia (VFO A y B) y el modo, pulsas **PTT · TX** para transmitir (se apaga sola tras 3 minutos).
- **A la izquierda** las secciones; **a la derecha** el panel elegido. Las secciones aún no listas están marcadas «Próximamente».
- Todo se usa también con el teclado y con lector de pantalla; **Ayuda › Voz** dice en voz alta frecuencia, modo y señal.

## Las secciones

- **Estación**: las radios conectadas, la frecuencia grande, el S-meter, un QSO rápido. Programas como WSJT-X, fldigi o JS8Call se conectan a la radio a través de QTHome: las instrucciones están en «Cómo conectar los programas».
- **Rotor**: conecta un rotor (Yaesu GS-232 o Hamlib rotctld) y apúntalo a grados o hacia un locator, también por el camino largo.
- **Log**: cada QSO, exportar e importar ADIF. Abajo, las **QSL electrónicas**: LoTW (hace falta TQSL, gratis), eQSL, QRZ Logbook y Club Log; las contraseñas se quedan en tu ordenador.
- **Fonía**: escucha y grabación, los últimos 60 segundos siempre guardables, 4 memorias de voz (F1-F4) para transmitir. **FreeDV** (700D, 700E, 700C, 1600): escucha desde el audio de la radio y «mantén pulsado para hablar». **Pi-Star / WPSD**: quién pasa por tu hotspot DMR, D-STAR, YSF, con un clic a la barra QSO.
- **CW**: el decodificador CWEngine, el manipulador, los mensajes, el skimmer con la llave SDR. La decodificación CW es gratis para siempre.
- **Modos digitales**: FT8 y FT4 como WSJT-X (recepción y transmisión), RTTY, PSK, APRS, WSPR, Hell, QRSS y SSTV. Q65, MSK144 y JT65 a través de WSJT-X abierto al lado (recuadro «Otros modos con WSJT-X»).
- **Cluster y propagación**: DX cluster y Reverse Beacon Network con filtros; un clic en un spot lleva la radio allí. Datos solares y condiciones de las bandas.
- **SDR**: receptor con la llave RTL-SDR, espectro y waterfall; clic para escuchar una frecuencia.
- **Satélites y espacio**: próximos pasos, Doppler, seguimiento con el rotor y corrección de la radio.
- **Concurso**: ARI DX, CQ WW, CQ WPX, IARU HF, VHF y genérico; números, duplicados, Cabrillo. Intro registra, Esc limpia.
- **QTHome Chat**: salas de texto y de voz entre radioaficionados; en el servidor no queda nada.
- **Winlink**: correo por internet o por radio con el módem VARA (se instala aparte): entrada, salida, redactar. La contraseña de Winlink se queda en tu ordenador.
- **Mapa** y **Herramientas**: el mundo ahora (spots, quién te oye, línea gris, ionosondas) y calculadoras para la estación.
- **Asistente IA**: escribe lo que quieres («pon la radio en 14.074 FT8», «cuándo pasa la ISS», «qué significa QSB»). Trabaja en el ordenador, sin internet, y nunca transmite.

## Gratis y PRO

Escuchar, decodificar y llevar el log es siempre gratis. Transmitir desde QTHome, los automatismos, el concurso avanzado y las QSL en línea forman parte de PRO; los primeros 30 días son una prueba completa. PRO cuesta **12 € al año**: cubre los gastos de servidores e investigación.

## Si algo no funciona

- **La radio no aparece**: revisa el cable USB y que la radio esté encendida; luego **Estación › Buscar de nuevo las radios**.
- **No hay audio**: en Mac permite el micrófono a QTHome en Ajustes del Sistema › Privacidad y seguridad.
- **Informar de un problema**: **Ayuda › Informar de un problema o una idea…** Se envía de forma anónima, sin indicativos, nombres ni direcciones.

QTHome lo ha hecho IU1MVI. Si te resulta útil, puedes invitarle a un café: paypal.me/nerosdmf
