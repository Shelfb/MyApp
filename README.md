# Definición de variables:
Se pueden declarar utilizando palabras clave como var o val, seguidas del nombre de la variable, el tipo de dato y un valor inicial. 
Las variables pueden ser de tipos primitivos como Int, Float o Boolean, o de tipos no primitivos como Array, List o Map. 
También se pueden crear tipos personalizados utilizando clases e interfaces.

# Manejo de nulos:
Los tipos de datos nullable contienen el valor null. Lo cual permite manejar situaciones en las que un valor no está disponible o no se ha inicializado. 
Se utilizan tipos como Int, String, Boolean, etc. para indicar que una variable puede ser null.
  - elvis: Devuelve el valor de la variable si no es null, o un valor por defecto si es null.
  - let: Ejecuta un bloque de código si la variable no es null.
  
# Opcionales:
La clase Optional<T> representa un valor que puede ser null o no, se utilizan principalmente para trabajar con valores opcionales.
Cuenta con métodos como: 
  - isPresent()
  - get()
  - orElse()
  - orElseGet() 

# Comentarios: 
Los comentarios se utilizan para agregar información descriptiva al código y mejorar su legibilidad. 
  - Comentarios de una sola línea: (//)
  - Comentarios de varias líneas: (/* ... */)
  - Comentarios de documentación: (/** ... */) 
