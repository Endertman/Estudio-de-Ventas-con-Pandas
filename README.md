# Estudio-de-Ventas-con-Pandas
Endert_Guerrero_T1_M3_Procesamiento_de_datos

# Errores en el DataFrame

## DataFrame "Ventas_Clientes_2021"
  
En el indice 2 del DataFrame "Ventas_Clientes_2021" se puede encontrar el primer error, "110,0", este error se debe a que es una cadena de texto cuando deberia ser un numero entero, ademas de tener una coma en vez de un punto para representar la parte decimal del numero. Lo mismo sucede con el indice 11, "100,00", estos errores seran arreglados mas adelante.

## DataFrame "Clientes_2021"
  
En el indice 0 del Datframe "Clientes_2021" encontramos el primer error, "JUan" cuando deberia ser "Juan", es un error simple a la hora de escribir el nombre es dicho caso hipotetico, algo similar sucede con los indices 1, "camila" deberia tener mayuscula al iniciar; indice 2, "DanIel" el cual tiene una mayuscula entremedio del nombre aunque esto no representa problemas en este caso ya que "Daniel" no se repite pero en caso de que fuera asi nos generaria un problema; indice 8 tambien presenta un problema similar, "LuiS". Todos estos problemas seran solucionados mas adelante.

# Errores en el DataFrame

## DataFrame "Ventas_Clientes_2021"

En el indice 2 del DataFrame "Ventas_Clientes_2021" se puede encontrar el primer error, "110,0", este error se debe a que es una cadena de texto cuando deberia ser un numero entero, ademas de tener una coma en vez de un punto para representar la parte decimal del numero. Lo mismo sucede con el indice 11, "100,00", estos errores seran arreglados mas adelante.

## DataFrame "Clientes_2021"

En el indice 0 del Datframe "Clientes_2021" encontramos el primer error, "JUan" cuando deberia ser "Juan", es un error simple a la hora de escribir el nombre es dicho caso hipotetico, algo similar sucede con los indices 1, "camila" deberia tener mayuscula al iniciar; indice 2, "DanIel" el cual tiene una mayuscula entremedio del nombre aunque esto no representa problemas en este caso ya que "Daniel" no se repite pero en caso de que fuera asi nos generaria un problema; indice 8 tambien presenta un problema similar, "LuiS". Todos estos problemas seran solucionados mas adelante.

# Solucionando problemas del DataFrame (Item1)

DataFrame "Ventas_Clientes_2021"
    
Para este dataframe remplazaremos la coma por un punto para que este sea representado correctamente y tambien eliminaremos todas las comillas haciendo uso de "replace", por ultimo convertiremos todos estos numero en "float"

DataFrame "Clientes_2021"

En este dataframe haremos uso de "str.title" con este quitaremnos todos lo errores ya que esta funcion nos pondra como mayuscula la primera letra de cada linea de texto y el resto de caracteres seran minusculas.

# Item2

Ahora crearemos un nuevo DataFrame ("df4") donde agruparemos a los clientes y sumaremos sus compras, este total lo dispodremos de forma desendente de forma que cuando lo mostraemos en pantalla podremos ver cuanto fue el total de las compras realizadas por el cliente organizado jerarquicamente segun dicho total.

Tambien como extra agregue una variable alojada en "mejor_cliente" y "peor_cliente" que encontran el nombre del cliente que mas compras realizo y al que menos compras realizo durante el 2021 a traves de la funcion "idxmax" e "idxmin", por otro lado la variable "compras" define la cantidad de compras que hicieron los clientes durante 2021 de una forma similar haciendo uso de "max" y "min".

Por ultimo se crearon la variable "maximo" que nos entregan el monto de maximo de la suma de todas las compras y la variable "minimo" que nos mostraria el contrario.

Al final mostraremos los resultados en pantalla para una mejor diccion.

# Item3

Ahora crearemos un nuevo DataFrame(df5), en este buscamos mostrar la diferencia entre el promedio de las compras realizado durante 2021 con respecto a la ultima compra realizada por el cliente en ese mismo año, Tambien encontraremos al cliente con la compra menor con respecto a su promedio a traves de las variables "down_cliente" y "down_media" haciendo uso de "idxmin" y "min" respectivamente.













    
