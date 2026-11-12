# Tema 1
## Visión general y niveles de abstracción
La idea general del tema es separar que ve el programador (arquitectura o ISA) de como esta construido por dentro (microarquitectura o estructura)

### Conceptos básicos
- La funcion basica de un computador es ejecutar programas, que manejan datos e instrucciones
- Programa: secuencia de instrucciones maquina que permite ejecutar una acción compleja.
- Instrucción: accion elemental que puede ejecutar un ordenador.
- Abstraccion: tecnica de ocultar los detalles que no son relevantes para el problema que estas estudiando

 ###Niveles de abstraccion (de arriba a abajo)
 1. Aplicacion
 2. Algoritmo
 3. Lenguaje de programacion
 4. Sistema operativo / Maquina virtual
 5. Arquitectura del repertorio de instrucciones (ISA)
 6. Microarquitectura u organizacion
 7. Nivel de transferencia de registros
 8. Puertas lógicas
 9. Circuitos
 10. Dispositivos
 11. Fisica

Arquitecuta (ISA) VS microarquitectura (estructura u organizacion)
|  | Que es | Ejemplos | En una familia de computadores |
| Arquitectura (ISA) | Lo que ve y puede usar el programador | Registros visible; memoria visible; repertorio y formato de instrucciones; tipos de datos; entrada/salida | Es la misma para todos los miembros |
| Microarquitectura | Como esta contruido el computador por dentro | Señales de control; interfaz con perifericos; velocidad o tamaño de las estructuras; estructura de la cache; ancho bus; tamaño ALU. | Puede cambiar de un meimbro a otro |

Una familia de computadores comparte una misma arquitectura, y cada miembro de la familia puede tener una estructura distinta

### ABI(application Binary Interface)

Una ABI define:
· El tamaño, la disposición y el alineamiento de los tipos de datos
· El orden y los mecanismos para pasar y recuperar argumentos y resultados en una llamada a una funcion
· Los mecanismos para que una aplicacion pueda llamar al sistema operativo
· El formato binario de los archivos compilados (objeto) de las librerias de programas
