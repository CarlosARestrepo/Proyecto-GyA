<p><img alt="UDLA logo" height="150px" src="https://www.uao.edu.co/wp-content/uploads/2022/06/Logo-nuevo-acreditación.png"  align="center" hspace="5px" vspace="5px"></p>

<ins>**Proyecto final Gestión y almacenamiento de datos.**</ins>

*Notebook de limpieza y visualización de datos*

**Estudiantes:**

*****Natasha Hoyos Código 2241007*****

*****Sergio Márquez Código 2241010*****

*****Carlos Adolfo Restrepo Código 2241006*****

Tenemos un registro de ventas, de los últimos 8 años, de un almacén de insumos para confección ubicado en Cali, este consta de las siguientes características:

1. **Descripción:** la cual indica el nombre exacto del producto vendido, esta característica es de tipo caracter.
2. **Unidad:** Nos indica la unidad de medida del producto vendido, esta característica es de tipo caracter.
3. **Sector:** Nos indica al grupo o clase que pertenece el producto, esta característica es de tipo caracter.
4. **Fecha:** Fecha exacta en la que se vendió el item esta característica es de tipo datetime.
5. **Cantidad vendida:** indica el número de productos vendidos, esta característica es de tipo numérica.
6. **Valor venta:** indica el valor recibido por la venta del producto, esta característica es de tipo numérica.
7. **Rentabilidad:** indica el porcentaje de ganancia que dejó la venta del producto, esta característica es de tipo numerica.

# ***Problemática:***

1.  Identificar qué se debe mejorar o cambiar para aumentar rentabilidad.
2.  Identificar algún sector (categoría) que deba mejorar la oferta.
3.  Insight que permitan generar más valor.


# ***Base de datos:***

**Datos conservados: 99.9%, equivalente a 156.816 registros. 6 columnas, 156.816 registros**

- *Se eliminaron registros de rentabilidad y fecha incongruente.*

- *Se eliminó la columna "Unidad de medida" porque no aporta información en el análisis sobre rentabilidad.*

- *Se corrigió la asignación de sectores erroneos.*

# ***Conclusiones:***
1. En los gráficos se pudo observar que el producto que más se vende son los hilos es el que menor rentabilidad le deja a la empresa, y que productos de alta rentabilidad como son los cierres y el cacharro no se les da mucha importancia por sus bajas ventas pero claramente son la clase de productos que hay que potenciar para tener mejores dividendos.

2. Los productos estrella de la empresa son las hilazas, pues tienen un buen volumen de ventas y una buena rentabilidad, por lo cual sería idóneo invertir más en ese sector.

3. El valor de las ventas ha aumentado año a año desde 2016 lo que da buenas señales en cuanto al crecimiento del negocio, por lo cual la prioridad debe estar en el incremento de ganancias potenciando a los productos que mayor rentabilidad dejan.

4. El año de mayor rentabilidad hasta el momento fue el 2016, seguido del 2021, en el cual se vuelve a tener como producto con mayor rentabilidad a los cierres, por lo cual se debe a apuntar a mejorar el portafolio en este sector, los hilos siguen siendo el producto de mayor venta, lo que indica que a pesar de que su rentabilidad no es buena es un producto que no debe faltar.

5 Los productos complemetarios tienen mejor rentabilidad que los hilos, se propone incrementar su oferta para contribuir en mayor medida a mejorar la retabilidad neta.

# ***Generación de valor:***

*Gloria Judith Trujillo, administradora almacén*: 

*"Conocer la realidad de las ventas del almacén, nos permite tomar decisiones precisas sobre los cambios que se deben hacer, para seguir creciendo. Por ejemplo:* 

*Dada la realidad de los datos, vale la pena aumentar la oferta de los productos complementarios, en lugar de seguir aumentando solo el portafolio de hilos"*

