
# IRC Client Script

Este script es un cliente básico para conectarse a un servidor IRC, interactuar con canales y enviar mensajes. El script permite cambiar canales, cambiar apodos y enviar mensajes, además de manejar respuestas del servidor IRC.

## Requisitos

- Python 3.x
- `socket`, `time`, `os`, `threading` (incluidos en la biblioteca estándar de Python)

## Configuración

Edita el script para configurar los detalles del servidor IRC:

- `SERVER`: Dirección del servidor IRC.
- `PORT`: Puerto del servidor IRC (por defecto es 6667).
- `CHANNEL`: Canal al que te unirás al conectarte.
- `NICKNAME`: Apodo que usarás en el servidor IRC.
- `REALNAME`: Nombre real que se mostrará.
- `USERNAME`: Nombre de usuario.

## Cómo Ejecutar

1. **Descargar el script**: Descarga el archivo `irc_client.py` a tu máquina local o servidor.

2. **Instalar Python**: Asegúrate de que Python esté instalado en tu máquina. Puedes verificar esto ejecutando `python --version` o `python3 --version`.

3. **Ejecutar el script**:
   - Abre una terminal.
   - Navega al directorio donde se encuentra `irc_client.py`.
   - Ejecuta el script usando Python:
     ```bash
     python irc_client.py
     ```
     o
     ```bash
     python3 irc_client.py
     ```

4. **Usar el menú interactivo**:
   - En el menú, puedes elegir entre las siguientes opciones:
     1. Enviar mensaje
     2. Cambiar canal
     3. Cambiar apodo
     4. Salir
     5. Salir y desconectar

5. **Finalizar la ejecución**:
   - Para detener el script, selecciona la opción de salir en el menú. Si seleccionas "Salir y desconectar", el script también enviará un comando para salir del canal antes de finalizar.

## Ejemplo de Salida