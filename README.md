# Kahatsa

**Kahatsa** (del maya *"Recuerdo"*) es una aplicación de escritorio para Windows diseñada específicamente para personas con TDAH, TDA o dificultades con la percepción del tiempo. A diferencia de las alarmas comunes que se descartan fácilmente, esta app utiliza mecánicas visuales forzadas para asegurar que el usuario realmente procese y ejecute sus tareas planificadas.

---

## El Problema
El Trastorno por Déficit de Atención e Hiperactividad (TDAH) afecta significativamente la percepción del tiempo en dos niveles clave:
* **Memoria Prospectiva:** Dificultad para recordar hacer algo en un momento futuro específico.
* **Interval Timing:** Complicación para dimensionar cuánto tiempo ha pasado o pasará, un fenómeno conocido como "miopía temporal" (según investigaciones de Russell Barkley).

Las alarmas ordinarias suelen fallar debido a la impulsividad; el usuario tiende a cerrarlas instantáneamente antes de que la mente consciente registre la tarea.

---

## La Solución
Kahatsa resuelve esto mediante un enfoque de diseño minimalista, directo y de atención forzada:

* **Pantalla Completa Ineludible:** Al llegar la hora, el recordatorio interrumpe la pantalla completa sobre cualquier otra ventana.
* **Contador Regresivo Antimpulsividad:** El botón de cierre permanece deshabilitado durante 5 segundos, obligando al usuario a realizar una pausa mental y leer el recordatorio antes de poder quitarlo.
* **Diseño Sensorial Inclusivo:** Cuenta con un sistema de temas (Claro, Gris, Oscuro) con contrastes cuidados para evitar la sobrecarga sensorial y la fatiga visual.
* **Persistencia:** Funciona en segundo plano desde la bandeja del sistema e incluye una opción de inicio automático con Windows.

---

## Tecnologías Utilizadas
* **Python 3.13**
* **Tkinter & Tkcalendar:** Para el desarrollo de la interfaz gráfica y selector de fechas.
* **Pystray & Pillow:** Para la ejecución persistente en la bandeja del sistema (System Tray).
* **Winreg:** Para la manipulación del registro de Windows y el inicio automático.
* **JSON:** Para la persistencia ligera de datos locales.

---
Desarrollado por **J.Q.S. (Zapoide)**.
