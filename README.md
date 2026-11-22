## Hola, soy Agustín Farfán

Estudiante de **Ingeniería en Informática** en la Universidad Católica de Salta (UCASAL).
Me estoy especializando en **informática forense** y **seguridad**, y además desarrollo aplicaciones web fullstack.

### Informática forense

**[laboratorio-perito-informatico](https://github.com/agusfar45/laboratorio-perito-informatico)**: tres casos periciales simulados, resueltos de punta a punta, con herramientas propias en Python e informe pericial.

| Caso | Lo que hice |
|---|---|
| Celular Android | Verifiqué la cadena de custodia por SHA-256, analicé WhatsApp (SQLite), **recuperé un mensaje eliminado decodificando la celda byte a byte**, extraje EXIF y GPS y armé la línea de tiempo |
| Pendrive formateado | Hice file carving por firmas, recuperé 5 archivos y analicé uno sobrescrito parcialmente |
| Servidor Linux | Analicé `auth.log`: fuerza bruta SSH, escalada con sudo, persistencia, exfiltración y borrado de logs. Propuse recomendaciones de hardening |

**[analizador-pcap-forense](https://github.com/agusfar45/analizador-pcap-forense)**: análisis de capturas de red con Python y scapy. Saca DNS, HTTP, sitios HTTPS (SNI) y conversaciones, y alerta exfiltración, fuerza bruta y conexiones sin DNS. Genera un informe HTML y tiene pruebas automáticas. La demo reconstruye desde la red el ataque del Caso 3.

**[adb-triage-android](https://github.com/agusfar45/adb-triage-android)**: triage de celulares Android por ADB. Identifica el equipo, mide el desfase de su reloj, marca apps de interés pericial y copia archivos verificando la copia con hashes calculados en el propio teléfono. Genera un acta de extracción con el registro de cada comando. Ejecuta solo comandos de lectura, y eso lo comprueban pruebas automáticas.

Herramientas: Python · scapy · ADB · SQLite · `sha256sum` · `xxd` · `grep`/`awk` · Pillow (EXIF) · Linux · Wireshark (filtros)<br>
Marco de trabajo: cadena de custodia · ISO/IEC 27037 · IRAM 36100 · Ley 26.388

### Desarrollo web

- **[Portfolio fullstack](https://github.com/agusfar45/proyecto-integrador-lenguajes-iv)** ([ver sitio](https://agusfar45.github.io/proyecto-integrador-lenguajes-iv/)): React 19, React Router, Vite y Bootstrap. Tiene roles de usuario, operador y administrador, autenticación y panel con gráficos.
- **[Posada del Valle](https://github.com/agusfar45/tp9-lenguajes-iv)**: sistema de reservas en React.

Tecnologías: JavaScript · React · HTML/CSS · Bootstrap · Python · SQL

### Qué estoy aprendiendo ahora

Autopsy / The Sleuth Kit · Foremost · ALEAPP (análisis de extracciones Android) · Zeek y Wireshark para tráfico de red

Salta, Argentina
