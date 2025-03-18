# Soy una cabecera

Como cabecera, podemos dar título al texto que estás leyendo en este preciso instante.

## Párrafos

Como se puede apreciar, si dejo un espacio entre ambos textos se generan dos párrafos.

Así, vemos que hay dos párrafos separados.

## Tipos de texto

Esto sería un _texto en cursiva_.

Esto sería un **texto en negrita**.

Esto sería un **_texto en cursiva y negrita_**.

## Enlaces

Esto sería un enlace:

[Ir a Google](https://www.google.com/)

## Imágenes

Así se cargaría una imagen: ![Perros golden](./img/perros.jpg)

## Citas

> Esto es una cita y queda recogifo en una especio de recuadro con borde gris claro.

> Esto es una cita que
>
> ocupa varias líneas.

## Listas ordenadas

Esto es una lista ordenada:

1. Elemento primero.
2. Elemento segundo.
3. Elemento tercero.
4. Elemento cuarto.

## Listas sin orden

Esto es una lista sin orden:

- Elemento primero.
- Elemento segundo.
- Elemento tercero.
- Elemento cuarto.

## Bloques de código

Esto es un bloque de código en C#:

```csharp
internal class Program
public static void Increment(int value)
{
value = value + 1;
}
static void Main(string[] args)
{
var inc = 3;
Increment(inc);
Console.WriteLine("Value: " + inc);
Console.ReadLine();
}
}
```

## Caracteres especiales

Para poder expresar las operaciones que se realizan con los caracteres \+, \* y \-, que se utilizan para dar formato a nuestro texto, debemos poner delante la barra invertida \\.

Ejemplo:

- 5\+2 es igual a 7.
- 10\*10 es igual a 100.
- 8\-4 es igual a 4.
