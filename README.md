Ignacio Hernández Bas 3ºGITT

Practica1:Plataforma Github & Git 
-----------------------------------

1-Introducción 
-----------------------------------

En la realización de esta práctica se va a llevar a cabo la familiarización con el entorno de trabajo, en este caso se utilizará Github y se llevará a cabo la prueba de comandos, los cuales se explicarán y documentarán en este documento. 

2-Prerrequisitos 
-----------------------------------

En primer lugar, se debe llevar a cabo la creación de un repositorio por parte del alumno y posteriormente hacer un fork del repositorio indicado y alojado en la siguiente URL: [https://github.com/gitt-3-pat/hello-world ](https://github.com/gitt-3-pat/hello-world)

![image](https://user-images.githubusercontent.com/91118338/150641278-91dcfa24-e0b9-4c1d-922b-4e970c675196.png)

*Ilustración 1 Fork del repositorio indicado* 

3-Prueba de comandos 
------------------------------------

1. **git clone** 

A partir de este comando se lleva a cabo la copia de un repositorio en un directorio de forma local. 

![image](https://user-images.githubusercontent.com/91118338/150641283-0097cf7b-b4f8-4955-80f3-a6462f479c41.png)

*Ilustración 2 Ejecución del comando git clone* 

2. **git status** 

Al ejecutar este comando obtenemos el actual estado del directorio de trabajo,indica la rama en la que el usuario se encuentra y si dicha rama está actualizada respecto a las últimas modificaciones. 

![image](https://user-images.githubusercontent.com/91118338/150641288-29f87c53-56be-459c-9040-0b5d32c35ad6.png)

*Ilustración 3 Ejecución del comando git status* 

3. **git add .**

Dicho comando se utiliza para indicar a Git aquellos ficheros los cuales han sido modificados o creados. Se debe realizar antes de llevar a cabo antes de realizar un git push/commit para indicar los cambios llevados a cabo en el repositorio. Se ha realizado la creación de un fichero, tal como se puede ver al ejecutar git status y mediante git add . se podrán ejecutar los comandos mencionados anteriormente. 

![image](https://user-images.githubusercontent.com/91118338/150641323-a070a60a-e473-4198-802c-a1bf8c143540.png)

*Ilustración 4 Ejecución de comandos git add . y git status.* 

4. **git commit** 

A partir del siguiente comando se hace una revisión de los cambios realizados y añadiendo “-m” se permite al usuario indicar un mensaje que haga referencia a dicha revisión. 

![image](https://user-images.githubusercontent.com/91118338/150641325-b2b2b262-ba2f-4202-8c78-1b0910906e63.png)

*Ilustración 5 Ejecución del comando git commit -m.* 

5. **git push** 

Dicho comando permite enviar los commits realizados anteriormente en el directorio local al repositorio remoto. Para poder llevarse a cabo, todos los cambios en el repositorio local deben haber sido revisados por el commit. 

![image](https://user-images.githubusercontent.com/91118338/150641330-6644f72e-8f1b-44cb-9caf-36eaa8ffe3a7.png)

*Ilustración 7 Ejecución del comando git push.* 

![image](https://user-images.githubusercontent.com/91118338/150641333-ebc28412-caff-456e-b120-9205ae1c6fab.png)

*Ilustración 6 Repositorio remoto tras realizar el push.* 

6. **git checkout**  

A partir de este comando se permite al usuario navegar por las diferentes ramas del repositorio, en el caso de que no se hayan creado, se puede crear directamente una rama añadiendo -b seguido del nombre de la rama que se desea crear. 

![image](https://user-images.githubusercontent.com/91118338/150641342-90722ea6-65b5-4ea8-9772-e15d4fd22246.png)

*Ilustración 8 Ejecución del comando git checkout -b.* 

![image](https://user-images.githubusercontent.com/91118338/150641352-15f6f70e-a0c2-4d09-b209-7fc19e15e664.png)

*Ilustración 9 Ejecución del comando git checkout.* 

7. **git branch**

Dicho comando nos permite observar las ramas del repositorio local además de indicar en cual de ellas se encuentra el usuario. 

![image](https://user-images.githubusercontent.com/91118338/150641356-25966891-2011-42f1-9f7e-8d9bccd063a6.png)

*Ilustración 10 Ejecución del comando git branch.* 

En el caso de que se quiera subir la rama creada localmente al repositorio remoto se deberá hacer un push con la siguiente estructura: git push -u origin nombre\_rama. 

![image](https://user-images.githubusercontent.com/91118338/150641358-d3108586-1ef4-4e09-9239-aa2b8b627230.png)

*Ilustración 11 Ejecución del comando git push -u.* 

8. **git merge** 

El siguiente comando permite llevar a cabo la unión de dos ramas en una única rama. Se va a llevar a cabo la creación de una rama adicional “desarrollo2” la cual se va a fusionar con la rama “desarrollo” creada previamente. 

![image](https://user-images.githubusercontent.com/91118338/150641365-4988193f-d9dc-4432-844e-059dfd45685c.png)

<center>*Ilustración 12 Rama “desarrollo2” creada.* </center>

![image](https://user-images.githubusercontent.com/91118338/150641381-0fec9847-5ac5-4d72-9b95-f1ff9e23338b.png)

*Ilustración 13 Ejecución del comando git merge desde la branch desarrollo.* 

![image](https://user-images.githubusercontent.com/91118338/150641383-7736888d-9104-4ed3-a504-c82b5119e7f6.png)

*Ilustración 14 Rama “desarrollo” tras llevar a cabo el merge.* 

9. **git rm**  

A partir de este comando se pueden borrar archivos pertenecientes al directorio de trabajo. 

![image](https://user-images.githubusercontent.com/91118338/150641389-863c389e-abeb-4a4d-a2cc-36f33d2166a6.png)

*Ilustración 15 Ejecución del comando git rm.* 

4-Comprobación de instalación correcta 
----------------------------------------

Por último, se debe llevar a cabo que la comprobación que la instalación de Intellij, Maven y Java 17 se ha realizado correctamente. 

![image](https://user-images.githubusercontent.com/91118338/150641428-6896c738-82bf-4973-a7ca-548797f59269.png)

*Ilustración 16 Muestra del Intellij ejecutando código.* 

![image](https://user-images.githubusercontent.com/91118338/150641435-72a9f3fd-502a-40d6-8e04-75f67bca883c.png)

*Ilustración 17 Ventana Maven del proyecto* 

![image](https://user-images.githubusercontent.com/91118338/150641437-ab91dc25-2577-4327-beb1-84cfe4ce79a1.png)

*Ilustración 18 Comprobación de la versión java instalada* 
