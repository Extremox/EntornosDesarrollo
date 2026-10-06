
**1. En la función1… Què fan aquestes línies de codi?**

String2 = string2 pierde un carácter por la función "substring" que coge el último carácter del valor, por lo que se queda como "string".
En la siguiente línea se le concatena el 1 al valor de "string" por lo que se queda la variable con valor: "string1".

**Què valen les variables string1 i string2 abans d'executar el codi de comprovació següent?**

El valor de cada variable es "string1"

**Per què no funciona l'operador == ? Quin operador s'ha d'usar en lloc d'aquest?**

Se le coloca el operador .equals, quedaría así:

```
if(string1.equals(string2)) { 
    System.out.println("SON IGUALES " + a);  
  
}  
else {  
    System.out.println("SON DIFERENTES");  
}
```

**La función2() està declarada com segueix:**

```
public void funcion2() {
			System.out.println("--------------------");
			System.out.println("Aquesta és la funció 2");
			System.out.println("Com faig la crida perquè funcione????");
}
```

**Aquesta funció com l'he de cridar des del mètode MAIN perquè funcione. Existeixen 2
possibilitats. Explica-les.**

