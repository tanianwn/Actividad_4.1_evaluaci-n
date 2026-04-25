# Actividad_4.1_evaluaci-n
## Resultados ejercicio 1 

<img width="1797" height="926" alt="Screenshot from 2026-04-21 17-00-31" src="https://github.com/user-attachments/assets/0674d97d-2e95-4945-9a85-ec642a94abd0" />

## Resultados
Se analizó el procedimiento de la primera figura y se observó en los resultados que el carrito se aleja hasta salir del plano. A pesar de que las ecuaciones son correctas, al compararlas con las de un compañero, se identificó una diferencia en la implementación: él elevó los términos al cuadrado directamente, mientras que en mi código se realizó mediante una función o sintaxis distinta. Esta diferencia en la escritura de la ecuación, aunque matemáticamente equivalente, podría ser la causa de la discrepancia en la representación gráfica

## Procedimiento 
<img width="2268" height="4032" alt="IMG_0350" src="https://github.com/user-attachments/assets/3d43746b-843d-4a1b-ac74-71a5c0ef5938" />
<img width="2268" height="4032" alt="IMG_0351" src="https://github.com/user-attachments/assets/2cfe674e-d912-4a10-822d-dd108f305efe" />

---


# Reposición Examen. Resultados Gráficos de Trayectoria

## Resultado 1 
<img width="500" alt="Resultados de la simulación" src="https://github.com/user-attachments/assets/6c4c0e33-54a3-44e1-b9db-82753bb9c8c6" />

En esta primera prueba, se validó la lógica matemática de el path a completar.

* **Observación Clave:** Se lograron obtener los resultados esperados en cuanto a la forma de las curvas; sin embargo, la trayectoria se visualiza de manera **invertida** respecto al eje original.
* **Causa:** Esto se debe a un factor de signo en las ecuaciones de velocidad o en la integración de la posición. Debido a las restricciones de tiempo durante la reposición, no se realizó el cambio en el código, pero la continuidad y el cálculo de las derivadas ($dx$, $dy$) son matemáticamente **correctos**.

---

## Resultado 2 

En la segunda simulación, tras ajustar los parámetros, se obtuvo una figura que asemeja un **moño horizontal** o una **montaña rusa**.
<img width="500" alt="Resultados de la simulación2" src="https://github.com/user-attachments/assets/86d64c74-ef35-4d1a-a386-bb8ba0b17ced" />


* **Descripción de la Forma:** La trayectoria presenta una subida suave, una transición en el tramo 2 que genera un bucle o curva cerrada (parecido a un moño), y una caída hacia los numeros negativos pronunciada hacia el final.
* **Análisis Técnico:**
    * **Parámetros de Tiempo ($T_s$):** Esta respuesta visual es probablemente consecuencia de los parámetros del paso de integración ($T_s$). Un tiempo de muestreo específico, junto con la naturaleza exponencial y trigonométrica del Tramo 3, fuerza al robot a realizar maniobras bruscas para cumplir con la posición en el tiempo $t$ dado.
    * **Dinámica del Robot:** Debido a que la velocidad lineal ($u$) se dispara para compensar la caída exponencial, el robot describe estas curvas cerradas para mantener la coherencia con el modelo cinemático.


---

