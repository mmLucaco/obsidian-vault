
## 🧩 Concepto simple

> Guardan datos para usarlos después.

---

## ⚙️ Concepto técnico

> Referencias a valores almacenados en memoria que pueden cambiar durante la ejecución del programa.

---

## 🏗️ Cuándo se usa (IMPORTANTE)

- Guardar estado del jugador (vida, monedas)
    
- Almacenar resultados temporales
    
- Pasar datos entre funciones
    

---

## 🧪 Ejemplo básico

```lua
local x = 10
local nombre = "Lucas"
```

---

## 🎮 Ejemplo en Roblox real

```lua
local playerCoins = 100

playerCoins = playerCoins + 10
```

👉 Esto se usa en sistemas como [[Leaderstats]]

---

## ⚠️ Errores comunes

- ❌ No usar `local` (contamina el entorno global)
    
- ❌ Reutilizar nombres sin querer
    

---

## 🛡️ Buenas prácticas

- Usar nombres claros (`playerHealth`, no `x`)
    
- Mantener variables dentro del scope necesario
    

---

## 🔗 Relacionado

- [[📄 Tipos de datos]]
    
- [[📄 Funciones]]
    
- [[🧠 Luau (Hub)]]
    
- [[Leaderstats]]
    

---

## 📚 Recursos

- [https://create.roblox.com/docs/es-es/luau/variables](https://create.roblox.com/docs/es-es/luau/variables)
    

---

## 🧠 Notas personales