# Borrador

## Cuarto punto

   Realice un programa que lea dos números reales y determine si el primero es múltiplo del segundo.
   
   1. Lo primero que haremos sera pedirle al usuario que ingrese ods números reales los cuales serán guardados en las variables "x" y "y".
   
      ![image](https://user-images.githubusercontent.com/124721286/225158538-56d34329-febd-4d5c-8921-2e02b1b2bbdf.png)
      
   2.  Para saber si el primer numero es múltimplo del segundo, lo que debemos hacrer es comprobar si el residuo de dividir el primero por el segundo es igual a cero.
   
      ![image](https://user-images.githubusercontent.com/124721286/225160077-f51bc1c0-7cbb-49c3-acc2-cf9aab3c7830.png)

   3.  Si lo anterior sucede, podremos decir que el primero número ingresado es múltiplo del segundo.
   
      ![image](https://user-images.githubusercontent.com/124721286/225160193-4b5f14e0-bb89-403d-9795-4896bacc88b7.png)
    
   4. Si por le contrario, el residuo al realizar la división del primero por el segundo es diferente de creo, diremos que el primer número no es múltiplo del segundo.
   
      ![image](https://user-images.githubusercontent.com/124721286/225160367-00cbd1ae-b3ba-485c-b878-9f3299fb6b69.png)

  5. Ejemplo usando los números 5 y 10.
  
      ![image](https://user-images.githubusercontent.com/124721286/225160454-3842e637-336c-49ca-b752-6370545e2117.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/225160478-086c9a9a-73b8-4dc3-9b13-dd108e984137.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/225160504-f8d56fd3-348f-4f92-b36b-76358f994abc.png)

  6. Ejemplo usando los números 6 y 21.
  
      ![image](https://user-images.githubusercontent.com/124721286/225160580-111b5f28-0195-466d-8db3-924edbf178cf.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/225160613-5479f83b-739b-499f-9a1e-930651da0a29.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/225160651-545139cb-0e11-4a7a-ac27-6033effe7158.png)

  7. Código completo.
  
      ![image](https://user-images.githubusercontent.com/124721286/225160698-8b52941c-d65d-4c49-87b2-b5a511e53abf.png)


## Séptimo punto

   Escriba un programa que pida 5 números reales y calcule las siguientes operaciones:

   - El promedio
   - La mediana
   - El promedio multiplicativo (multilplica todos y luego calcula la raíz de la cantidad de operandos)
   - Ordenar los números de forma ascendente
   - Ordenar los números de forma descendente
   - La potencia del mayor número elevado al menor número
   - La raíz cúbica del menor número
   
   1. Lo primero que haremos sera pedirle al usuario que digite cinco números reales los cuales guardaremos en las variables "a", "b", "c", "d" y "e".
   
      ![image](https://user-images.githubusercontent.com/124721286/225161047-0634ea4a-0fef-42ad-9182-2ef81503515f.png)

   2. Debido a que gran parte de los items solicitados requieren de que los números ingresados sean ordenados, procederemos a realizar esta acción. Lo primero que haremos será determinar cual de los números ingresados es el mayor de todos, esto lo conseguimos al realizar la comparación de uno por uno con los demás. Si se cumple la condición de que un número sea mayor que los otros, entonces le asignaremos ese número a la variable "mayor".
   
      ![image](https://user-images.githubusercontent.com/124721286/225161397-a9aebde4-0125-43d4-ad8e-d53c4d63bd98.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/225161432-b8331ec8-7ec0-44a3-87a3-ed98be125e7b.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/225161455-6cb2ef81-3873-4aa1-82ee-71aea7502539.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/225161508-651b8585-fdc1-4184-aec1-0429821d4e46.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/225161554-275c5b0b-2994-4102-8575-2094694873bb.png)
      
   3. Una vez definido cual es el mayor, procederemos a determinar cual de los números ingresados es el que le sigue en orden descendente al mayor. Lo anterior lo lograremos si empezamos a comparar los números que no corresponden a mayor con los demás y lo guardaremos en la variable "medio3". Por ejemplo: si determinamos que el número mayor es "a" lo que haremos para determinar "medio3" será comparar "b", "c", "d" y "e" de tal forma que el que sea mayor entre estos se le asignará la variable "medio3". Sin embargo, no podemos olvidar que posiblemente "a" no sea el número mayor, por lo que es candidato a ser "medio3" por lo tanto debemos incluirlo en los casos donde no es el mayor. (Las siguientes imagenes corresponden al ejemplo de cuando a es el mayor, ya que se reptie en los demas casos solo que esta vez obviando a sus respectivos mayores)
      
      ![image](https://user-images.githubusercontent.com/124721286/225163188-906dd8b7-f023-4899-9d9c-d6565aaa9055.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/225162370-d4c5f238-7cb9-40a5-a8cc-1eb9a98dc054.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/225162414-f4da9192-476d-4bef-9ee3-f60147b33f2b.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/225162439-94528431-73d1-4a0f-a1e9-ef85a1d2a912.png)
      
   4. De la misma forma procederemos con el número que le sigue al anterior es decir a "medio3", este lo guardaremos en la variable "medio2". No debemos olvidar que debemos obviar los números "mayor" y "medio3", ya que se supone que estos ya fueron determinados anteriormente. (Las siguientes imagenes corresponden a cuando "b" es "medio3", ya que el procedimiento se repite para los demas casos).

      ![image](https://user-images.githubusercontent.com/124721286/225163383-a7dde842-07ae-471b-9994-cc017ae44db7.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/225163552-f09fa280-36d2-4b92-825a-388c04e482d5.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/225163573-3e5f4d0b-8531-4d2c-900b-20446ecab777.png)

   5. Ahora, lo que debemos hacer es determinar el siguiente número descendente y el menor, estos los guardaremos en las variables "medio1" y "menor" correspondientemente. Para esto, debemos comprarar los dos últimos números que nos faltan (olvidando a "mayor", "medio3" y "medio2") y determinar cual es el número mayor entre estos. (Las siguientes imagenes corresponden a cuando "c" es "medio2", ya que este procedimiento se repite para los demas casos).

      ![image](https://user-images.githubusercontent.com/124721286/225163946-f91fc767-12ec-40ce-8423-bf7dd3659e19.png)

   6. Los pasos 3, 4 y 5 deben repetirse para los distintos casos posibles.

   7. Una vez teniendo ordenados los números, procedemos a solucionar los items que nos estan solicitando, en este caso el promedio. Para esto, lo único que debemos hacer es realizar la suma de los números ingresados y el resultado dividirlo entre cinco. El resultado de toda la operación lo guardaremos en la variable "promedio". Luego de haber realizado el cálculo le mostraremos al usuario el resultado.
     
      ![image](https://user-images.githubusercontent.com/124721286/225164682-9614a439-f5a0-4724-b059-306277df5c27.png)

   8. Para la mediana, lo único que debemos hacer es mostrarle el valor de la variable "medio2", puesto que, al haber ordenado de forma previa los números, el número de la mitad correspondería a el valor de "medio2".

      ![image](https://user-images.githubusercontent.com/124721286/225164905-59f3da54-abb5-420b-81d5-f347d48cca92.png)
      
   9. En el siguiente item nos piden calcular el promedio multiplicativo; Para esto, lo que debemos hacer es realizar la multiplicación de todos los números intgrasados y lo obtenido, elevarlo a la 1/5. El resultado lo guardaremos en la variable "pmult". Una vez hecho esto, le mostraremos al usuario el resultado.

      ![image](https://user-images.githubusercontent.com/124721286/225165273-8e3a53f8-2156-485f-a5d5-2abdce60ae88.png)
      
   10. 
      

      

   
      






























