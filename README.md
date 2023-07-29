# Estudio-de-Ventas-con-Pandas
Endert_Guerrero_T1_M3_Procesamiento_de_datos

# Errores en el DataFrame

## DataFrame "Ventas_Clientes_2021" 

En el índice 2 del DataFrame "Ventas_Clientes_2021" se puede encontrar el primer error, "110,0". Este error se debe a que es una cadena de texto cuando debería ser un número entero, además de tener una coma en vez de un punto para representar la parte decimal del número. Lo mismo sucede con el índice 11, "100,00". Estos errores serán arreglados más adelante. 

## DataFrame "Clientes_2021" 

En el índice 0 del DataFrame "Clientes_2021" encontramos el primer error, "JUan" cuando debería ser "Juan". Es un error simple a la hora de escribir el nombre en dicho caso hipotético. Algo similar sucede con los índices 1, "camila", que debería tener mayúscula al iniciar; índice 2, "DanIel", el cual tiene una mayúscula entremedia del nombre, aunque esto no representa problemas en este caso, ya que "Daniel" no se repite. Pero en caso de que fuera así, nos generaría un problema. El índice 8 también presenta un problema similar, "LuiS". Todos estos problemas serán solucionados más adelante. 

# Solucionando problemas del DataFrame (Item1)

## DataFrame "Ventas_Clientes_2021" 

Para este dataframe, reemplazaremos la coma por un punto para que este sea representado correctamente y también eliminaremos todas las comillas haciendo uso de "replace". Por último, convertiremos todos estos números en "float". 

## DataFrame "Clientes_2021" 

En este dataframe haremos uso de "str.title" con este quitaremos todos los errores, ya que esta función nos pondrá como mayúscula la primera letra de cada línea de texto y el resto de caracteres serán minúsculas. 

# Item2

Ahora crearemos un nuevo DataFrame ("df4") donde agruparemos a los clientes y sumaremos sus compras. Este total lo dispondremos de forma descendente para que, al mostrarlo en pantalla, podamos ver cuánto fue el total de las compras realizadas por el cliente organizado jerárquicamente según dicho total. 

También, como extra, agregué una variable alojada en "mejor_cliente" y "peor_cliente" que encontrará el nombre del cliente que más compras realizó y al que menos compras realizó durante el 2021 a través de las funciones "idxmax" e "idxmin". Por otro lado, la variable "compras" define la cantidad de compras que hicieron los clientes durante 2021 de una forma similar haciendo uso de "max" y "min". 

Por último, se crearon la variable "máximo" que nos entregará el monto máximo de la suma de todas las compras y la variable "mínimo" que nos mostrará lo contrario. 

Al final, mostraremos los resultados en pantalla para una mejor dicción. 

# Item3 

Ahora crearemos un nuevo DataFrame ("df5"). En este buscamos mostrar la diferencia entre el promedio de las compras realizadas durante 2021 con respecto a la última compra realizada por el cliente en ese mismo año. También encontraremos al cliente con la compra menor con respecto a su promedio a través de las variables "down_cliente" y "down_media" haciendo uso de "idxmin" y "min" respectivamente. 













    
