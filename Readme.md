
<!-- TODO:  -->

# Ejercicio 4 Contornos Primer Trimestre

## 1. Creacion de los directorios.
    Dentro de la carpeta ejercicio 4 creamos las carpetas ordenador 1 y 2. El archivo ``` README.md ``` contiene los pasos realizados y capturas para demostrarlos.

![Alt text](img/01_Captura%20carpetas%20de%20mi%20ejercicio.jpg)


## 2. Creamos un repo vacío en GitHub.
    Creamos un repo en GitHub vacío sin readme ni gitignore

![Alt text](img/02_Creaccion%20repo%20vacio%20en%20Github.jpg)

## 3. Creamos un nuevo proyecto.

    Creamos un nuevo proyecto con reposito local aun no hemos ningun commit 

![Alt text](img/03_Creacion%20de%20proyecto%20con%20codigo%20de%20ejemplo%20en%20ordenador1.jpg)


## 4. Creamos nuevo archivo readme de forma local.

Al añadir el readme después nuestro IDE nos pregunta si queremos añadirlo al repor local de Git en nuestro caso NO. De querer añadirlo lo haremos por consola mas adelante.

![Alt text](img/04.1_Antes%20de%20crear%20el%20readme%20local.jpg)

![Alt text](img/04.2_Despues%20de%20crear%20el%20readme%20local.jpg)

## 5. Primer Push al repo remoto de GitHub.

Imagen capturando la lista completa de comandos escritos en la consola. Se pueden leer mejor en las otras dos capturas más "cercanas".

### 5.1 Capturas

#### 5.1.1 Captura general.

![Alt text](img/05_Primer%20commit%20y%20pusheo%20al%20repo%20remoto.jpg)

#### 5.1 Capturas especificas.

![Alt text](img/05.1%20_Parte%201de2.jpg)

![Alt text](img/05.2_Parte%202de2.jpg)

## 6. Clonacion repo remoto en Ordenador2.

![Alt text](img/06_Clonacion%20desde%20repo%20remoto%20a%20ordenador2jpg.jpg)

## 7. Nuevas funcionalidades desarrolladas en Ordenador2.

    Creamos una nueva rama que vamos a llamar "feat_persona" 

![Alt text](img/07_Creacion%20de%20rama%20feat_persona.jpg)

    Modificamos el proyecto. Añadimos una nueva clase persona. En esta añadimos el codigo que deseemos. Modificamos tambien la clase Main.
    
![Alt text](img/08_Creamos%20una%20clase%20persona.jpg)
![Alt text](img/08.1_Clase%20persona%20creada.jpg)

    Nos movemos a la rama feat persona y añadimos el codigo que, como nos deja ver IntelliJ se modifico desde el primer commit a este segundo.

    NOTAS (<!-- TODO: Meter algun desplegable o algo para que las nota no interrumpan la lectura del ejercicio -->)
    
    {
    NOTA1: En mi caso no se porque me dice que algunos archivos sin trackear porque solo he modificado la main y la clase persona. Si puedes explicarme te lo agradezco.

    NOTA2: Dices de pushear la rama, no se como se hace deberia primero hacer un commit a esa rama y después pushear el repo local contra el remoto. No entiendo lo que nos pedias en este punto.
    }

### 7.1 Capturas.

#### 7.1.1 General.
![Alt text](img/09_Perspectiva%20completa%20comandos%20Git%20rama%20feat_persona.jpg)

#### 7.1.2 Específicas.
![Alt text](img/09.1_rama%20feat_persona.jpg)

![Alt text](img/09.2_rama%20feat_persona.jpg)

NOTA3: El código se me puede comprobar en el IDE que es un copy paste del tuyo. He abierto el historial de commits y he copiado las diferencias entre los commits por eso solo adjunto capturas de la consola de Git.

## 8. Pusheo al repo remoto y merge.

    En este punto pushearemos la rama "feat_persona" al repo remoto.
    Despues de hacer esto mergearemos las ramas "master" y "feat_persona".

### 8.1 Capturas.

![Alt text](img/10_Pusheo%20de%20la%20rama%20(feat_persona).jpg)

![Alt text](img/10.1_Pusheo%20de%20la%20rama%20(feat_persona)%20visto%20en%20GitHub.jpg)

![Alt text](img/11_Mergeo%20master%20y%20feat_persona.jpg)

NOTA4: El merge se hace en local y despues de haber pusheado la rama.

Nota5: Se puede apreciar que aqui se pusheo a origin en Ordenador1 se debe pushear a Ejercicio4 que es como hemos "guardado" el enlace al repo remoto.

## 9. Creacion de una nueva rama y modificacion gitignore.

    En este punto nos movemos a la carpeta de ordenador uno. Comprobamos que no hay nada mas que el commit inicial. 

    Añadimos el archivo .xml al gitignore y lo comiteamos.

![Alt text](img/12_Estado%20inicial%20Ordenador%201%20.jpg)

![Alt text](img/13_Creamos%20rama%20(feat_empleado).jpg)

![Alt text](img/14.1_Modificando%20gitignore%20.jpg)

![Alt text](img/14_Modificando%20gitignore%20.jpg)

![Alt text](img/15_Commit%20a%C3%B1adiendo%20al%20gitignore%20el%20fichero%20xml%20.jpg)

## 10. Modificamos el proyecto dentro de esta rama y pusheamos.

    Añadimos una nueva clase Empleado. Existen cambios en la Main y la nueva clase que no era trackeada. Asi que los añadimos al area intermedia y lo commiteamos. Una vez hecho esto lo pusheamos a nuestro repo remoto y vemos que ramas tenemos con el comando ``` git branch -a ``` .

![Alt text](img/16_Commit%20probando%20empleado(segundo%20commit)%20.jpg)
    
![Alt text](img/17_Pusheando%20rama%20empleado%20.jpg)

![Alt text](img/17.1_Ramas%20dentro%20de%20este%20repo%20local%20.jpg)

## 11. Mergeamos las ramas master y feat_empleado.

    Mergeamos estas ramas en local e intentamos hacer un push.

![Alt text](img/19%20Pto%20de%20cagada%20deberia%20haber%20implementado%20el%20push%20de%20ordenador%202%20.jpg)

En mi caso como no habia confirmado las modificaciones el Github no me da error.
<!-- TODO: Intentar hacerlo al contrario desde ordenador 2 habiendo confirmado y dejando como definiva la version de ordenador1-->

No entiendo que ha pasado la verdad.

![Alt text](img/20__Me%20quedo%20bloqueado%20y%20perdido%20.jpg)

## 12. Paso intermedio a mayores.

    Creo que cometo un error en el momento que pusheo desde ordenador dos sin que ordenador1 con sus ramas esté subido, es decir, no me surge ningun conflito en ordenador 1 cuando pusheo. Sin embargo cuando quiero pullear desde el ordenador 2 si que me surge un conflicto. Como he visto en tus commit que te quedas con la parte de empleado modifico la main, borrando lo que sobra, y despues pulleo el repo remoto.


### 12.1 Capturas.
 
![Alt text](img/21_Intento%20arreglarlo%20para%20seguir.jpg)

![Alt text](img/21.2_Intento%20arreglarlo%20para%20seguir.jpg)

![Alt text](img/21.3_Intento%20arreglarlo%20para%20seguir.jpg)

![Alt text](img/21.4_Intento%20arreglarlo%20para%20seguir.jpg)
## 13. Intento dejar los dos ordenadores con el mismo proyecto.

    Debido al error que he cometido intento dejar las carpetas Ordenador1 y Ordenador2 con lo mismo (tener el mismo proyecto en el repo remoto y los dos locales) [¿Pueden tener distintos commit el repo local y el remoto siendo el mismo proyecto?]

### 13.1 Capturas de los commit en cada ordenador.

#### 13.1.1 Ordenador1.

![Alt text](img/22.1_situacion%20ord1.jpg)

#### 13.1.1 Ordenador2.

![Alt text](img/22.2_situacion%20ord2.jpg)

    Cuando deberiamos volver al Ordenador2. Nos informa que vamos dos commit por delante del repo remoto asi que lo que vamos a hacer es pushear el proyecto de Ord2 y después Pullearlo desde Ordenador1. Justo debajo podemos ver todos los comando usados en la consola de git. 
    
    NOTA6: Atencion a los directorios que muestra la consola para entender desde que sitios estamos pusheando y pulleando.

![Alt text](img/24.0_Push%20desde%20ord2.jpg)


![Alt text](img/24.2_Push%20desde%20ord2.jpg)

![Alt text](img/24.1_Pull%20desde%20ord1.jpg)

## 14. Estado final en los dos ordenadores.

    Por último cambiamos el este Readme.md para poder leerlo directamente en nuestro repo de GitHub.

### 14.1 Ordenador1.

![Alt text](img/25.1_Estado%20final%20commit%20en%20Ordenador1.jpg)

### 14.2 Ordenador2.

![Alt text](img/25.2_Estado%20final%20commit%20en%20Ordenador2.jpg)

### Conclusiones.

    Dejo aquí anotadas cosas a comentar con el profesor:
        - Repasar las capturas y comprobar que es lo que hemos hecho.



