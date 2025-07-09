# Errores comunes al instalar PES 6 en Linux (Wine 32-bit)

---

## ❌ "The game is not properly installed"

✅ Soluciones:
- Verificar que esté bien el valor `InstallDir` en el registro de Wine (`regedit`)
- Asegurarse de estar usando un **prefix de 32 bits**
- Ejecutar el juego desde el mismo prefix usando terminal

---

## ❌ "AFS file not found"

✅ Soluciones:
- Faltan archivos `.afs` (como `e_sound.afs`, `e_text.afs`, etc.)
- Verificá que estén en la carpeta `/dat` del juego
- Si bajaste una versión sin estos archivos, copialos desde un ISO o versión completa

---

## ❌ "grep: referencia hacia atrás inválida"

✅ Soluciones:
- Ocurre si escribiste mal un comando con grep
- Revisá que las barras invertidas (`\`) estén bien, o escribí directamente en terminal sin copiar/pegar mal

---

## ❌ No puedo escribir la barra invertida `\`

✅ Soluciones:
- En teclado latinoamericano: `Alt Gr + Q`
- O usá el teclado en pantalla (`onboard`)
- Si se buguea, reiniciá el entorno gráfico o apagá `onboard`

---

## ❌ El .desktop no lanza el juego

✅ Soluciones:
- Asegurate de que tenga permisos: clic derecho → "Permitir ejecutar"
- Revisá la ruta del prefix y el `.exe` en el archivo `.desktop`
