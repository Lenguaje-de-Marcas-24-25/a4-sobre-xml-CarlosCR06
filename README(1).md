
# Preguntas y Respuestas sobre XML

## 1. Características propias del lenguaje XML
- **Extensible:** Permite definir etiquetas personalizadas.
- **Estructurado:** Los elementos están organizados jerárquicamente.
- **Legible:** Apto para humanos y máquinas.
- **Portabilidad:** Ideal para intercambiar datos entre plataformas.
- **Auto-descriptivo:** Los datos se explican a través de las etiquetas.

## 2. Estructura de un documento XML y sus reglas sintácticas
- **Único nodo raíz** que contiene todos los elementos.
- Las etiquetas deben tener **apertura y cierre**.
- **Atributos entre comillas**.
- Uso de **entidades** para caracteres especiales.

## 3. ¿Qué es un nodo raíz en XML?
El nodo raíz es el elemento principal que contiene todos los demás elementos de un documento XML.

## 4. ¿Qué es un elemento vacío? Ejemplos
Un elemento vacío no tiene contenido entre sus etiquetas. Puede declararse como:
```xml
<elemento></elemento>
```
o
```xml
<elemento/>
```

## 5. ¿Qué sentido tiene crear documentos XML bien formados?
Garantiza que el documento sea procesado correctamente, permitiendo interoperabilidad entre diferentes sistemas.

## 6. ¿Qué es un espacio de nombres? Ventajas de uso
Los espacios de nombres previenen conflictos de nombres en documentos XML combinados. **Ventajas:**
- Evita conflictos de nombres.
- Facilita la integración de diferentes vocabularios en un mismo documento.

## 7. Entidades en XML. Ejemplo
Las entidades en XML permiten representar caracteres especiales:
```xml
<entidades>
   <menor_que>&lt;</menor_que>
   <mayor_que>&gt;</mayor_que>
   <comilla_doble>&quot;</comilla_doble>
   <comilla_simple>&apos;</comilla_simple>
   <ampersand>&amp;</ampersand>
</entidades>
```

## 8. Comentarios en XML
Los comentarios en XML se escriben entre `<!--` y `-->` y no pueden contener dos guiones consecutivos.

**Ejemplo:**
```xml
<!-- Este es un comentario de ejemplo -->
<persona>
   <nombre>Juan</nombre>
   <edad>30</edad>
</persona>
```
