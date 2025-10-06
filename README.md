# Mis Customizaciones de Firefox y derivados 🪐

Holiiii estrellitas, ¿cómo están? Hoy les traigo un regalito que hará que su navegador deje de verse tan… básico. Este repo contiene un **userChrome.css** y guía de instalación que funciona en **Firefox y cualquier navegador basado en Firefox** (LibreWolf, Waterfox, Basilisk, etc.).  

> Advertencia: Esto no convierte tu navegador en la NASA, pero sí en un navegador decente visualmente.  

---

## ¿Qué encontrarás aquí?

- `userChrome.css` listo para copiar y pegar (tema estilo Furina, porque lo demás es aburrido).  
- Guía de instalación detallada, paso a paso, para no romper nada.  
- Tips para solucionar errores comunes y que tu navegador no explote en llantos.  

---

## Preview (Porque todos queremos presumir)

Imagínate esto: tu navegador con pestañas suaves, transparencias controladas, scroll estético y botones que no parecen del 2004.  

*(Aquí puedes poner un GIF o imagen de tu navegador personalizado)*

---

## Requisitos mínimos

- Navegador basado en Firefox (sí, Firefox normal cuenta).  
- Sistema operativo: Windows, Linux o macOS.  
- Paciencia, porque esto es tweaking manual.  

---

## Instalación paso a paso

> **Recomendación 0:** Haz backup de tu perfil. No seas ese usuario que llora porque perdió sus marcadores.  

1. **Ubica tu perfil de Firefox**  
   - Abre Firefox.  
   - Escribe en la barra: `about:support`  
   - Busca **"Directorio del perfil"** y haz clic en **"Abrir carpeta"**  

2. **Activa la carga de userChrome.css**  
   - En `about:config`, busca:  
     - `toolkit.legacyUserProfileCustomizations.stylesheets`  
     - Cambia a `true` (si no, tu archivo no hará nada).  

3. **Copia el archivo**  
   - Dentro de tu carpeta de perfil, crea una carpeta llamada `chrome` si no existe.  
   - Coloca dentro el `userChrome.css` del repo.  

4. **Reinicia el navegador**  
   - Sí, literalmente cierra y vuelve a abrir.  

---

## Solución de errores comunes

- **No pasa nada**  
  - Revisa que `toolkit.legacyUserProfileCustomizations.stylesheets` esté en `true`.  
  - Asegúrate de que el archivo se llama exactamente `userChrome.css`.  

- **Algunos estilos no aplican**  
  - Firefox cambió selectores, revisa si el repo tiene la versión más reciente.  
  - Borra caché y reinicia otra vez.  

- **Se ve raro o roto**  
  - Probablemente tu tema o extensión interfiere. Desactiva extensiones conflictivas y prueba de nuevo.  

- **Nada funciona y quieres llorar**  
  - Respira. Haz backup y prueba paso a paso.  
  - No uses `rm -rf /` en tu PC, aunque suene tentador.  

---

## Inspiración y Créditos

- Estilo y colores: **KutexVT**  
- Basado en estética Furina (porque sí)  
- Si usas esto, **menciona el repo al menos**, no seas rata.  

---

## ¿Necesitas ayuda?

Únete a nuestro Discord en [guns.lol/kutex](https://guns.lol/kutex) y pregunta sin miedo, estrellita.  

---

## Disclaimer

Si tu navegador explota, pierde marcadores o terminas gritando a la pantalla, no me hago responsable. Todo bajo tu propio riesgo, estrellita.  
