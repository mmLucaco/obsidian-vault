
## 🧠 Qué es  

GUI = Interfaz Grafica

Básicamente es todo lo que el jugador ve:

* "Botones"
* "Texto"
* "Barras de vida"
* "Inventario"



---

## ⚙️ Cómo funciona  

El concepto técnico de **GUI** (*Graphical User Interface o Interfaz Gráfica de Usuario*) en los videjuegos se define como el conjunto de elementos visuales(
* "Iconos"
* "Menús"
* "Barras de vida"
* "Inventario"
) 
renderizados en pantalla que permiten al jugador interactuar con el entorno, interpretar la información del juego y manipular sus mecánicas.



---




## 💻 Ejemplo  

Este es un ejemplo de estructura en Roblox

```
StarterGui
 └── ScreenGui
      └── Frame
           └── TextButton / TextLabel
```

Ejemplo de script basica que lo que hace es que creamos una variable textButtom para obtener las propiedades del TextButtom con el script.Parent, despues usamosla señal de MouseButton1Click para cuando se presiona se conecte con la funcion que va a decirnos Hola y va a cambiar el nombre del botom 

```
local textButtom = script.Parent

textButtom.MouseButton1Click:Connect(function()
	print("Hola")
	textButtom.Text = "Hola"


end)

```


---


## 🧪 Prueba / práctica  

* [[Practica]]

---

## ❌ Errores comunes

* [[Errores Comunes]]

---
​
## ​📄 Documentación relacionado con UI (GUI)

* [[DOCUMENTACIÓN---RECURSOS]]
