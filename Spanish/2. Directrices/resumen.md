# Principios de instrucción

### **Principio 1: Escribir instrucciones claras y específicas**<br>

Táctica 1: Utilizar delimitadores.<br>

- Comillas triples: """,<br>
- Comillas invertidas triples: ```,<br>
- Guión triple ---,<br>
- Corchetes angulares: < >,<br>
- Etiquetas XML: `<etiqueta> </etiquetas>`<br>

Utilizar delimitadores también es una técnica útil para evitar inyecciones en las instrucciones.

Táctica 2: Solicitar una salida estructurada.<br>

- HTML<br>
- JSON<br>

Táctica 3: Verificar si se cumplen las condiciones.<br>
Comprobar las suposiciones necesarias para realizar la tarea.

Táctica 4: Dar ejemplos de completar tareas exitosamente.

### **Principio 2: Darle tiempo al modelo para "pensar"**

Si un modelo comete errores al apresurarse hacia una conclusión incorrecta, debes intentar reformular la consulta.

Táctica 1: Especificar los pasos para completar una tarea.<br>
Paso 1: ...<br>
Paso 2: ...<br>
...
Paso N: ...

Táctica 2: Instruir al modelo para que encuentre su propia solución antes de apresurarse hacia una conclusión.

# Limitaciones del modelo.

- Alucinaciones.
- Realiza declaraciones que suenan plausibles pero no son verdaderas.

Reducir las alucinaciones.
Primero encontrar información relevante,<br>
luego responder la pregunta<br>
basándose en la información relevante.