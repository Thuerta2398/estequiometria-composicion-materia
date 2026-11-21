# Laboratorio Sellado · juego de escape de estequiometría

Composición de la Materia · Lic. en Bioingeniería · Universidad Xochicalco, Campus Ensenada. Elaborado por T. Huerta.

**Jugar:** https://thuerta2398.github.io/estequiometria-composicion-materia/umbrella-lab/

Juego formativo de repaso del Tema 5 (≈ 52 min). Ambientación de suspenso en tonos grises: una fuga de vapor tóxico selló el nivel B-3 de la Estación Albacora y cada puerta se abre con un cálculo. Historia, personajes, lugares y logotipo son ficticios y originales.

## Salas

| # | Sala | Temas (Tema 5) | Retos | Tiempo |
|---|---|---|---|---|
| 1 | Esclusa de descontaminación | Anatomía de la ecuación, subíndices y coeficientes, estados, conservación de la masa, tipos de reacción | 5 | ~7 min |
| 2 | Sala de balanzas | Balanceo por tanteo (fácil, intermedio y combustión), con contador de átomos en vivo | 3 | ~6 min |
| 3 | Archivo de muestras | Peso molecular, peso fórmula, composición porcentual | 4 | ~7 min |
| 4 | Cámara de conteo | g ↔ mol, mol → partículas, átomos de un elemento, volumen molar (22.4 L, CN) | 5 | ~7 min |
| 5 | Laboratorio de análisis | Fórmula empírica a partir de % (con y sin ajuste ×2, ×3) y análisis de combustión | 4 | ~7 min |
| 6 | Sala de síntesis | g de A → g de B en los 5 pasos de la actividad T5b | 5 | ~8 min |
| 7 | Cámara del antídoto | Reactivo limitante, rendimiento teórico y % de rendimiento | 4 | ~8 min |

Cada sala abre con una nota de la Dra. Valdivia, que funciona como mini lección con las fórmulas en notación de ingeniería (factor unitario). Los datos se generan al azar, así que cada estudiante ve números distintos.

## Mecánica
- **2 intentos** por reto (1 en preguntas de dos opciones). Tras el primer error aparece una pista; al terminar el reto se muestra el procedimiento completo.
- **Exposición al vapor:** +10 % por error y +5 % por pedir una pista antes de responder; −20 % al liberar una sala. Al llegar a 100 % el estudiante se desmaya y repite la sala con datos nuevos.
- **Herramientas** que aparecen solo al tocar su botón y nunca se enciman al reto: en celular y tableta se abren debajo del reto; en computadora, en una columna a la derecha.
  - Calculadora de botones con EXP, xʸ, Ans y N<sub>A</sub>; el botón *Usar el resultado* copia el valor a la casilla activa (en notación científica, separa coeficiente y exponente).
  - Tabla de masas atómicas con los elementos de la sala (mismos valores que T5 y T5b).
- **Progreso guardado** en el navegador (Continuar / Reiniciar), mapa del nivel y lista «Sellos liberados X de 7». Las salas liberadas se pueden repasar sin afectar el progreso.
- **Informe final** con nombre, aciertos al primer intento, errores, pistas, desmayos, exposición máxima y tiempo activo, para enviar como captura.
- No hay antitrampa ni comprobante con QR: esa función la cumplen las actividades evaluadas T5 y T5b.

## Ajustes para docentes
Al inicio del `<script>` en `index.html`: `DANO_GAS`, `PISTA_GAS`, `ALIVIO` y las tolerancias `TOL` (1 %) y `TOL_SCI` (1.5 %). Los bancos de compuestos y ecuaciones están en `ROOMS[k].gen`.

## Referencias
Brown, T. L., LeMay, H. E., Bursten, B. E., Murphy, C. J., Woodward, P. M., & Stoltzfus, M. W. (2018). *Chemistry: The central science* (14th ed.). Pearson.

Prohaska, T., Irrgeher, J., Benefield, J., Böhlke, J. K., Chesson, L. A., Coplen, T. B., Ding, T., Dunn, P. J. H., Gröning, M., Holden, N. E., Meijer, H. A. J., Moossen, H., Possolo, A., Takahashi, Y., Vogl, J., Walczyk, T., Wang, J., Wieser, M. E., Yoneda, S., … Meija, J. (2022). Standard atomic weights of the elements 2021 (IUPAC Technical Report). *Pure and Applied Chemistry, 94*(5), 573–600. https://doi.org/10.1515/pac-2019-0603
