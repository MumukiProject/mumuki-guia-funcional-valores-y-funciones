¡Haskell no vive sólo de números :wink:! Para cerrar, conozcamos algunas funciones para trabajar con strings:

* `length` nos dice el largo de un string;
* `head` nos devuelve el primer caracter (la primer letra) de un string;
* `++` nos permite concatenar (unir) strings y es infija (como todos los chirimbolos que vimos).

Veamos ejemplos de todas ellas:

```haskell
ム length "seru giran"
10

ム head "xilofon"
'x'

ム "guarda" ++ "polvos"
"guardapolvos"
```

> Hacé una función `cuantoMidenJuntos` que te diga cuánto miden dos strings concatenados. Por ejemplo: 
> 
> ```haskell
> ム cuantoMidenJuntos "tres" "empanadas"
> 13
> ```
