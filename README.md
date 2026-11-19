# Modeler My ArQ

Editor de planos topográficos en una sola página (`index.html`), sin dependencias ni servidor.
Trabaja en coordenadas **GTM / WGS 84** (metros).

## Publicar
Sube `index.html` a la raíz del repositorio `modeler-my-arq` y publícalo en Netlify
(arrastrar la carpeta, o conectar el repositorio con «Publish directory» = `/`).

## Uso rápido
- **Abrir…** carga un proyecto `.json`, un `.kml` (de My ArQ u otro) o un `.csv` (`nombre,este,norte`).
- **Puntos**: edita nombre, Este y Norte; también se arrastran en el plano.
- **Lotes**: lista ordenada de puntos. Lotes vecinos comparten puntos para que todo encaje.
- **Herramientas del plano**: Mover, ＋Punto, Trazar lote, Fusionar (elimina duplicados), Medir.
- **Renumerar**: punto inicial + sentido (horario/antihorario); numera primero el perímetro exterior y luego los interiores.
- **Hoja**: título, papel (tabloide, A3, carta, A4), escala, cuadros y notas.
- **Ver plano / Exportar**: PDF (imprimir → Guardar como PDF), PNG, SVG, DXF (AutoCAD), KML, CSV y proyecto `.json`.
- Autoguardado en el navegador; usa **Guardar** para llevarte el `.json`.

Los datos de cada terreno no se incluyen en la página: se cargan desde el archivo del proyecto.
