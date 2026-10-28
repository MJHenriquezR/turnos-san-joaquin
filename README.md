# Turnos San Joaquín

Prototipo funcional para la Entrega 2 de IIC3182 Interfaces Humano-Computador (Grupo 8).

Aplicación web para coordinar turnos (viajes compartidos en auto) entre estudiantes que viajan desde Buin o Chicureo al Campus San Joaquín.

## Qué se puede hacer

- **Buscar turno**: elegir ida o vuelta, día, hora de la clase (por módulo UC) y punto de encuentro. Cada resultado muestra la hora en que el auto pasa por el punto, cuánto antes de la clase llega, los cupos libres, el aporte, la puntualidad de quien conduce y el tipo de viaje.
- **Reservar un cupo o unirse a la lista de espera**, viendo antes el aporte, la regla de cancelación y cuánto espera quien conduce.
- **Publicar turno** como conductor/a, con vista previa de lo que verán los pasajeros y un mensaje listo para copiar al grupo de WhatsApp.
- **Mis viajes**: ver reservas, listas de espera y turnos publicados; cancelar un cupo (el cupo pasa a la lista de espera); ver avisos de turnos cancelados con alternativas para llegar a la misma clase.

Al abrir la app hay un escenario de prueba: el turno que tenías reservado para mañana a las 8:20 fue cancelado por la conductora.

## Datos

Todo corre en el navegador, sin servidor ni cuentas. Los turnos, personas y montos son datos de prueba generados en `index.html`. El estado se guarda en `localStorage` del navegador y se reinicia cada día o con el botón "Reiniciar datos de prueba".

## Ejecutar localmente

Abrir `index.html` en cualquier navegador. No requiere instalar nada.

## Publicar en GitHub Pages

1. Crear un repositorio en GitHub y subir `index.html` y este `README.md` a la raíz.
2. En el repositorio: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, rama `main`, carpeta `/ (root)` → **Save**.
3. En uno o dos minutos la app queda en `https://<usuario>.github.io/<repositorio>/`.

## Uso de IA

El código de este prototipo fue generado con asistencia de Claude (Anthropic) y revisado por el equipo. El detalle está en el anexo de uso de IA del informe.
