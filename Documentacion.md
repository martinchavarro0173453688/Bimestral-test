Calcular el área de un triangulo equilátero conociendo la medida de uno de sus lados.
 
 # solucion:

 ## Variable de entrada:
 *numerica:* medida de un lado;

 ## variable de salida:
 *numerica:* area;

 ## proceso:
 Ingresar la medida de un lado;
 area= ((Lado * Lado) * sqrt(3)) / 4;
 *imprimir*(area);



Ingresada una distancia en metros, calcular su equivalencia en pies.

# Solucion:

## Variable de entrada:
*numerica:* Distancia_en_metros;


## Variable de salida:
*numerica:* Distancia_en_pies;

## Proceso:
ingresar Distancia_en_metros;
Distancia_en_pies = (Distancia_en_metros * 3.28084)
*imprimir*Distancia_en_pies;



Pasar una cantidad dada en atmosferas a su equivalente en Pascales.


# Solucion:

## Variables de entrada:
*numerica:* atmosferas;

## Variable de Salida:
*numerica:* pascales;

## Proceso:
ingrese atmosferas;
ingrese pascales;
pedir al usuario las atmosferas
pascales = (atmosferas * 101325)
*imprimir*(pascales);


Hacer el algoritmo para crear y subir un repositorio a github.

# Solucion:

## Proceso 
 Crear un repositorio en la pagina GitHub con el boton new.
 Describir el repositorio (opcional).
 Nombrar el repositorio.
 Seleccionar si va a ser publico o privado.
 Hacer click en "Create repository".
 Abrir la terminal y navegar a la carpeta de tu proyecto.
 Iniciar un repositorio git con comando "git init".
 Agregar los archivos a Git con el comando "git add .".
 Confirmar los cambios con el comando "git commit -m "mensaje del commit".
 Copiar la URL del repositorio en GitHub.
 Agregar la URL a tu repositorio con el comando "git remote add origin [URL]".
 Guardar los cambios de tu repositorio a Git con el comando "git push -u originmaster".
 Ingresar tu nombre de usuario y contraseña de GitHub cuando sea solicitado.




 Calcular la suma de los primeros n números impares ingresando n.
# Solucion:

## Variables de entrada:
*numerica:* n;

## Variables de Salida;
*numerica:* suma;

## Proceso:
Ingresar el valor de n;
Ingresar n
si(n modulo2 !=0){
        suma= sumar(numero);
}
*imprimir*(suma);


Ingresados dos números calcular el modulo del primer número con el segundo número

# Solucion:

## Variables de entrada:
*numerica:* termino1;
*numerica:* termino2;

## Variables de salida:
*numerica:* modulo;

## Proceso 
Ingresar termino1;
Ingresar termino2;
modulo = termino1 modulo termino2
*imprimir*(modulo)