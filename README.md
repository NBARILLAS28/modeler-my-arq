# Modeler My ArQ

Editor de planos topográficos en una sola página (`index.html`), sin dependencias ni servidor.
Trabaja en coordenadas **GTM / WGS 84** (metros).

## Publicar
Sube `index.html` a la raíz del repositorio `modeler-my-arq` y publícalo en Netlify
(arrastrar la carpeta, o conectar el repositorio con «Publish directory» = `/`).

## Uso rápido
- **Abrir…** carga un proyecto `.json`, un `.kml` (de My ArQ u otro) o un `.csv` (`nombre,este,norte`).
- **Puntos**: edita nombre, Este y Norte; también se arrastran en el plano. Si renombras un punto con el nombre de otro (p. ej. el nuevo a «P5»), los demás se recorren solos (P5→P6, P6→P7…); hay una casilla para apagarlo.
- **Lotes**: lista ordenada de puntos. Lotes vecinos comparten puntos para que todo encaje.
- **Herramientas del plano**: Mover, ＋Punto, Trazar lote, Fusionar (elimina duplicados), Medir.
- **Renumerar**: punto inicial + sentido (horario/antihorario); numera primero el perímetro exterior y luego los interiores.
- **Hoja**: título, papel (tabloide, A3, carta, A4), escala, cuadros y notas.
- **PDF para trámites**: «Plano de ubicación» en Oficio vertical (8.5 × 13 in) con marco, brújula, extensión punto a punto (distancia y azimut), cuadro de datos (ubicación, propietario, área, perímetro, escala, coordenadas, colindancias, naturaleza, fecha) y línea de firma. Marca los lotes que forman la propiedad (los lados compartidos desaparecen y queda el contorno), escribe propietario y colindancias, y pulsa **PDF (imprimir)** → *Guardar como PDF* (tamaño Oficio, escala 100 %). Si los lotes marcados no se tocan, sale una hoja por cada parte. Los datos se guardan dentro del proyecto `.json`.
- **Ver plano / Exportar**: PDF (imprimir → Guardar como PDF), PNG, SVG, DXF (AutoCAD), KML, CSV y proyecto `.json`.
- Autoguardado en el navegador; usa **Guardar** para llevarte el `.json`.

Los datos de cada terreno no se incluyen en la página: se cargan desde el archivo del proyecto.
