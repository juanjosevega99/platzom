# Platzom 

Platzom es un idioma inventado para el [Curso de fundamentos de JavaScript](htpps://platzi.com/js) de [Platzi](htpps://platzi.com)

## Descripción del idioma	 

-Si la palabra termina en "ar", se le quitan esos dos caracteres
-Si la palabra inicia con Z, se le añade "pe" al final 
-Si la palabra traducida tiene 10 o mas letras, se debe partir a la mitad y unir con un guión del medio
-Si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra intercambiando mayúsculas y min

## Instalación 

```
npm install platzom
```

## Uso 

```
import platzom from 'platzom'

platzom("Programar") // Program
platzom("Zorro") //Zorrope
platzom("Zarpar") //Zarppe
platzom("abecedario") //abece-dario
platzom("sometemos") //SoMeTeMoS
```

## Créditos
- [Juan Jose Vega](https://twitter.com/juanjosevega17)

## Licencia 

[MIT](https://opensource.org/licenses/MIT)