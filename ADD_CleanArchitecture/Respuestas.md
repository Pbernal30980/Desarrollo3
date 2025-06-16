# Respuestas Codelab

1. **¿Qué es ADD y para qué sirve en el diseño de software?**  
   Attribute-Driven Design (ADD) es un método para diseñar software centrado en cumplir con prioridades como rapidez, seguridad o capacidad de crecimiento. Su objetivo es crear un sistema que desde el inicio cumpla con lo que el negocio y los usuarios necesitan.

2. **¿Cómo se conecta ADD con Clean Architecture?**  
   ADD define las metas del sistema, como ser rápido o seguro, mientras que Clean Architecture organiza el código en partes claras para lograr esas metas. Juntos, crean sistemas sólidos y fáciles de mantener.

3. **¿Cuáles son los pasos clave de ADD para diseñar software?**  
   - Identificar qué necesita el sistema, como velocidad o estabilidad.  
   - Diseñar cómo las partes del sistema trabajarán juntas para cumplir esas necesidades.  
   - Verificar que todo funcione bien y hacer ajustes si es necesario.

4. **¿Cómo se eligen los atributos de calidad en ADD y por qué son clave?**  
   Se eligen hablando con el equipo sobre lo que el sistema debe hacer bien, como responder rápido o proteger datos. Son clave porque guían todo el diseño para satisfacer al negocio y a los usuarios.

5. **¿Por qué Clean Architecture ayuda a ADD?**  
   Clean Architecture organiza el código en capas separadas, lo que facilita construir lo planeado en ADD. Esto hace que el sistema sea flexible y fácil de actualizar sin complicaciones.

6. **¿Qué considerar al crear capas en Clean Architecture con ADD?**  
   - Cada capa debe tener un propósito claro, como manejar reglas del negocio o conectar con bases de datos.  
   - Las capas deben ser independientes para evitar problemas si algo cambia.  
   - Deben apoyar las prioridades de ADD, como rapidez o seguridad.

7. **¿Cómo ayuda ADD a decidir según las necesidades del negocio?**  
   ADD se enfoca en lo que el negocio quiere, como un sistema que no falle o sea rápido. Esto lleva a elegir soluciones, como respaldos automáticos, que apoyen esos objetivos.

8. **¿Qué ventajas tiene combinar ADD con Clean Architecture en microservicios?**  
   - Crea microservicios que cumplen con lo que el negocio necesita, como crecer rápido.  
   - Mantiene el código flexible para cambiar tecnologías sin problemas.  
   - Facilita mejorar y mantener cada microservicio por separado.

9. **¿Cómo asegurar que la arquitectura cumpla con los atributos de calidad de ADD?**  
   Se revisa si el sistema cumple con lo planeado, como tiempos rápidos, usando pruebas. Si hay problemas, se corrigen, y se sigue ajustando con el tiempo para mantener la calidad.

10. **¿Qué herramientas o métodos ayudan a validar esta arquitectura?**  
   - Herramientas como JMeter para probar velocidad o programas de seguridad para verificar protección.  
   - Monitoreo con herramientas como Prometheus para revisar cómo funciona el sistema.  
   - Métodos como revisiones de diseño o pruebas automáticas para asegurar que todo esté en orden.