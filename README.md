# Newton VR · ¿Qué fuerza necesito?

Juego educativo de física para la Gala Tecnológica: empuja una caja, descubre cuándo se rompe la fricción estática y detenla dentro de la zona meta usando la fricción cinética.

**Jugar en línea:** https://xiaoting507.github.io/newton-vr/

## Qué enseña
- Diagrama de Cuerpo Libre en tiempo real (N, P, F, f).
- Fricción estática (f = F hasta μsN) y cinética (f = μkN).
- Segunda ley de Newton: a = (F − fk) / m.
- Gráfica en vivo de fricción contra fuerza aplicada.

## Modos
- **Desafío:** 3 niveles (madera 10 kg, hielo 10 kg, rugosa 15 kg), 15 s cada uno, con marcador.
- **Explorar:** cambia superficie y masa libremente.
- **Cuestionario:** 6 preguntas antes y después de jugar.

## Controles
- Mantén **EMPUJAR** o la barra espaciadora para subir la fuerza.
- Arrastra la barra de fuerza para fijar un valor exacto.
- Mando USB: gatillo derecho (RT/R2). `R` reinicia, `Esc` vuelve al menú.

## Modo VR (WebXR)
1. En las gafas (Meta Quest, Pico u otras), abre el navegador y entra a https://xiaoting507.github.io/newton-vr/
2. Toca **Entrar en VR** y acepta el permiso.
3. Controles dentro de VR:
   - **Gatillo** (analógico): fuerza aplicada de 0 a 150 N según cuánto lo presiones.
   - **A / X**: opción principal (Desafío, Empezar, Siguiente nivel).
   - **B / Y**: opción secundaria (Explorar, Reintentar) o reiniciar la caja.
   - **Stick ← →**: cambiar superficie · **↑ ↓**: cambiar masa (modo Explorar).
   - **Clic en el stick**: volver al menú.
4. El control vibra mientras la fricción estática aguanta y al romperse.

El modo VR necesita internet (carga three.js) y el link https. El archivo local funciona sin VR.

## Jugar sin internet
Descarga `index.html` y ábrelo con doble clic en cualquier navegador.
