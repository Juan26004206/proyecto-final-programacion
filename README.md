Proyecto Final — Cotizador de Seguros TK‑U  
Curso: Introducción a la Programación de Computadoras  

Este proyecto consiste en desarrollar un **cotizador automático de seguros** para la empresa TK‑U, ubicada en la ciudad de Jedha.  
El sistema calcula el precio final del seguro aplicando recargos según la edad del asegurado, el estado civil y la cantidad de hijos.

---

1. Análisis del Problema

La empresa TK‑U realiza cientos de cotizaciones al día, pero el proceso es manual, lo que provoca:

- Atrasos en la entrega  
- Límite de solo 50 cotizaciones diarias  
- Pérdida de posibles clientes  

El objetivo del programa es **automatizar el cálculo de la cotización**, aplicando recargos según:

 Edad del asegurado  
- 18–24 años → 10%  
- 25–49 años → 20%  
- 50 años o más → 30%

Estado civil y edad del cónyuge  
Si el asegurado está casado, se aplica un recargo adicional usando los mismos rangos de edad.

Cantidad de hijos  
Cada hijo genera un recargo del **20% del precio base**.

---

2. Algoritmo del Programa (Paso a Paso)

1. Solicitar nombre del asegurado.  
2. Solicitar edad del asegurado.  
3. Verificar que sea mayor de edad.  
4. Definir el precio base (Q.2000).  
5. Calcular recargo según la edad del asegurado.  
6. Preguntar si está casado.  
7. Si está casado, solicitar edad del cónyuge y calcular su recargo.  
8. Preguntar si tiene hijos.  
9. Si tiene, solicitar cuántos y calcular el recargo total por hijos.  
10. Sumar todos los recargos.  
11. Calcular el precio final:  
   **precio_final = precio_base + recargo_total**  
12. Mostrar el resultado al usuario.

---

3. Archivo Principal

El archivo principal del proyecto es:


Este archivo contiene toda la lógica del cotizador:

- Conversión de datos ingresados  
- Condicionales por edad  
- Recargo por cónyuge  
- Recargo por hijos  
- Suma total  
- Cálculo del precio final  
- Alertas con los resultados  

---

4. Cómo Ejecutar el Programa

1. Abrir el archivo `proyecto_final.js` en un editor de texto.  
2. Copiar el contenido dentro de un archivo HTML o ejecutarlo en un entorno que soporte `prompt()` y `alert()`.  
3. Abrir el archivo en un navegador web.  
4. Ingresar los datos solicitados.  
5. El sistema mostrará el recargo total y el precio final.

---

5. Estructura del Repositorio
   
---

6. Autor

**Juan Pablo López López**  
Introducción a la Programación de Computadoras  
Año 2026

---

7. Estado del Proyecto

Proyecto completado y funcional.
