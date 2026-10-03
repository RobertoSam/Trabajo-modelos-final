# Solucionario: regresión lineal múltiple, polinomial y Ridge

Curso **Modelos de Aprendizaje Automático** · MMC–IMCA.

Solución de dos listas de ejercicios (30 en total):

- **Parte I · Regresión lineal múltiple** (15): costo $J(\beta)$, gradiente, ecuaciones normales, Hessiana, colinealidad, descenso del gradiente y su convergencia, reescalamiento, modelos anidados.
- **Parte II · Regresión polinomial y Ridge** (15): matriz de diseño polinomial, estandarización, solución cerrada de Ridge, contracción en la base propia, efecto de las unidades, descenso del gradiente con penalización.

Cada ejercicio incluye **enunciado**, **base teórica** y **solución paso a paso**. Los resultados numéricos se verificaron con aritmética racional exacta (SymPy).

## Cómo verlo

Abre [`index.html`](index.html) en un navegador. Las fórmulas se renderizan con MathJax, así que necesita conexión a internet.

Notación: $J(\beta)=\frac{1}{2n}\|y-X\beta\|^2$, $\nabla J=\frac1n X^\top(X\beta-y)$, $H=\frac1n X^\top X$, y para Ridge $J_\lambda(\beta)=\frac1{2n}\left(\|y-Z\beta\|^2+\lambda\|\beta\|^2\right)$.
