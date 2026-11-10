# Bulevar Diverso · Realidad aumentada (Meta Quest 3)

La isla del Bulevar del Río (Cali) como una maqueta 3D en tu cuarto, para recorrer con las manos en las **Meta Quest 3**. Esta carpeta es la **página ya construida** (la genera `npm run github:ar` en el proyecto de código) y se publica con GitHub Pages.

## Abrirla en las Quest 3

1. Ponte las gafas y abre **Quest Browser** (el navegador de Meta).
2. Entra al enlace de GitHub Pages de este repositorio (Settings → Pages), del estilo `https://TU-USUARIO.github.io/bulevar-diverso-AR/`.
3. Espera a que cargue la isla y pulsa **«Entrar en realidad aumentada»**. Acepta el permiso que pide el navegador.
4. Verás tu cuarto y la maqueta frente a ti:
   - **Mover:** junta el pulgar y el índice sobre el asa naranja de la base y mantén el pellizco.
   - **Girar:** pellizca una de las ruedas de los extremos y lleva la mano alrededor de la isla. Con las dos manos, una en cada rueda, también la agrandas o la achicas.
   - **Lugares:** señala la pestaña «Lugares» y haz un pellizco corto; luego toca el punto naranja del Gato de Tejada.
5. Para salir, pulsa el botón Meta de un control o haz el gesto del menú con la mano.

La experiencia web normal está en la misma dirección con `?web` al final.

## Publicarla o actualizarla

- En el proyecto de código: `npm run github:ar` y vuelve a subir el contenido de `bulevar-diverso-AR/` (no la carpeta entera: `index.html` tiene que quedar en la raíz).
- **Settings → Pages:** Deploy from a branch, rama **main**, carpeta **/ (root)**.
- La realidad aumentada necesita HTTPS: GitHub Pages ya lo da. Abrir `index.html` con doble clic no funciona.
