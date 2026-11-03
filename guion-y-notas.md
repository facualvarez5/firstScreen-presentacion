# Mejora FirstScreen — recorrido y notas

## 1. FirstScreen

Presentación del equipo. FirstScreen automatiza el primer filtro de selección con IA y mantiene la decisión final en manos del equipo.

## 2. Nuestra promesa · apertura

Frase central de apertura y cierre: “Aceleramos la primera decisión para que encuentres al mejor candidato en menos tiempo”. Hacer una pausa para que se lea completa.

## 3. Para qué existe

Enfocar el propósito: recuperar capacidad del equipo de RRHH para evaluar y decidir. FirstScreen automatiza tareas iniciales, no sustituye la decisión humana.

## 4. Tiempo del primer filtro

2.500 × 3 / 60 = 125 horas. Se entrevista al 30%: 750 personas. 750 × 15 / 60 = 187,5 horas. Total 312,5 horas por mes. La referencia a dos personas proviene de la presentación original, no es una conversión independiente a equivalentes de jornada completa.
En Canva figura como ejemplo de 2.500 postulaciones; no se identifica una empresa ni una búsqueda real. Mantener “Escenario” hasta disponer de esa vinculación.

## 5. Costo del primer filtro

312,5 × USD 12,27 = USD 3.834,375. Se conserva USD 3.835, el importe redondeado del escenario original. El costo unitario se redondea a USD 1,53. Son estimaciones del escenario TPP.

## 6. Costo de una mala contratación

Dato conservado de la presentación original, no validado nuevamente en esta migración: costo de desvinculación equivalente al 150% del salario anual de la posición. La cifra depende del contexto y no es universal. Fuente citada en el original: https://www.hrmorning.com/articles/real-cost-employee-turnover/ . No confundir con los costos operativos mensuales de nuestro escenario.

## 7. Costo de la demora

Rango de la presentación original para el tiempo de cobertura de una vacante. No es una promesa sobre la reducción que genera FirstScreen. Fuente original: https://www.iprofesional.com/management/381234-cuanto-tiempo-toma-a-las-empresas-cubrir-una-vacante-laboral . Se separa esta dimensión temporal del costo de desvinculación.

## 8. De la postulación a la decisión

Proceso completo: el equipo define atributos, criterios y preguntas; el agente entrevistador conduce el intercambio por texto, voz o video; el agente evaluador aplica puntuación y rúbricas; la decisión final permanece bajo supervisión humana.

## 9. Demostración

Pausa para mostrar el producto real. Esta diapositiva no contiene una grabación ni simula una demo. Abrir la aplicación de FirstScreen y recorrer la búsqueda, entrevista, evaluación y decisión.

## 10. Confiabilidad de la entrevista

Las alertas no equivalen a pruebas concluyentes. No afirmar que permiten detectar todo uso de IA o toda manipulación. Su propósito es aportar contexto y señalar entrevistas que requieren revisión.

## 11. Ahorro de dinero

Comparación del costo total del escenario, no un resultado garantizado. Manual: USD 3.835. FirstScreen: USD 2.236,50. Diferencia: USD 1.598,50, aproximadamente 41,7%; se conserva ≈40% del original. El costo unitario con FirstScreen es USD 0,89, no el ahorro por postulación. No mezclar aquí el 65% de tiempo liberado.
La etiqueta visible se simplificó a “ahorro operativo”; el ≈ indica aproximación. Los importes y supuestos del cálculo no cambiaron.

## 12. Ahorro de tiempo

El 65% equivale a unas 203 horas sobre 312,5 horas. Es la estimación temporal de la presentación original. No equivale al porcentaje de ahorro económico, ni necesariamente a una reducción de dotación. Por eso se muestra en una diapositiva independiente.

## 13. Para qué recuperar tiempo

Conectar el beneficio con su propósito: destinar capacidad a entrevistas de mayor profundidad, avanzar en la búsqueda y atender más postulantes. Se conservan los beneficios originales de estandarización, menor margen de error, menor tiempo de contratación, experiencia ágil y mayor capacidad. No se agrega una métrica de impacto no medida.

## 14. Modelo de negocio

Valores de la presentación original. Implementación: relevamiento del puesto, calibración de prompt y rúbricas de evaluación. Suscripción: infraestructura en la nube, almacenamiento seguro y mantenimiento. Consumo variable según modalidad y plan. El alcance por cantidad de posiciones no está explicitado en estas diapositivas; no inventarlo. No sumar estos importes al escenario de costos sin explicar primero sus supuestos.

## 15. Qué cubre el precio

Modelo SaaS híbrido basado en uso. Implementación: relevamiento, calibración de prompt y rúbricas. Suscripción: nube, almacenamiento seguro y mantenimiento. Consumo: USD 0,08–1,50 por CV procesado o entrevista completada, dependiendo de la modalidad y el plan. No presentar ese rango como tarifa única ni como costo interno de IA.

## 16. Llegada al mercado

Segmento inicial: organizaciones de contratación masiva y recurrente. Canales conservados del original: pilotos bonificados, venta directa B2B y alianzas con consultoras. Las frases de propósito explican esos canales, sin agregar resultados comerciales.

## 17. Diálogo con RRHH

Casos de prueba confirmados por el equipo: Original Penguin, Paula Cahen D’Anvers y Green Grocery. Los nombres se toman de la imagen aportada; los logos quedan reservados para incorporar los oficiales. No se atribuyen contratos ni resultados comerciales. Mejoras: autocompletado al cargar CV, canales de contacto integrados y métricas específicas.

## 18. Arquitectura

Diagrama conceptual, no topología de despliegue. React + TypeScript sirve el portal del candidato y el panel del reclutador. Se comunica por API HTTP con Go. Go concentra gestión de vacantes, entrevistas, evaluación y puntuación. PostgreSQL para persistencia, Amazon S3 para almacenamiento; OpenAI, Tavus/Daily y SMTP como servicios externos. Diseño hexagonal con separación de responsabilidades.

## 19. Desarrollo y calidad

Metodología del original: ciclos semanales, historias de usuario, demos y retrospectivas. Diseño: arquitectura hexagonal, separación de responsabilidades y facilidad de mantenimiento. Calidad: BDD/TDD, pruebas automatizadas e integración continua con CI/CD. No se agregan coberturas de tests ni métricas de calidad.

## 20. Riesgos y decisiones

Riesgos y respuestas de la presentación original. No afirmar ausencia de sesgos ni seguridad absoluta. Explicar cómo cada decisión responde a un riesgo concreto: supervisión humana para evaluación con IA, acceso y almacenamiento seguro para datos, operación centralizada y optimización para presupuesto.

## 21. Por qué FirstScreen

Recapitular sin mezclar porcentajes: ahorro de tiempo, reducción del costo operativo, menor tiempo de contratación, evaluaciones estandarizadas y mayor capacidad de selección. Cada dimensión ya fue explicada en su propia diapositiva.

## 22. Nuestra promesa · cierre

Frase central de apertura y cierre: “Aceleramos la primera decisión para que encuentres al mejor candidato en menos tiempo”. Hacer una pausa para que se lea completa.

## 23. Preguntas

Abrir espacio de preguntas. Usar el índice (G) para volver al escenario, precios o arquitectura según lo que pregunten.

## 24. Agradecimientos

Agradecimientos conservados de la presentación original.

## 25. Muchas gracias

Cierre y contacto del equipo. FIUBA · Universidad de Buenos Aires · 2026.