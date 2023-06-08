# Descripción del Proyecto

Este proyecto consiste en un código de calculadora simple desarrollado en PHP. Permite a los usuarios realizar operaciones básicas de suma, resta, multiplicación y división.

## Uso

Para utilizar la calculadora, sigue estos pasos:

1. Abre el archivo que contiene el código en un entorno o servidor que admita PHP.
2. Ejecuta el archivo en tu navegador web.
3. Verás una interfaz de calculadora con números y operadores mostrados.
4. Ingresa un número o haz clic en los botones numéricos para ingresar valores.
5. Haz clic en un botón de operador (+, --, *, /) para realizar la operación correspondiente.
6. Para borrar la entrada actual, haz clic en el botón "C".
7. Para calcular el resultado, haz clic en el botón "=".
8. El resultado calculado se mostrará en el campo de entrada.

## Notas Importantes

- El estado de la calculadora se mantiene mediante el uso de cookies. La función **"storeCookies()"** se encarga de establecer y actualizar las cookies con el valor de entrada y el operador.
- Las operaciones aritméticas se realizan mediante el método **"performOperation()"**, que utiliza una estructura **"switch"** para determinar la operación en función del operador seleccionado.
- La división entre cero se maneja verificando si ambos números son cero. Si es así, se devuelve el mensaje **"Error de Sintaxis"** como resultado.

Por favor, ten en cuenta que este código representa una implementación básica de una calculadora y es posible que no maneje todos los casos extremos o escenarios de error. Se recomienda mejorar y validar el código según tus requisitos específicos.