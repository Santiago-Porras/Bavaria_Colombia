![contexto-0](img/Imagen1.png)
# Reto Colombia

En Bavaria quieren encontrar la mejor estrategia de impulso, mantenimiento o frenado, de un listado de marcas establecido, con el objetivo de ofrecer el mejor portafolio a los puntos de venta/zonas dependiendo de sus características e historial de compra.​

## ¿Qué construir?

El objetivo es encontrar la probabilidad de que un cliente compre cada una de las marcas dadas, con el fin de asignar la estrategia adecuada a cada uno de ellos.​

Para esto se creará un modelo que estimé dicha probabilidad para cada una de las 5 marcas que se van a listar.​

![contexto-1](img/contexto-1.png)
![contexto-3](img/contexto-3.png)

## Explicación Datasets

**BaseConsolidada.csv** = Tabla de clientes con las características de su punto de venta, ubicación e histórico de compra

- Cliente	: Id del Establecimiento (Llave primaria)
- Regional2: Región donde se encuentra ubicado (Conjunto de departamentos)
- Gerencia2: Gerencia que le distribuye el producto (Conjunto de 1, 2 o mas ciudades)	
- SubCanal2: Tipo de establecimiento: (Tienda, Bar, etc)	
- Categoria: Variable definida por AB-Inbev para calificar la importancia de un establecimiento dada su compra histórica. 	
- Nevera: Variable dummie que me permite ver si el establecimiento tiene o no una nevera en su punto de venta.
- Año: Año en el que se realiza la compra
- Mes: Mes en el que se realiza la compra
- Cliente: Id del establecimiento
- SegmentoPrecio2: Categoría de la marca, dado el ingreso por litro a la compañía.
- Marca2: Marca vendida
- Cupo2: Tipo de envase de la marca vendida
- CapacidadEnvase2: Capacidad en volumen, de la Marca2-Cupo2 vendido.
- Volumen: Cantidad de volumen vendido de la Marca-Cupo2-CapacidadEnvase2
- disc: Descuentos otorgados al establecimiento por la compra
- nr: NetRevenue que dejó la venta a la compañía.


## ¿Cuáles son los entregables?

1. El output requerido completo.
2. El modelo aplicado,  consideraciones y resultados obtenidos.​

## Formato del entregable:

- Se debe entregar un csv o xlsx bajo la siguiente estructura: Evidenciando la probabilidad de compra por cada cliente para el siguiente mes.

![contexto-2](img/contexto-2.png)
