.. highlight:: lua

Sobre el lenguaje de programación LUA
###########################################

| **Lua** es un lenguaje de programación imperativo, estructurado y bastante ligero que fue diseñado como un lenguaje interpretado con una semántica extendible. El nombre significa «luna» en portugués.

Historia
--------
| Lua fue creado en 1993 por Roberto Ierusalimschy, Luiz Henrique de Figueiredo y Waldemar Celes basado en C y Perl con una estructura similar. Miembros del Grupo de Tecnología en Computación Gráfica (Tecgraf) en la Pontificia Universidad Católica de Río de Janeiro. Las versiones de Lua anteriores a la 5.0 fueron distribuidas bajo una licencia similar a la BSD, de la versión 5.0 en adelante se utiliza la licencia MIT, compatible con la GPL.

| Lua ha sido usado en muchas aplicaciones comerciales y no comerciales, cuyo número incrementa cada año.

Características
---------------
| Lua es un lenguaje de programación suficientemente compacto para usarse en diferentes plataformas. En Lua las variables no tienen tipo, sólo los datos y pueden ser lógicos, enteros, números de coma flotante o cadenas. Estructuras de datos como vectores, conjuntos, tablas hash, listas y registros pueden ser representadas utilizando la única estructura de datos de Lua: la tabla.

| Lua es un lenguaje multiparadigma porque su semántica puede ser extendida y modificada redefiniendo funciones de las estructuras de datos utilizando metatablas, casi como en Perl (así permite implementar, por ejemplo, la herencia aunque sea ajena al lenguaje). Lua ofrece soporte para funciones de orden superior, recolector de basura. Combinando todo lo anterior, es posible utilizar Lua en programación orientada a objetos.


Funcionamiento interno
----------------------
| Los programas en Lua no son interpretados directamente, sino compilados a código bytecode, que es ejecutado en la máquina virtual de Lua. El proceso de compilación es normalmente transparente al usuario y se realiza en tiempo de ejecución, pero puede hacerse con anticipación para aumentar el rendimiento y reducir el uso de la memoria al prescindir del compilador.

| También es posible la compilación en tiempo de ejecución utilizando LuaJIT.

Códigos de ejemplo
------------------
El clásico programa Hola mundo puede ser escrito de la siguiente manera:

.. code-block:: lua

  print("Hola mundo!")

También puede ser escrito como:

.. code-block:: lua

  io.write('Hello World!\n')

o el ejemplo dado en el `Website de Lua <http://www.lua.org/cgi-bin/demo?hello>`_:

.. code-block:: lua

  io.write("Hello world, from ",_VERSION,"!\n")

Los comentarios usan la siguiente sintaxis, similar a Ada, SQL y VHDL:

.. code-block:: lua

  -- Un comentario en Lua empieza con doble guión hasta la siguiente línea
  --[[ Los strings y comentarios multilínea
     se adornan con doble corchete]]

El factorial es un ejemplo de función recursiva.

.. code-block:: lua

  function factorial(n)
   if n == 0 then
      return 1 end
   return n * factorial(n - 1)
  end

