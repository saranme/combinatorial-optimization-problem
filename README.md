# Combinatorial optimization problem
Resolución de problema de 4 viajantes recorriendo la mínima distancia posible con algoritmo genético.

Una compañía dedicada a la logística ha de replanificar sus rutas de reparto debido a la avería de uno de sus camiones. 
Su flota actual sólo consta de 4 vehículos y ha de abastecer de mercancía a todos sus clientes. 
Las coordenadas de las ubicaciones de sus respectivos almacenes están en el fichero coord.csv. El mismo consta de tres columnas:
•	id_cliente: identificador único de cliente
•	lat: latitud de la ubicación del almacén del cliente
•	lon: longitud de la ubicación del almacén del cliente

Cada uno de los vehículos partirá y acabará su ruta en las coordenadas (40.54557, -3.69453), sede de la empresa. Se asume que todos los vehículos son iguales y no tienen ninguna restricción de carga o volumen a la hora de realizar los repartos. La única restricción es que cada vehículo ha de realizar al menos una entrega. 

El objetivo es deterinar qué clientes serán abastecidos por cada vehículo de forma que la suma total de los km recorridos por los cuatro camiones sea mínima, así como indicar el total de la distancia recorrida por cada uno.

