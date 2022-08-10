# Lab1Redes

Por: Juan Manuel Deutsch, Héctor Diaz Alvarado y Santiago Contreras Aristizábal

Se nos presentó el siguiente problema: ¿Cómo permitir que Jaimito Pérez y sus familiares puedan navegar a la página cisco.com desde su casa y mediante cualquiera de sus computadores personales y teléfonos celulares  usando una red de internet y comunicación de datos? Mediante el conocimiento adquirido por la clase de Redes en grupo se ideó la siguiente solución:

1. Agregar los componentes:

  1.1. Para desarrollas satisfactoriamente la práctica son obligatorios los siguientes componentes:
    - Server-PT
    - Cloud-PT
    - Cable-Modem-PT
    - Wireless-Home-Router
    
  1.2. Los siguientes son los dispositos mediante los cuales se accederá a la página:
    - 3 smartphones
    - 2 Laptops personales
    - 1 PC de conexión por cable
    
2. Realizar los cambios necesarios en las placas de internet de las laptops. Las laptops tienen una placa de conexión alámbrica por deafult y para que se conecten de manera inalámbrica se les tiene que cambiar las placas. Para esto se realizan los siguienes pasos:
  
  2.1. Apagar la laptop.
  ![image](https://user-images.githubusercontent.com/89588991/183784661-85334fae-689c-4e47-9981-7c626dc22da4.png)

  2.2. Remover la placa alámbrica actual con la que cuenta arrastrandola con el mouse hacia el panel.
  ![image](https://user-images.githubusercontent.com/89588991/183783683-7830512b-d6cb-4864-ab12-109d301718fc.png)
  
  2.3. Agregar la nueva placa de internet inlámbrica seleccionandola en el menú de opciones y poniendola en el lugar donde anteriormente estuvo la placa alámbrica
  ![image](https://user-images.githubusercontent.com/89588991/183784451-e9dbfe8c-748c-4211-bfce-b656a8fe8d9b.png)
  
  2.4. Encender de nuevo la laptop y repetir el proceso con la otra

3. Ahora procederemos a configurar el servidor con la página y su respectiva IP:
  
  3.1. Para configurar la IP y el DNS entramos en la pestaña de Config que aparece al pinchar en el servidor en la vista lógica y colocamos nuestros datos.
  ![image](https://user-images.githubusercontent.com/89588991/183785099-07faca22-4dfa-48d8-a037-342092937190.png)
  
  3.2. Ya con la dirección IP y el DNS configurado, procedemos a configurar los servicios.
  ![image](https://user-images.githubusercontent.com/89588991/183785445-eace9ca5-9daa-4963-ac7c-c439fad7ba22.png)
  
  3.3. Para finalizar verificamos que el nombre de la página referida al DNS sea la correcta. Para esto entramos en la opción de DNS que aparece en el panel lateral y   verificamos que en la tabla diga cisco.com.
  ![image](https://user-images.githubusercontent.com/89588991/183785669-d30b2157-4392-4516-a1e6-3df0d8f6cc3d.png)

4. Ahora se procede a revisar las configuraciones de la nube de internet.
   
   4.1. En la pestaña Ethernet9 que aparece en el panel lateral revisamos que la opción elegida sea Cable
   ![image](https://user-images.githubusercontent.com/89588991/183785815-46763dfb-6839-47b4-a49e-27dd4af0b07b.png)
   
   4.2. De la misma forma, entramos en la configuración de Cable para revisar que aparezca la siguiente configuración.
   ![image](https://user-images.githubusercontent.com/89588991/183786120-47bdda25-cddb-4278-93f5-34ca2f15126a.png)
   
5. Revisar el Router inalámbrico:

  5.1. Entramos en la pestaña de config del router y realizamos la siguiente configuración:
  ![image](https://user-images.githubusercontent.com/89588991/183786407-e3701a92-b32e-41b9-bc9d-4f1a4f0b42e4.png)
  
  5.2. Ahora en la pestaña interna de la GUI identificada como Wireless hacemos la siguiente configuración:
  ![image](https://user-images.githubusercontent.com/89588991/183786481-2e77d9da-8448-43e8-b1a4-81975f337014.png)

6. Ahora conectamos el servidor al internet usandio un cable Copper Straight-Through que encontramos en la sección de conexiones en el menú inferior izquierdo. Pinchamos el servidor y posteriormente la nube de internet.
  ![image](https://user-images.githubusercontent.com/89588991/183786727-ab173f03-07e6-418a-8fac-892187898d22.png)
  
7. Conectamos usando un cable coaxial la nube de internet y el cable-modem.
  ![image](https://user-images.githubusercontent.com/89588991/183786917-eac343ce-ee56-4c98-afd3-a84e4fd9fcbf.png)

8. Usando nuevamente el cable Copper Straight-Through conectamos el cable-modem al router inalámbrico.

9. De la misma forma conectamos el PC al router usando el mismo cable.

10. Para los dispositivos inlámbricos no es necesario entrar ya que se conectan automáticamente siempre que estén encendidos y con una placa inalámbrica.

11. Revisamos el dominio previamente mencionado (cisco.com)

  11.1. Primero revisamos la conexión en el PC alámbrico
  ![image](https://user-images.githubusercontent.com/89588991/183787263-65062fa8-299e-4e4a-8b4e-7fb62fa992a6.png)
  
  11.2. Posteriormente en los dispositivos inalámbricos.
  ![image](https://user-images.githubusercontent.com/89588991/183787305-ab592cf0-fe85-4126-8075-00c6bccc32a0.png)

Funcionando todo ya podemos concluir el laboratorio con un tipo de conexión de árbol. 

Para mayor información y vista gráfica revisar el video:

https://youtu.be/9Il3gyp_90E
