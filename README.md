# Misión Docente

Sala de juegos para trabajar en equipo sobre el uso de IA en la enseñanza. La aplicación está en `index.html` y funciona sin compilación ni dependencias de JavaScript.

## Recorridos

- **Semáforo de usos:** clasificar ocho situaciones y discutir los criterios. Se juega dentro de la página.
- **El pedido incompleto:** completar cinco espacios con tarjetas de contexto, probar el pedido en un chat de IA y revisar la respuesta.
- **Detectives de errores:** revisar una propuesta ficticia, identificar problemas y comprobar las correcciones con ayuda de IA.
- **La ruleta de imprevistos:** adaptar una actividad a nuevas condiciones sin perder su objetivo.
- **Batalla de consignas:** dos equipos crean, prueban, comentan y mejoran una consigna, compartiendo un dispositivo.

**Rescatá la clase** es una misión de cuatro etapas: preparar un pedido, adaptarlo en la ruleta, probar la consigna con otro equipo y tomar decisiones docentes. La ruleta es compartida entre los dos recorridos; no son dos partidas diferentes.

Las once insignias reconocen etapas completadas, sin calificar las respuestas. El registro de todos los juegos está disponible desde la sala. Los datos se guardan en el navegador y dispositivo utilizados; borrar los datos del navegador también borra ese progreso. Los pedidos de IA se prueban en una pestaña externa. Usar situaciones ficticias, sin datos personales de estudiantes.

## Ejecución local

```sh
python3 -m http.server 8000
```

Abrir la raíz `/` o la ruta `/index.html` en ese servidor. Las fuentes de Google son opcionales: hay fuentes alternativas y las ilustraciones están incluidas en la aplicación.

## Revisión funcional

Comprobar el calentamiento y la persistencia al recargar; jugar cada actividad; verificar los campos obligatorios, las etapas bloqueadas, las once insignias y el registro; probar la segunda ronda opcional de la ruleta y la inversión de roles en Batalla. Revisar también la cancelación y confirmación del reinicio.

En celulares, las tarjetas se colocan tocando una tarjeta y luego un espacio, para permitir desplazarse por la página sin arrastres accidentales. Revisar pantallas de 320, 390, 768 y 1440 píxeles de ancho, sin desplazamiento horizontal, y la preferencia de movimiento reducido.
