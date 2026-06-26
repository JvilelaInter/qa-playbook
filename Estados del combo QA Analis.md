Instructivo QA – Uso del campo "QA Análisis" en Jira

Objetivo:
El presente documento define el uso del campo "QA Análisis" como punto de control de calidad dentro del flujo de trabajo en Jira.

Tener en cuenta que estamos en la instancia antes comenzar a definir los casos de prueba de la HU.
Su propósito es asegurar la correcta validación de las Historias de Usuario, garantizando alineación con:

•	Criterios de aceptación
•	Diseño (Figma)
•	Reglas de negocio
________________________________________
Estados del campo "QA Análisis"
🔹 1. NO_REVISADO
Descripción:
Corresponde al estado inicial del campo "QA Análisis". Indica que la Historia de Usuario aún no ha sido validada por el equipo de QA.
Cuando aplica:
•	La cantidad de Historias del sprint impide su análisis
•	Falta de disponibilidad del recurso QA
________________________________________
✅ 2. REVISADO_OK
Descripción:
Indica que la Historia de Usuario ha sido validada satisfactoriamente por QA y cumple con los estándares de calidad establecidos (DOR - DOD)
Criterios de aplicación:

•	La totalidad de los criterios de aceptación están completos y especificados
•	La definición respeta el diseño definido en el Figma
•	El contrato concuerde con el lineamiento del Swagger
•	Tablas o collection de BDD

________________________________________
❌ 3. REVISADO_NOOK
Descripción:
Indica que la Historia de Usuario ha sido analizada, pero no cumple con los requisitos funcionales o de calidad esperados.
Cuando aplica:
•	Los criterios de aceptación son incompletos o ambiguos
•	Existen diferencias entre lo desarrollado y el diseño del (Figma)

________________________________________
📝 Buenas prácticas
•	En todos los estados, se debe registrar un comentario claro y detallado justificando la selección.
•	Documentar: 
o	Bloqueos detectados
o	Desviaciones funcionales
o	Evidencia de validación (si aplica)

SUGERENCIAS: 
