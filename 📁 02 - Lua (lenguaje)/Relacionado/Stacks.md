
## 🧩 Concepto simple

> Último en entrar, primero en salir (LIFO).

---

## ⚙️ Concepto técnico

> Estructura de datos donde el último elemento agregado es el primero en eliminarse.

---

## 🏗️ Cuándo se usa

- Historial (undo/redo)
    
- Inventarios simples
    
- Sistemas de acciones
    

---

## 🧪 Ejemplo

```lua
local stack = {}

table.insert(stack, "A")
table.insert(stack, "B")

table.remove(stack) -- elimina "B"
```

---

## 🎮 Ejemplo en Roblox

- Sistema de acciones del jugador
    
- Historial de movimientos
    

---

## ⚠️ Errores comunes

- ❌ No controlar si está vacío
    

---

## 🔗 Relacionado

- [[Table]]
    
- [[📄 Estructuras de datos]]
    

---

## 📚 Recursos

- [https://create.roblox.com/docs/es-es/luau/stacks](https://create.roblox.com/docs/es-es/luau/stacks)
    

#luau