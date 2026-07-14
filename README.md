# El Orejano — Sitio estático

Pequeña página estática del asadero y restaurante *El Orejano*. Contiene el menú y estilos.

## Archivos principales
- `index.html`: página principal y hoja de estilos embebida.

## Cómo ver el sitio

Opciones rápidas:

- Abrir `index.html` directamente en un navegador (doble clic).
- Servidor simple (recomendado para pruebas de rutas/scroll):

```bash
# Python 3
python -m http.server 8000

# luego abrir http://localhost:8000
```

## Funcionalidad añadida

- Menú móvil: se añadió un botón de toggle en el `header` que despliega un panel con las secciones del menú cuando la ventana es menor a 720px.
- Comportamiento: el botón alterna la clase `.open` en el `header`; al pulsar un enlace o `Escape` el panel se cierra. El estado accesible se refleja en `aria-expanded`.

## Personalización rápida

- Colores y variables están en `:root` dentro de `index.html` — cambia las variables CSS si quieres ajustar la paleta.
- Punto de quiebre móvil: `@media (max-width: 720px)`.

## Próximos pasos (opcional)

- Añadir animación de slide más suave o fondo semitransparente al desplegable.
- Convertir los estilos inline a `styles.css` si prefieres separar recursos.

---
Si quieres, puedo añadir una versión con `styles.css` y `app.js` separados o mejorar la animación del menú.
