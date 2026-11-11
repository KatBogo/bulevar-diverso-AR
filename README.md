# Bulevar Diverso · Realidad aumentada (Meta Quest 3)

La isla del Bulevar del Río (Cali) como una maqueta 3D en tu cuarto, para recorrer con las manos en las **Meta Quest 3**. Esta carpeta es la **página ya construida** (la genera `npm run github:ar` en el proyecto de código) y se publica con GitHub Pages.

La dirección abre directo la **versión con Meta Immersive Web SDK (IWSDK)**, la que se presenta (está en la carpeta `iwsdk/`). La primera versión, hecha con @react-three/xr, sigue en la misma dirección con `?xr` al final.

## Abrirla en las Quest 3

1. Ponte las gafas y abre **Quest Browser** (el navegador de Meta).
2. Escribe **`katbogo.github.io/bulevar-diverso-ar`** (todo en minúscula).
3. Espera a que cargue la isla y pulsa **«Entrar en realidad aumentada»**. Acepta el permiso que pide el navegador.
4. Verás tu cuarto y la maqueta frente a ti:
   - **Mover:** pellizca la isla (junta el pulgar y el índice con la mano sobre ella) y mantén el pellizco; al soltar, se queda ahí.
   - **Girar y cambiar el tamaño:** pellízcala con las dos manos; gíralas como un timón, sepáralas o júntalas.
   - **Pestañas, puntos y fichas:** señala con la mano (sale un rayo) y haz un pellizco corto.
   - **Historia:** la línea del tiempo con sus seis fechas; «Anterior», «Siguiente» y «Cerrar».
   - **Lugares:** toca el punto naranja del Gato de Tejada y su ficha se abre junto a él.
   - **Eventos:** Feria del Libro, Alumbrado o Sucursal Fest; su decoración sube sobre la isla.
   - **Rutas:** elige una; se dibuja el camino con las paradas numeradas.
5. Para salir, pulsa el botón Meta de un control o haz el gesto del menú con la mano.

La experiencia web normal está en la misma dirección con `?web` al final.

## Publicarla o actualizarla

- En el proyecto de código: `npm run github:ar` y vuelve a subir el contenido de `bulevar-diverso-AR/` (no la carpeta entera: `index.html` tiene que quedar en la raíz).
- **Settings → Pages:** Deploy from a branch, rama **main**, carpeta **/ (root)**.
- La realidad aumentada necesita HTTPS: GitHub Pages ya lo da. Abrir `index.html` con doble clic no funciona.
