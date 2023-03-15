# Borrador

## Primer punto Quiz
   Dilan Torres : 1000353530
   
   ![image](https://user-images.githubusercontent.com/124721286/225171932-6644b634-fdae-4a8f-a69d-dcf4c304ed4f.png)

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
      
   10. En el siguiente item nos piden que organicemos los números de forma ascendente. Sin embargo, al tener ya los números ordenados, lo único que deberemos hacer es mostrarle al usuario un mensaje situando como primer número a "menor", seguido de esto a "medio1", luego a "medio2", después "medio3" y por último a "mayor".

   ![image](https://user-images.githubusercontent.com/124721286/225165806-d7bd98dd-92a5-4dd0-becf-3fb7b146527e.png)

   11. Luego de haber hecho esto, debemos organizar los números en forma descendente, asi que realizaremos lo mismo que en el paso anterior solo que esta vez el orden sera primero "mayor", el siguiente será "medio3", luego "medio2", seguido de "medio1" y en último lugar posicionaremos a "menor".

   ![image](https://user-images.githubusercontent.com/124721286/225166099-b2f77a39-fb9b-4ce0-8846-130286ba4132.png)

   12. El penúltimo item nos pide que elevemos el mayor número al menor número, para esto, simplemente usamos el simbolo de potencia en python, El resultado de esta operación lo guardaremos en la variable pot, y una vez hecho el cálculo mostraremos el resultado en un mensaje.
    
       ![image](https://user-images.githubusercontent.com/124721286/225166432-8cfd9cee-76fa-42a4-9157-60a35a6856c6.png)
       
   13. Por último, debemos calcular la raiz cúbica del menor número, asi que, usando el simbolo de potencia en python, elevaremos el menor número a la 1/3. Cuando tengamos el resultado, lo guardaremos en la variable raiz y le mostraremos el resultado al usuario.

       ![image](https://user-images.githubusercontent.com/124721286/225166727-13248533-2643-4990-9b1c-2edc041d4ea5.png)

   14. Ejemplo usando los números 45, 21, 7, 56 y 2.

       ![image](https://user-images.githubusercontent.com/124721286/225166858-2930a780-da15-4d6e-b9c3-b7dbbce2778c.png)
       
       ![image](https://user-images.githubusercontent.com/124721286/225166880-12175733-a113-461d-a39b-016f5170bd19.png)
       
       ![image](https://user-images.githubusercontent.com/124721286/225166902-49ca5b6e-0bfb-4e0c-b419-3f3bab5e6cc0.png)
       
       ![image](https://user-images.githubusercontent.com/124721286/225166929-d681a313-4517-461f-a191-62fe0d6cf9c3.png)
       
       ![image](https://user-images.githubusercontent.com/124721286/225166952-cead5d65-4058-439f-ada6-96b4f12a299d.png)
       
       ![image](https://user-images.githubusercontent.com/124721286/225166997-57a8b9e9-d947-4e1e-9b55-e92dffa8d88e.png)

   15. Código completo
        
        ![image](https://user-images.githubusercontent.com/124721286/225167155-13c0510e-0afa-4376-948b-6a8597f0b79a.png)
        ![image](https://user-images.githubusercontent.com/124721286/225167220-9d57abbc-a512-4cb8-8573-b8f2ebd9a1f4.png)
        ![image](https://user-images.githubusercontent.com/124721286/225167276-59301dad-b08e-415b-9c22-a8c6476c2970.png)
        ![image](https://user-images.githubusercontent.com/124721286/225167311-ca1a1cc0-1ff3-43af-8004-e001b76fc46a.png)
        ![image](https://user-images.githubusercontent.com/124721286/225167352-e08f6d52-072f-48dc-89ac-1f7d2a76c0aa.png)
        ![image](https://user-images.githubusercontent.com/124721286/225167389-4dad3515-ed2d-4e01-a2d8-52ef7cd439c1.png)
        ![image](https://user-images.githubusercontent.com/124721286/225167423-4807aa4b-2f89-4950-a871-eeb1bdef04ba.png)
        ![image](https://user-images.githubusercontent.com/124721286/225167538-0c22d092-6da5-40fe-9724-f93cd88702d7.png)
        ![image](https://user-images.githubusercontent.com/124721286/225167578-241846f0-59cf-457b-b8f9-4ed05e852a06.png)
        ![image](https://user-images.githubusercontent.com/124721286/225167635-055e1879-90ca-409f-a226-044526f1131e.png)
        ![image](https://user-images.githubusercontent.com/124721286/225167681-fc43dcd6-2991-47fb-bbcd-94f0f0a0ef08.png)
        ![image](https://user-images.githubusercontent.com/124721286/225167725-a9a69704-ab4f-4356-9f95-94ec62d109f1.png)
        ![image](https://user-images.githubusercontent.com/124721286/225167842-22feb582-e3d0-482c-bbfa-3b4873753a92.png)
        ![image](https://user-images.githubusercontent.com/124721286/225167914-ef447554-5896-4bb3-b48d-27a41af45688.png)
        
## Décimo punto 

   Escriba un programa que dada una distancia calcule:

   - El tiempo que le tomaría a la luz recorrer la distancia.
   - El tiempo que le tomaría al sonido (en el aire) recorrer la distancia.
   - El tiempo que le tomaría al vehiculo comercial más veloz recorrer la distancia.
   - El tiempo que le tomaría a Bolt recorrer la distancia.
   
   1. Como primer paso le pediremos al usuario que nos digite una distancia en metros. Esta distancia se guardará el la variable "x".
      
      ![image](https://user-images.githubusercontent.com/124721286/225168303-e92e9fd8-3140-41b7-bdfd-2ddadf06f15d.png)
      
   2. Seguido de esto calcularemos el tiempo que le tomaria a la luz resrorres esa distancia. Esto lo haremos dividiendo la distancia "x" entre la velocidad de la luz en metros sobre segundo (299.792.458 m/s). El resultado lo guardaremos en la variable "tluz".

      ![image](https://user-images.githubusercontent.com/124721286/225168534-92943f2d-8de4-4cac-b351-5ffafea2b058.png)
      
   3. Igual que en el paso anterior, calcularemos el tiempo pero esta vez el que le toma al sonido en recorrer la distancia "x" usando, dividiendo la x sobre la velocidad del sonido en metros sobre segundo (343.2 m/s). El resultado lo guardaremos en la variable "tsonido".
 
      ![image](https://user-images.githubusercontent.com/124721286/225168993-971fb60e-60d4-4153-9416-f9e189e0dd52.png)
      
   4. Para el tiempo que le tomaria al vehiculo comercial mas caro, repetiremos el proceso de los pasos anterios sol que esta vez usando la velocidad correspondiente en metros sobre segundo (141.111 m(/s). El resultado lo guardaremos en la variable "tvehiculo".

      ![image](https://user-images.githubusercontent.com/124721286/225169520-c05d1611-16b5-4024-8da9-5a2f58c5b91f.png)
      
   5. Ahora, calculamos el tiempo que le tomaria a Usain Bolt recorrer la distancia ingresada, dividiendo la misma entre la velocidad del corredor en metros sobre segundo (12.4 m/s). El resultado lo guardaremos en la variable tbolt.

      ![image](https://user-images.githubusercontent.com/124721286/225170041-d724e43e-7608-45b6-b510-69870115e02e.png)
      
   6. Cómo paso final le mostraremos al usuario varios mensajes indicando los tiempos calculados para cada caso.

      ![image](https://user-images.githubusercontent.com/124721286/225170108-6940ccdb-ac4c-4176-bffd-c63052c845db.png)

   7. Ejemplo usando una distacncia de 100.000.000 metros.
      
      ![image](https://user-images.githubusercontent.com/124721286/225170197-29566ae6-8c26-4c5c-b818-d9702f4a16c5.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/225170242-3b928fac-f54a-4589-9d97-de25be2142f4.png)
      
### Diagrama de flujo punto 10 
   [![](https://mermaid.ink/img/pako:eNo1kc9PgzAUgP8V8k6YMKQtjJZEEzfG9OBJT44dKnSuEdqFFWVb9r_bFXynl_d9eT_yLlDpWkAGu0b_VnveGe89L5Vn42nzomQl9dabzR69hV802nBlhDfcjcLCgaU_eA9eLY8WVpJPbOlY7pumP1s83GPGUobjhE5C7oSVb45ayVo7h8QkxBNfOV745kfsZdU3o4FiFCKEJqdwzto3n7oxI8dh_N9h7ejzppBqWyoIoBVdy2Vtj73cjBLMXrSihMymNe--SyjV1Xq8N_rtpCrITNeLAPpDzY3IJf_qeAvZjjdHWz1wBdkFBshwmoSYURzhlFBGcDIP4AQZoSGL5zRCJMU4pXN2DeCste0QhSyKCImp5UmKSBKAqKXR3ev4C_cSN-HD-bc1rn_SVXdW?type=png)](https://mermaid.live/edit#pako:eNo1kc9PgzAUgP8V8k6YMKQtjJZEEzfG9OBJT44dKnSuEdqFFWVb9r_bFXynl_d9eT_yLlDpWkAGu0b_VnveGe89L5Vn42nzomQl9dabzR69hV802nBlhDfcjcLCgaU_eA9eLY8WVpJPbOlY7pumP1s83GPGUobjhE5C7oSVb45ayVo7h8QkxBNfOV745kfsZdU3o4FiFCKEJqdwzto3n7oxI8dh_N9h7ejzppBqWyoIoBVdy2Vtj73cjBLMXrSihMymNe--SyjV1Xq8N_rtpCrITNeLAPpDzY3IJf_qeAvZjjdHWz1wBdkFBshwmoSYURzhlFBGcDIP4AQZoSGL5zRCJMU4pXN2DeCste0QhSyKCImp5UmKSBKAqKXR3ev4C_cSN-HD-bc1rn_SVXdW)

   
   



      

      

   
      






























