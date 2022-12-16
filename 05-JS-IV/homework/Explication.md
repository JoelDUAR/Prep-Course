## objetos

Un objeto es una coleccion de propiedades.

## propiedades

Las propiedades son un conjunto de claves-valor (Key-Value) en donde la clave es el identificador y el valor es lo que se guarda dentro de ella. Pudiendo haber tantas claves como valor querramos, las claves tienen un solo nombre, no pudiendo repetirse dentro del objeto, mientras que puede haber mismos valores pero en diferentes claves.

## Métodos

Los métodos son funciones dentro de los objetos en donde el metodo seria la clave y dentro como valor se guarda la funcion. La notación para estos metodos es invocar el nombre del objeto seguido de un punto, con la clave correspondiente, y sus parentesis a continuació

## bucle for..in

Es un tipo de bucle for que permite recorrer objetos, con la diferencia de que ya no es por índice, sino mediante la siguiente sintaxis:

for(let clave in nombre-objeto){
    bloque de codigo a ejecutar;
}

## notación de puntos vs notación de corchetes.

# notación de punto

Se utiliza para llamar a la clave y por ende su valor mediante la sintaxis:

nombre-objeto.nombre-clave.

Si bien es mas sencilla que la notación con corchetes, es una notación literal ya que impide llamar a funciones o variables ya que luego del punto el interprete de JS busca una propiedad.

# notación de corchete

Utilizada para llamar claves mediante la sintaxis:

nombre-objeto["clave"]

Es mas complicada de escribir pero permite llamar a toda propiedad, incluyendo aquellas que con la notación anterior no se puede.
