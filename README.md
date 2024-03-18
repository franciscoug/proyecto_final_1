# Ciencia de Datos en Python
## proyecto_final_1

Descripci´on: El proyecto consiste en aplicar los conocimientos aprendidos en clase (y apoy´andose
de referencias adicionales u´tiles) para crear modelos predictivos de regresi´on lineal uni-variable
sencillos de la forma:
                                    y = β0 + β1 ∗ x
Donde:
y es la variable dependiente,
x es la variable independiente,
β0 es el intercepto de la recta,
β1 es la pendiente de la recta.

Tanto x como y son parte del dataset usado , β0 y β1 son par´ametros del modelo los cuales buscamos estimar con los datos, esto significa que se busca encontrar que valores de β0 y β1 producen
una recta que describa de la mejor manera posible la relaci´on entre los datos x y y.

Se trabajara con un set de datos de muchas variables y se realiza un an´alisis exploratorio para
visualizar y analizar los datos y entender c´omo se comportan, luego de esto podremos elegir las
variables independientes x a trabajar(segu´n el potencial predictivo de estas a trav´es de medir la
correlaci´on) , esto significa que aunque el dataset posee mu´ltiples variables (columnas), en vez de
crear un modelo multi-variable crearemos mu´ltiples modelos uni-variable.

Los datos se encuentran dados en el formato binario de NumPy .npy por lo tanto usaremos la
funci´on load de numpy para poderlos utilizar: https://docs.scipy.org/doc/numpy/reference/
generated/numpy.load.html

Usando slicing sobre el dataset este deber´a separarse de la siguiente forma:

80 % del dataset(filas) se usar´a para todo el proceso de entrenamiento es decir: el analisis
exploratorio, selecci´on de variables a usar, creaci´on de modelos predictivos. Les llamamos
?set de entrenamiento?.
20 % del dataset(filas) se usar´a para probar ,validar y evaluar los modelos resultantes. Esto
significa que el 20 % de data no es usado durante todo el proyecto y es usado solo al final
cuando ya poseemos los modelos predictivos. Les llamamos ?set de validaci´on y pruebas?
Los datos del proyecto podr´a encontrarlos en el GES en la secci´on de Material de Apoyo con el
nombre de Datos para Proyecto #1

#Video explicativo
[Texto del enlace]([URL_del_enlace](https://vimeo.com/924775099/e9e5a79e75?share=copy)https://vimeo.com/924775099/e9e5a79e75?share=copy)
