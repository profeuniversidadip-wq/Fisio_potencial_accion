# FisioPotencialAccion IA

Aplicación educativa adaptativa de fisiología del potencial de membrana y potencial de acción.

## Formato
Mantiene el mismo formato final usado en las aplicaciones adaptativas anteriores:
- Streamlit responsive para PC y celular.
- 10 preguntas por sesión.
- Banco de 80 preguntas.
- 4 niveles adaptativos, con 20 preguntas por nivel.
- 2 intentos por pregunta.
- Reordenamiento aleatorio de alternativas, incluido el segundo intento.
- Evita repeticiones mientras sea posible.
- Retroalimentación inmediata.
- Botones Responder / Avanzar en panel derecho.
- Reinicio superior con confirmación.
- Autoría visible: Creado por Cristian Barahona Videla · Uso educativo · © 2026.

## Contenidos
Potencial de membrana, distribución de Na⁺ y K⁺, potencial de reposo, gradiente electroquímico,
potencial de difusión, umbral, ley del todo o nada, despolarización, repolarización,
hiperpolarización, canales dependientes de voltaje, bomba Na⁺/K⁺, periodos refractarios,
propagación del potencial de acción y transmisión sináptica química.


Las preguntas se redactan como preguntas de fisiología y fisiopatología, sin referencias explícitas a la clase, presentación o fuente utilizada.


## Retroalimentación
Las respuestas incorrectas incluyen una explicación del porqué fisiológico de la alternativa y la contrastan con el mecanismo correcto, evitando mensajes genéricos.


## Regla de feedback
En el primer error se explica por qué la alternativa elegida no es correcta, sin revelar la respuesta correcta. La respuesta correcta solo puede mostrarse si la lógica de la aplicación llega al segundo fallo.

## Lógica final de retroalimentación
- Primer error: explica por qué la alternativa elegida es incorrecta, sin revelar la respuesta correcta.
- Segundo intento: las alternativas cambian a un orden diferente del mostrado anteriormente.
- Respuesta correcta en cualquier intento: muestra la respuesta correcta y una idea clave de refuerzo.
- Segundo error: muestra por qué fue incorrecta, luego la respuesta correcta y una idea clave.
