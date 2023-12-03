# Programa-2-Proceso-por-lotes-con-Multiprogramaci-n-
## Requerimientos

1. **Número de Trabajos Inicial:**
   - Se solicita al inicio del programa, conformando lotes con capacidad máxima de 5.

2. **Generación Interna de Información:**
   - Número de Proceso: Consecutivo y único.
   - Tiempo Máximo Estimado: Aleatorio (rango entre 6 y 18).
   - Operación: Aleatoria entre (+, -, *, /, residuo, porcentaje).

3. **Ejecución según Número de Proceso (ID):**
   - Los trabajos se ejecutan conforme a su número asignado.

4. **Interrupciones y Errores:**
   - Procesos en ejecución pueden ser interrumpidos por Entrada/Salida o terminados por Error.

5. **Teclas para Operaciones:**
   - | Tecla | ¿Qué Indica? | ¿Qué Hace?                                  |
     |-------|--------------|--------------------------------------------|
     | I     | Interrupción  | Proceso en uso va a la cola de procesos en ejecución. |
     | E     | Error        | Termina el proceso en ejecución, mostrando "ERROR" en lugar de resultado. |
     | P     | Pausa        | Detiene la ejecución del programa.           |
     | C     | Continuar    | Reanuda el programa pausado con la tecla "P". |

6. **Visualización en Pantalla:**
   - Procesos en Espera (Lote en Ejecución):
     - Número de Programa.
     - Tiempo Máximo Estimado.
     - Tiempo Transcurrido (0 si no se ha ejecutado).
   - Número de Lotes Pendientes: Especifica el número de lotes pendientes por ejecutar (mostrará 0 si no hay).
   - Proceso en Ejecución:
     - Muestra todos los datos del proceso.
     - Tiempo ejecutado.
     - Tiempo restante por ejecutar.
   - Trabajos Terminados:
     - Número de Programa.
     - Operación.
     - Resultado de la operación o "ERROR" en caso de terminación con error.
   - Reloj (Contador General): Indica el tiempo desde el inicio del programa.

7. **Finalización del Programa:**
   - Al terminar el lote en ejecución, continúa con el siguiente lote en espera.
   - El programa termina cuando todas las operaciones de todos los lotes se han realizado (Pausarlo).

## Entrega del Programa

### Datos Personales
- Nombre: [Nombre del Estudiante]
- Matrícula: [Número de Matrícula]

### Datos de la Materia
- Materia: [Nombre de la Materia]
- Profesor: M. en C. Violeta del Rocío Becerra Velázquez

### Número de Actividad
- Actividad: [Número de Actividad]

### Objetivo de la Actividad
- [Descripción del objetivo de la actividad]

### Notas acerca del Lenguaje
- Lenguaje utilizado: [Nombre del Lenguaje]
- Razón por la elección: [Explicación breve]

### TDA y Estructuras Utilizadas
- [Lista de TDA o estructuras utilizadas]

### Soluciones y Conclusiones
- [Detalles sobre cómo se abordaron los problemas y conclusiones obtenidas]
