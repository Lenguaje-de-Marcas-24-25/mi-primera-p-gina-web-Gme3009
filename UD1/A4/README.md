
## 1.Características propias del lenguaje XML

XML (Extensible Markup Language) es un lenguaje de marcado diseñado para almacenar y transportar datos. Algunas de sus características clave son:

- **Simplicidad**: XML es fácil de leer y escribir tanto para humanos como para máquinas.
- **Extensibilidad**: No tiene etiquetas predefinidas, lo que permite a los usuarios definir sus propias etiquetas.
- **Autodescripción**: Los datos en XML están acompañados de metadatos en la forma de etiquetas.
- **Plataforma independiente**: Puede ser utilizado en diferentes plataformas y lenguajes de programación.
- **Jerarquía**: La estructura de XML es jerárquica, lo que permite representar relaciones entre los datos.

## 2.Estructura de un documento XML y reglas sintácticas

La estructura básica de un documento XML sigue estas reglas:

1. **Declaración XML**: Al inicio de un documento XML es común incluir una declaración que indica la versión y la codificación del archivo

2. **Elemento raíz**: Todo documento XML debe tener un único elemento raíz que contenga todos los demás elementos. 
    
3. **Elementos**: Los elementos deben tener etiquetas de apertura y cierre correspondientes. Los nombres de las etiquetas son sensibles a mayúsculas y minúsculas
   
4. **Atributos**: Los elementos pueden tener atributos que proveen información adicional. Los valores de los atributos deben estar entre comillas

5. **Bien formado**: Un documento XML debe ser bien formado, es decir, cumplir estrictamente las reglas de apertura y cierre de etiquetas, entre otras.

## 3.¿Qué es un nodo raíz?

El nodo raíz es el elemento principal o contenedor de un documento XML. Todos los demás elementos deben estar contenidos dentro del nodo raíz. Solo puede haber un nodo raíz por documento. En el ejemplo anterior, `<libros>` es el nodo raíz.

## 4.¿Qué es un elemento vacío?

Un elemento vacío es un elemento que no contiene ningún contenido ni hijos, pero puede tener atributos.

## 5.Qué sentido tiene  crear documentos XML bien formados
Crear un documento XML bien formado asegura que pueda ser procesado correctamente por cualquier parser XML. Las ventajas incluyen:

- **Interoperabilidad**: Permite el intercambio de datos entre sistemas diferentes sin errores de interpretación.
- **Mantenimiento y legibilidad**: Documentos bien formados son más fáciles de leer y mantener.
- **Validación**: Facilita la validación con un DTD o esquema, asegurando que los datos sigan las reglas predefinidas. 

## 6.Espacios de nombres en XML
Los espacios de nombres en XML  se usan para evitar conflictos entre nombres de elementos cuando se combinan vocabularios distintos en un mismo documento.

**Ventajas de los espacios de nombres**:
- Evitar conflictos cuando diferentes vocabularios usan etiquetas con los mismos nombres.
- Se facilita el intercambio de datos entre diferentes sistemas o aplicaciones que usan XML

## 7.Entidades en XML. Crea un XML con las entidades vistas en clase.

Las entidades en XML permiten representar caracteres especiales o reservados que tienen un significado específico en el lenguaje, como <, >, o &. 

```
<mensaje>Usa &lt; y &gt; para representar los símbolos de menor y mayor.</mensaje>
```

## 8.Comentarios en XML. Muestra uno de los ejercicios anteriores con el enunciado dentro de un comentario. Dentro del comentario deben aparecer dos guiones.

Los comentarios en XML permiten incluir notas o explicaciones dentro del código que no son procesadas por los parsers. Se delimitan con <!-- y -->:

```
<!-- Este es un comentario que no será procesado -->
<libro>
   <titulo>Don Quijote</titulo>
</libro>
```