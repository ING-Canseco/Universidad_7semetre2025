📘 1. Funcionalidades básicas de Crystal Reports

Crystal Reports es
una herramienta de reportería y análisis de
datos integrada con Visual Studio. Se usa mucho en entornos
empresariales porque permite crear informes detallados a partir de bases de
datos.

Principales funcionalidades:

* Conexión a
  múltiples fuentes de datos: SQL Server, Oracle, MySQL, Excel, archivos de texto,
  etc.
* Diseño de
  informes personalizados: arrastrar y soltar campos, tablas, gráficos y
  subreportes.
* Parámetros y
  filtros dinámicos:
  los usuarios pueden filtrar datos en tiempo real (ej. filtrar ventas por
  fecha).
* Agrupación y
  resúmenes:
  permite calcular totales, promedios, máximos, mínimos automáticamente.
* Fórmulas
  personalizadas:
  se pueden crear expresiones con un lenguaje propio (similar a Excel, pero
  más avanzado).
* Subreportes: insertar reportes dentro de
  otros para analizar datos relacionados.
* Exportación: exportar informes a PDF,
  Excel, Word, HTML y otros formatos.
* Integración
  con aplicaciones:
  se puede incrustar en proyectos de Visual Studio (C#, VB.NET) para generar
  reportes desde un sistema.

📘 2. Mini Diccionario de Funciones (Crystal Reports)

Aquí te dejo un
primer bloque de 7 funciones más usadas,
con definición y ejemplo:

1. Sum ({Campo})
   * Devuelve la suma de los
     valores en un campo numérico.
   * Ejemplo: Sum({Ventas.Monto})
     → suma total de las ventas.
2. Average
   ({Campo})
   * Calcula el promedio de un
     campo.
   * Ejemplo:
     Average({Alumnos.Calificación}).
3. Maximum
   ({Campo})
   * Obtiene el valor máximo de
     un campo.
   * Ejemplo:
     Maximum({Empleados.Salario}).
4. Minimum
   ({Campo})
   * Obtiene el valor mínimo de
     un campo.
   * Ejemplo:
     Minimum({Productos.Precio}).
5. Count
   ({Campo})
   * Cuenta el número de
     registros de un campo.
   * Ejemplo:
     Count({Clientes.ID}) → cantidad de clientes registrados.
6. Round
   ({Campo}, n)
   * Redondea el valor a n decimales.
   * Ejemplo:
     Round({Ventas.Monto}, 2) → redondea a 2 decimales.
7. ToText
   ({Campo}, n)
   * Convierte un número en
     texto, con n decimales.
   * Ejemplo:
     ToText({Ventas.Monto}, 2) → muestra monto como texto con 2 decimales.
