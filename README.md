# 📘 GUÍA DEFINITIVA COMPLETA DE MARKDOWN (README.md)

Esta guía incluye absolutamente TODO lo que puedes usar en Markdown
compatible con GitHub Flavored Markdown (GFM).

---

# 📑 TABLA DE CONTENIDOS

1. Encabezados  
2. Texto y formato  
3. Listas  
4. Enlaces  
5. Imágenes  
6. Citas  
7. Código  
8. Tablas  
9. Líneas horizontales  
10. Checklist  
11. HTML en Markdown  
12. Detalles desplegables  
13. Badges  
14. Emojis  
15. Anclas internas  
16. Escapar caracteres  
17. Comentarios  
18. Saltos de línea  
19. Alertas GitHub  
20. Diagramas Mermaid  
21. Enlaces por referencia  
22. Notas al pie  

---

# 1️⃣ ENCABEZADOS

## Resultado

# H1
## H2
### H3
#### H4
##### H5
###### H6

## Sintaxis

```md
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

---

# 2️⃣ TEXTO Y FORMATO

## Resultado

**Negrita**  
*Itálica*  
***Negrita + Itálica***  
~~Tachado~~  
<u>Subrayado (HTML)</u>

## Sintaxis

```md
**Negrita**
*Itálica*
***Negrita + Itálica***
~~Tachado~~
<u>Subrayado</u>
```

---

# 3️⃣ LISTAS

## Resultado

- Elemento 1
- Elemento 2
  - Sub elemento
    - Sub sub elemento

1. Paso uno
2. Paso dos
3. Paso tres

## Sintaxis

```md
- Elemento 1
- Elemento 2
  - Sub elemento
    - Sub sub elemento

1. Paso uno
2. Paso dos
3. Paso tres
```

---

# 4️⃣ ENLACES

## Resultado

[Google](https://www.google.com)  
https://github.com

## Sintaxis

```md
[Google](https://www.google.com)

https://github.com
```

---

# 5️⃣ IMÁGENES

## Resultado

![Ejemplo](https://via.placeholder.com/150)

## Sintaxis

```md
![Ejemplo](https://via.placeholder.com/150)
```

Imagen con enlace:

```md
[![Imagen](https://via.placeholder.com/100)](https://google.com)
```

---

# 6️⃣ CITAS

## Resultado

> Esto es una cita  
>> Cita anidada

## Sintaxis

```md
> Esto es una cita
>> Cita anidada
```

---

# 7️⃣ CÓDIGO

## Código en línea

Resultado:

Usa `console.log()`.

Sintaxis:

```md
Usa `console.log()`.
```

## Bloque de código

Resultado:

```javascript
function hola() {
  console.log("Hola mundo");
}
```

Sintaxis:

````md
```javascript
function hola() {
  console.log("Hola mundo");
}
```
