§G

Reposicionar portafolio: liderazgo + datos → valor de negocio; tecnología → habilitador.

§C

- Mantener sitio estático GitHub Pages; `index.html` autocontenido.
- Mantener diseño visual, responsive, animaciones, enlaces y descarga CV funcionales.
- Usar solo experiencia, cifras y credenciales ya verificables en repo; ⊥ inventar cargos, equipos, alcance o resultados.
- Liderazgo = iniciativa, priorización, articulación entre áreas, adopción y decisiones; ⊥ afirmar gestión formal de personas sin evidencia.
- Datos = diagnóstico, control, trazabilidad y decisión; ⊥ lista aislada de herramientas.
- Español claro, ejecutivo, concreto; conservar entidades HTML existentes donde corresponda.

§I

web: `index.html` → GitHub Pages single-page portfolio
asset: `assets/CV_Juan_Pablo_Canales_Product_Engineer.pdf` → descarga CV vigente
doc: `README.md` → resumen público repo
nav: `#about`, `#stack`, `#experience`, `#projects`, `#certifications`, `#contact`

§V

V1: primer pantallazo comunica liderazgo + datos + valor antes de herramientas digitales
V2: propuesta de valor prueba impacto con `CLP 200 millones`, `10 horas semanales`, `nueve áreas`
V3: tecnología descrita como medio subordinado a problema, decisión o resultado
V4: liderazgo descrito mediante conductas verificables; ⊥ jefatura formal no demostrada
V5: experiencia + proyectos usan secuencia contexto → decisión/iniciativa → resultado → herramienta
V6: sección principal de capacidades prioriza liderazgo, negocio y datos; stack técnico queda secundario
V7: metadatos, intro, hero, contacto y `README.md` sostienen mismo posicionamiento
V8: ∀ enlaces internos/externos + descarga CV permanecen válidos
V9: sitio conserva legibilidad desktop/móvil y respeto por `prefers-reduced-motion`
V10: ⊥ nuevas cifras, credenciales o alcances no presentes en fuente actual

§T

id|status|task|cites
T1|x|reescribir metadatos + intro + hero alrededor de liderazgo, datos, impacto|V1,V2,V3,V7,V10,I.web
T2|x|convertir competencias en capacidades de liderazgo, negocio y datos; relegar stack|V3,V4,V6,V10,I.nav
T3|x|reestructurar experiencia + proyectos con narrativa de decisiones y valor|V2,V3,V4,V5,V10,I.web
T4|x|alinear navegación + formación + contacto + `README.md`; conservar interfaces|V7,V8,I.asset,I.doc,I.nav
T5|x|validar HTML, anclas, enlaces, responsive, accesibilidad básica y movimiento reducido|V8,V9,I.web

§B

id|date|cause|fix
B1|2026-09-25|verificador esperaba `&mdash;`; fuente usa `—`|corregir literal de prueba
B2|2026-09-25|verificador asumió breakpoint `768px`; fuente usa `860px`|validar breakpoint existente + viewport real
