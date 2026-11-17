# Estequiometría · Actividad interactiva (Tema 5)

Composición de la Materia · Lic. en Bioingeniería · Universidad Xochicalco, Campus Ensenada. Elaborado por T. Huerta.

Cubre el Tema 5 hasta **cálculo de fórmulas empíricas**: conservación de la masa, anatomía de la ecuación, subíndices y coeficientes, tipos de reacción, peso fórmula y molecular, composición porcentual, mol y masa molar, y fórmula empírica (desde % y desde masas). Son 15 reactivos (16 puntos), autoevaluables.

## Características
- **Reactivos por matrícula:** la matrícula es la semilla; cada estudiante recibe compuestos y números distintos. También se pide el nombre completo.
- **Antitrampa:** pantalla completa obligatoria; si el estudiante sale, cambia de pestaña o la ventana pierde el foco, la pantalla se bloquea y se cuenta la salida y el tiempo fuera. Copiar, pegar, seleccionar, clic derecho, arrastrar e imprimir están deshabilitados; los intentos de copiar o pegar se registran. Se bloquea la inserción de bloques de texto. Marca de agua con nombre y matrícula. Se registran las recargas y se impide abrir la misma matrícula en dos pestañas.
- **Sin límite de tiempo**, con registro del tiempo activo, el total y el tiempo fuera.
- **Calificación:** numéricas con 2 intentos (1 y 0.5 pts); opción múltiple con 1 intento. La solución aparece al terminar cada reactivo. Los errores de formato no consumen intentos.
- **Herramientas** (botones flotantes a la derecha, accesos directos en cada reactivo que las requiere y aviso al entrar a cada bloque o al fallar un cálculo): calculadora (EXP, potencias, raíz, Ans) y tabla de masas atómicas con solo los elementos que usa ese estudiante.
- **Comprobante** en PNG o PDF con datos, tiempos, indicadores de integridad, resultado por reactivo, calificación, código de verificación y QR.

## Archivos
| Archivo | Uso |
|---|---|
| `index.html` | La actividad (un solo archivo). |
| `verificar.html` | Página docente: valida comprobantes (QR o captura manual) y genera el solucionario de cualquier matrícula. No aparece en la actividad. |
| `.nojekyll` | Necesario para GitHub Pages. |

## Publicar en GitHub Pages
1. Crea un repositorio público (p. ej., `estequiometria-composicion-materia`) y sube los tres archivos a la raíz.
2. En **Settings → Pages**: *Deploy from a branch*, rama `main`, carpeta `/ (root)`.
3. Enlace para el alumno: `https://thuerta2398.github.io/<repositorio>/`.
4. Página docente: `https://thuerta2398.github.io/<repositorio>/verificar.html` (no la compartas).

## Revisar comprobantes
Escanea el QR: se abre `verificar.html` con los datos e indica **✓ Comprobante válido** o **✗ El código no coincide** (imagen editada). Desde ahí puedes abrir el solucionario de esa matrícula.

## Limitaciones
Es una página estática: las medidas disuaden y dejan evidencia, pero no impiden usar otro dispositivo. En iPhone no existe la pantalla completa para páginas web; el comprobante lo indica como «no disponible» y siguen contando los cambios de pestaña o de aplicación. El progreso se guarda en el navegador del dispositivo: si el estudiante cambia de equipo, empieza de nuevo con los mismos reactivos.

## Referencias
Brown, T. L., LeMay, H. E., Bursten, B. E., Murphy, C. J., Woodward, P. M., & Stoltzfus, M. W. (2018). *Chemistry: The central science* (14th ed.). Pearson.

Goldberg, D. E. (2005). *Schaum’s outline of theory and problems of beginning chemistry* (3rd ed.). McGraw-Hill.

Prohaska, T., Irrgeher, J., Benefield, J., Böhlke, J. K., Chesson, L. A., Coplen, T. B., Ding, T., Dunn, P. J. H., Gröning, M., Holden, N. E., Meijer, H. A. J., Moossen, H., Possolo, A., Takahashi, Y., Vogl, J., Walczyk, T., Wang, J., Wieser, M. E., Yoneda, S., … Meija, J. (2022). Standard atomic weights of the elements 2021 (IUPAC Technical Report). *Pure and Applied Chemistry, 94*(5), 573–600. https://doi.org/10.1515/pac-2019-0603

Código QR generado con qrcode-generator 1.4.4 (MIT), de Kazuhiko Arase.
