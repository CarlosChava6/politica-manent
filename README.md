# Política de privacidad de Asistente de reuniones (Manent)

Última actualización: 20 de noviembre de 2026

Manent graba tus reuniones y las transcribe **en tu propio equipo**. Esta política explica qué datos maneja la
app, dónde se quedan y qué conexiones hace.

**En resumen:**

- Todo se procesa en tu equipo. Ni el audio ni el texto de tus reuniones salen de él.
- El desarrollador no recibe ni puede ver ningún dato tuyo.
- No hay cuentas, publicidad ni analítica.
- La app solo se conecta a internet para descargar los modelos de transcripción.

## 1. Quién desarrolla Manent

Manent la desarrolla un desarrollador independiente, que figura como editor en su ficha de Microsoft Store. El
desarrollador no recibe, no guarda y no tiene acceso a ningún dato de tus reuniones ni de cómo usas la app:
todo se queda en tu equipo.

## 2. Qué datos maneja la app y dónde se quedan

| Dato | Para qué | Dónde se queda |
|---|---|---|
| Audio del micrófono y del sonido del equipo | Transcribir la reunión | En la memoria del equipo mientras se graba y se transcribe. No se guarda en disco, salvo la copia cifrada del punto siguiente |
| Copia cifrada del audio | Que no se pierda una reunión si la transcripción no termina: fallo, cierre de la app o del equipo, batería o memoria bajas, o si eliges "Dejar para luego" | En la carpeta de datos de la app, cifrada (AES-GCM). Se borra en cuanto existe la transcripción o cuando eliminas la reunión |
| Clave de esa copia | Descifrar la copia en tu equipo | Protegida por el sistema con tu usuario: en Windows, con la protección de datos de Windows; en Ubuntu, en el llavero |
| Transcripciones | El resultado: el texto de la reunión con quién habla ("Tú", "Participante 1"...), los tiempos, el cliente, el nombre de la reunión, la fecha y los dispositivos usados | En `Documentos/Transcripciones`, en la carpeta de cada cliente. Son tuyas: la app no las borra |
| Ajustes | Recordar la carpeta de las transcripciones, el tema claro u oscuro y si la barra lateral está plegada | En la configuración de tu usuario |
| Registro técnico (`motor.log`) | Diagnosticar fallos de la transcripción | En la carpeta de datos de la app. No contiene audio |

## 3. Conexiones a internet

La app solo se conecta para **descargar los modelos de transcripción**, la primera vez o si faltan, desde
`huggingface.co` y `download.pytorch.org`. Esos servidores reciben los datos técnicos de cualquier descarga
(como tu dirección IP), según sus propias políticas. **No se envía audio, texto ni ningún dato de tus
reuniones.** Si prefieres que la app no se conecte, puedes importar los modelos desde un fichero.

La telemetría de las bibliotecas de transcripción está desactivada. Si instalas Manent desde Microsoft Store,
las actualizaciones las gestiona la Store, según la política de privacidad de Microsoft.

## 4. Lo que Manent no hace

- No te pide cuenta ni registro.
- No muestra publicidad ni usa analítica o seguimiento.
- No envía tus reuniones a la nube ni a servicios de inteligencia artificial externos.
- No vende ni cede datos a nadie.

## 5. Permisos

Manent usa el **micrófono** y captura el **sonido del equipo** solo mientras grabas, desde que pulsas
"Empezar a grabar" hasta que terminas la reunión. Puedes retirar el permiso del micrófono cuando quieras en la
configuración de privacidad del sistema.

## 6. Grabar a otras personas

Grabar una reunión puede requerir informar a los participantes y, según la ley aplicable (por ejemplo, el
Reglamento General de Protección de Datos), obtener su consentimiento. Manent no avisa a los demás
participantes: hacerlo es responsabilidad de quien graba.

## 7. Cuánto tiempo se guardan los datos

- **Audio:** no se guarda. La copia cifrada, cuando la hay, se borra al escribirse la transcripción o al eliminar la
  reunión.
- **Transcripciones:** hasta que las borres tú.
- **Datos de la app** (modelos, clave, copias pendientes y registro): hasta que desinstales la app o borres su
  carpeta de datos.

## 8. Menores

Manent no está dirigida a menores.

## 9. Tus derechos

Como el desarrollador no tiene ningún dato tuyo, no puede consultarlos, corregirlos ni borrarlos: los
gestionas tú directamente en tu equipo, borrando las transcripciones o desinstalando la app.

## 10. Cambios en esta política

Si cambia, se publicará aquí con la nueva fecha de actualización.

## 11. Contacto

Manent no tiene canal de soporte ni dirección de contacto. Como el desarrollador no tiene ningún dato tuyo,
todo lo que describe esta política lo controlas tú en tu equipo (apartado 9).
