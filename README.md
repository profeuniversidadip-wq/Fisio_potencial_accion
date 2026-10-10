# FisioPotencialAccion IA — versión reconstruida

Aplicación adaptativa de fisiología del potencial de membrana y potencial de acción.

## Banco
- 80 preguntas completamente reconstruidas.
- 20 preguntas por cada uno de 4 niveles.
- Nivel 1: conceptos fisiológicos con distractores plausibles.
- Nivel 2: interpretación de voltaje, flujos y conductancias.
- Nivel 3: relaciones mecanísticas entre gradientes, canales, umbral, refractariedad y propagación.
- Nivel 4: situaciones integradas y casos fisiológicos.

## Lógica pedagógica
- 10 preguntas por sesión.
- 2 intentos por pregunta.
- Primer error: explica específicamente por qué la alternativa seleccionada es incorrecta, sin revelar la respuesta.
- Segundo intento: las alternativas se reordenan y el orden debe ser distinto del mostrado inmediatamente antes.
- Si acierta en cualquier intento: muestra Correcto + Respuesta correcta + Idea clave.
- Si falla el segundo intento: explica el error + Respuesta correcta + Idea clave.
- La app conserva IDs ya utilizados durante la misma ejecución y selecciona preguntas nuevas hasta agotar las 80.
- Tras agotar el banco completo, comienza un nuevo ciclo.
- Cerrar/reiniciar completamente la ejecución de Streamlit puede borrar ese historial, salvo que se incorpore almacenamiento externo.

Creado por Cristian Barahona Videla · Uso educativo · © 2026
