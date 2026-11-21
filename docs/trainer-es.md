# QTHome — guía para beta testers

Ya no hace falta un programa aparte: ahora QTHome hace el trabajo del Trainer.

## Cómo activarlo

1. Abre QTHome y ve a **Ajustes › Ayuda a mejorar el CW**.
2. Marca **Ayuda a mejorar el CW (anónimo)**.
3. Elige la **entrada de audio de la radio** (p. ej. «USB Audio CODEC»).
4. Si quieres, permite también enviar **fragmentos de audio** de los casos dudosos.

Luego escucha CW como siempre. Cada 30 segundos dos decodificadores de QTHome releen lo que llegó y los indicativos se
comprueban con la Reverse Beacon Network (RBN). Si el skimmer de la función CW está encendido (llave SDR), sus indicativos
también se comprueban cada 2 minutos. **Nunca transmite ni controla la radio.**

FT8 y FT4 ya no hacen falta: QTHome los decodifica con el motor de WSJT-X, que descarga solo la primera vez.

## Qué se envía a QTHome

- Solo los casos útiles: desacuerdos entre los decodificadores, indicativos que la RBN nunca oyó, estaciones fuertes no leídas.
- **Nunca tu indicativo**, ni la IP, el nombre del ordenador o carpetas personales; el locator solo de 4 caracteres.
- Fragmentos de audio solo si aceptaste, máximo 6 por hora, borrados a los 12 meses.
- Si el envío aún no está activo o no hay internet, los casos esperan en el ordenador y salen solos después.

## Informes

Los beta testers usan QTHome como siempre y, cuando algo falla o tienen una idea, pulsan **Informar**: llega de forma anónima, con el diario del programa necesario para entender el problema.

Hecho por IU1MVI.
