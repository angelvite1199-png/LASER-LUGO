LASER LUGO — PROTOTIPO v0.1

ARCHIVO PRINCIPAL
- index.html: aplicación web autocontenida. No necesita instalación ni servidor para probarse.

CÓMO PROBAR
1. Descarga index.html.
2. Ábrelo en Chrome, Edge, Firefox o Safari.
3. Cambia ancho, fondo, alto, espesor y kerf.
4. Alterna Vista 3D / Piezas 2D.
5. Guarda un proyecto para almacenarlo en este navegador.
6. Exporta SVG para inspeccionarlo en tu programa de diseño/corte.

CÓMO PUBLICAR GRATIS CON GITHUB PAGES
1. Crea una cuenta gratuita en https://github.com/ si no tienes una.
2. Crea un repositorio público, por ejemplo: laser-lugo.
3. Sube index.html a la raíz del repositorio.
4. En Settings > Pages, selecciona Deploy from a branch, la rama main y la carpeta /(root).
5. Guarda y espera a que GitHub publique la dirección pages.github.io correspondiente.

LIMITACIONES IMPORTANTES DEL PROTOTIPO
- La vista 3D es una ilustración conceptual, no un modelo CAD de precisión ni una simulación de encastres.
- La exportación SVG genera paneles rectangulares y marcas ilustrativas; todavía no calcula uniones finger-joint correctas ni aplica el kerf a la geometría. No usar para fabricar piezas finales sin rediseñar y verificar las uniones.
- La distribución 2D es una vista preliminar, no un optimizador automático de anidado (nesting).
- Los proyectos se guardan en localStorage del navegador y no se sincronizan entre dispositivos.
- El bloqueo premium es una idea de arquitectura, no un sistema de cobro. Antes de vender funciones hacen falta autenticación, verificación de permisos del lado del servidor y una integración de pagos.

PRÓXIMAS ETAPAS RECOMENDADAS
1. Implementar geometría paramétrica de cajas y uniones ajustadas a espesor/kerf.
2. Añadir pruebas de tolerancia y exportación SVG validada.
3. Implementar nesting con rotación y márgenes configurables.
4. Añadir generadores modulares (letras, toppers, llaveros, figuras).
5. Añadir usuarios, almacenamiento en nube y roles/planes premium seguros.
