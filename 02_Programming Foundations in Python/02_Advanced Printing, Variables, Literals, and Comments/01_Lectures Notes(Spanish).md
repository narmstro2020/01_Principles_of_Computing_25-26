# Notas de Clase – Principios de Computación
## Tema: Python – Impresión Avanzada, Variables, Literales y Comentarios

---

## 🧠 Sección 1: Variables

### 🔤 ¿Qué es una Variable?
- Una variable es un **nombre** que se refiere a un **valor** almacenado en la memoria.
- Las variables permiten que los programas recuerden y reutilicen información.

### ✅ Sintaxis
```python
nombre = "Jordan"
edad = 16
altura = 5.9
```

### 🧠 Reglas de Nomenclatura
- Debe comenzar con una letra o guion bajo (`_`)
- Puede contener letras, dígitos y guiones bajos
- No puede ser una palabra clave reservada de Python (`if`, `print`, `while`, etc.)
- No puede contener espacios

---

## 🔢 Sección 2: Literales

### 📘 ¿Qué es un Literal?
Un literal es un **valor fijo** utilizado en el código de Python.

### 🧱 Tipos de Literales

| Tipo       | Ejemplo          |
|------------|------------------|
| Cadena     | `"hola"`         |
| Entero     | `42`             |
| Flotante   | `3.14`           |
| Booleano   | `True`, `False`  |

### ✅ Ejemplos de Código
```python
saludo = "¡Hola!"
año = 2024
pi = 3.14159
activo = True
```

---

## 💬 Sección 3: Comentarios

### 📗 ¿Qué es un Comentario?
- Un comentario es ignorado por Python.
- Se utiliza para explicar lo que hace tu código.

### ✅ Sintaxis
```python
# Esto es un comentario
nombre = "Jordan"  # Esto establece el nombre
```

- Usa comentarios para:
  - Describir secciones de código
  - Desactivar una línea temporalmente
  - Explicar por qué se hace algo

---

## 🖨️ Sección 4: Impresión Avanzada

### 🔹 `print()` con Comas
```python
print("Nombre:", nombre)
print("Edad:", edad)
```

### 🔹 Concatenación de Cadenas
```python
print("Nombre: " + nombre)
```
- Debes usar `+` solo con variables de tipo cadena.

### 🔹 f-Strings (Cadenas Formateadas)
```python
print(f"Nombre: {nombre}, Edad: {edad}")
```
- Estilo recomendado en Python 3.6+

---

## 🧪 Código de Demostración

```python
# Almacenar información personal
nombre = "Maya"
grado = 10
gpa = 3.8
materia_favorita = "Matemáticas"

# Imprimir de 3 maneras
print("Nombre:", nombre, "| Grado:", grado, "| GPA:", gpa)
print("Nombre: " + nombre + " | Materia Favorita: " + materia_favorita)
print(f"{nombre} está en el grado {grado} y ama {materia_favorita}.")
```

---

## 🎯 Vocabulario Clave

| Término   | Definición |
|-----------|-----------|
| Variable  | Un valor con nombre que puede cambiar |
| Literal   | Un valor fijo en el código |
| Comentario| Una línea ignorada por Python, usada para explicar código |
| f-string  | Un método de formato usando `{}` para insertar valores en cadenas |

---

## 📝 Tarea de Tarjeta Biográfica

Pide a los estudiantes que creen un programa en Python que:
- Use 5 variables (por ejemplo, nombre, edad, pasatiempo, trabajo soñado, comida favorita)
- Imprima una “biografía” usando los tres estilos de formato
- Incluya al menos 3 comentarios

**Ejemplo de salida:**
```
Nombre: Sasha
Edad: 15
Trabajo Soñado: Desarrollador de Videojuegos
Pasatiempo: Dibujar
Comida Favorita: Sushi
```

---

## ❓ Preguntas de Salida

**Preguntar a los estudiantes:**
1. ¿Qué es una variable?
2. ¿Qué sucede cuando olvidas las comillas alrededor de una cadena?
3. ¿Cuál fue tu forma favorita de usar `print()`?
