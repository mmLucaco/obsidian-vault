

## 🧩 Concepto simple

> Primero en entrar, primero en salir (FIFO).

---

## ⚙️ Concepto técnico

> Estructura donde el primer elemento agregado es el primero en eliminarse.

---

## 🏗️ Cuándo se usa

- Turnos de jugadores
    
- Colas de eventos
    
- Matchmaking
    

---

## 🧪 Ejemplo

```lua
local queue = {}

table.insert(queue, "A")
table.insert(queue, "B")

table.remove(queue, 1) -- elimina "A"
```

---

## 🎮 Ejemplo en Roblox

- Sistema de matchmaking
    
- Cola de spawn de jugadores
    

---

## ⚠️ Errores comunes

- ❌ Ineficiencia si la lista es muy grande
    

---

## 🔗 Relacionado

- [[Table]]
    
- [[📄 Estructuras de datos]]
    

---

## 📚 Recursos

- [https://create.roblox.com/docs/es-es/luau/queues](https://create.roblox.com/docs/es-es/luau/queues)
    

#luau