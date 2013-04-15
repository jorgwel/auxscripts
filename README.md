# **Auxscripts** # 
========

En este repositorio hay scripts para el shel de linux que envuelven tareas
repetitivas de glassfish y postgres para hacerlas...igual de repetitivas,
pero más cortas.


## **Instalación** ##
   1. Clonar proyecto
            
        git clone https://github.com/jorgwel/auxscripts.git
        
   2. Entrar al directorio del proyecto clonado

        cd auxscripts
        
   3. Realizar la comprobación de los requerimientos

        [ TO-DO ]
        
   4. Copiar los scripts al PATH
 
        sudo cp dbaccion domaccion /bin





## **Descripción de uso de los scripts** ##

## dbaccion ##

Este script envuelve las acciones ejecutadas sobre postgres.

   1. Para verificar si una base de datos ya existe (**-e**)

        dbaccion -e [nombre de la base de datos]
        
   2. Para crear una base de datos (**-c**)

        dbaccion -c [nombre de la base de datos]
            
   3. Para eliminar una base de datos (**-b**)

        dbaccion -b [nombre de la base de datos]

   4. Para importar instrucciones de un script a una base de datos (**-i, -n, -s**)

        dbaccion -i -n [nombre de la base de datos] -s [nombre/path del script]
        
   4. Para reemplazar contenido de una base de datos con un script(**-r, -n, -s**)

        dbaccion -r -n [nombre de la base de datos] -s [nombre/path del script]
        

## domaccion ##

Este script envuelve las acciones ejecutadas sobre postgres.

   1. Para verificar el estado (arriba/abajo) de un dominio (**-v**)

        domaccion -v [nombre del dominio]
        
   2. Para iniciar un dominio (**-i**)

        domaccion -i [nombre del dominio]
            
   3. Para detener un dominio (**-d**)

        domaccion -d [nombre del dominio]

   4. Para importar instrucciones de un script a una base de datos (**-i, -n, -s**)

        domaccion -i -n [nombre de la base de datos] -s [nombre/path del script]
        
   4. Para reemplazar contenido de una base de datos con un script (**-r, -n, -s**)

        domaccion -r -n [nombre de la base de datos] -s [nombre/path del script]
        
<!--#***bold italic***  **bold** ***bold italic***-->