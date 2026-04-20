

## 🧩 Concepto simple

> Repite código varias veces.

---

## ⚙️ Concepto técnico

> Estructuras iterativas que ejecutan bloques de código mientras se cumpla una condición o un rango.

---

## 🏗️ Cuándo se usa

- Repetir acciones
    
- Iterar sobre tablas
    
- Sistemas continuos (ej: daño por segundo)
    

---

## 🧪 Tipos de loops

### 🔹 for

```lua
for i = 1, 5 do
    print(i)
end
```

### 🔹 while

```lua
while true do
    print("Loop infinito")
end
```

### 🔹 pairs (tablas)

```lua
for key, value in pairs(tabla) do
    print(key, value)
end
```

---

## 🎮 Ejemplo en Roblox

```lua
for _, player in pairs(game.Players:GetPlayers()) do
    print(player.Name)
end
```

---

## ⚠️ Errores comunes

- ❌ Loops infinitos sin control
    
- ❌ Usar while sin condición clara
    

---

## 🛡️ Buenas prácticas

- Usar `for` cuando sabés el rango
    
- Evitar loops pesados en cada frame
    

---

## 🔗 Relacionado

- [[Table]]
    
- [[If]]
    
- [[📄 Control de flujo]]
    

---

## 📚 Recursos

- [https://create.roblox.com/docs/es-es/luau/control-structures](https://create.roblox.com/docs/es-es/luau/control-structures)
    

#luau