# Pendiente de completar

He rellenado la web con datos públicos de tu ORCID, el Portal de Recerca de la UAB, GitHub y UAB Divulga.
Esto es lo que falta o conviene revisar. Escribe tus respuestas aquí debajo de cada punto (o pásame las fotos) y lo incorporo.

> Este fichero no se publica en la web (está excluido en `_config.yaml`).

---

## 1. Fotos

Ahora todas las imágenes son las de la plantilla (`images/photo.jpg`, `images/background.jpg`). Necesitaría:

- [ ] **Foto tuya** (retrato, idealmente cuadrada) → página de inicio y perfil
- [ ] **Imagen de cabecera/fondo** (`images/background.jpg`), p. ej. una foto de laboratorio, de moscas, un gráfico tuyo…
- [ ] **Imágenes para las tarjetas de inicio**: Research, Projects, Resources, CV
- [ ] **Imágenes para los proyectos y recursos** (opcional): URBANOMICS (mosquito), CATick (garrapata), iMKT, DEST, DrosOmics, PopHumanScan
- [ ] **Logo / icono** del sitio (`images/logo.svg`, `images/icon.png`), si quieres uno propio

## 2. Contacto

- [x] **Email**: he puesto `marta.coronado@uab.cat` (sacado del README de TAB). Cámbialo si prefieres otro.
- [ ] **Despacho / dirección exacta** (edificio, despacho):
- [ ] ¿Quieres mostrar **teléfono**? (Sí/No, cuál):
- [ ] ¿Sigues usando **Twitter/X @geneticament**? ¿Tienes Bluesky, LinkedIn, ResearchGate…?

## 3. Publicaciones (Google Scholar)

Ahora las publicaciones se cargan **automáticamente desde tu ORCID** (32 entradas, incluyendo dos de UAB Divulga).

- [ ] **Tu ID de Google Scholar** (lo que va tras `user=` en la URL de tu perfil):
- [ ] Para que la web lea Google Scholar automáticamente hace falta una **clave de SerpAPI** (servicio de pago con plan gratuito, 100 búsquedas/mes), que se guarda como secret `GOOGLE_SCHOLAR_API_KEY` en GitHub. ¿Quieres hacerlo?
  - Alternativa sin clave: me dices qué preprints de bioRxiv o artículos faltan y los añado a mano en `_data/sources.yaml`.
- [ ] ¿Hay más artículos de **divulgación** (UAB Divulga, The Conversation, prensa…) aparte de los dos de 2018 y 2019?
- [ ] ¿Qué **3 publicaciones** quieres destacar? Ahora mismo: Genome Biology 2025 (TEs y epigenética), MBE 2018 (selección en el embrión) y NAR 2019 (iMKT).

## 4. Texto de presentación

He redactado una bio breve en inglés a partir de tu ORCID. Revísala en `index.md` y `research/index.md`.

- [ ] ¿La web en **inglés**, castellano, catalán o bilingüe?
- [ ] Tu **línea de investigación actual** como lecturer (¿mosquitos urbanos, garrapatas, ratones salvajes…?) en 3-5 frases:
- [ ] ¿Tienes **grupo** propio o formas parte de alguno en la UAB (p. ej. Bioinformàtica de la Diversitat Genòmica)?

## 5. CV

- [ ] **Docencia**: la pestaña Teaching muestra TAB y Bioestadística (UAB), y Data Visualization y Phylogenomics (UPC). ¿Sigues en la UPC? ¿Quito alguno o añado otras asignaturas?
- [ ] **Licencia de los materiales docentes**: ahora tienen GPL (GPL-3.0; Data Visualization GPL-2.0), que está pensada para código. Para apuntes y diapositivas lo habitual es **Creative Commons**: CC BY 4.0 (reutilización libre citándote) o CC BY-NC-SA 4.0 (sin uso comercial y compartiendo igual). Una opción común es CC para el contenido y MIT/GPL para el código. ¿Cuál prefieres?
- [ ] **Estancias** de investigación (p. ej. Helsinki con Isaac Salazar-Ciudad, Brighton con Adam Eyre-Walker…):
- [ ] **Becas y premios** (FPI/FPU, Juan de la Cierva, Beatriu de Pinós, premios de tesis…):
- [ ] **Dirección de estudiantes** (TFG, TFM, tesis):
- [ ] **Comunicaciones en congresos** destacadas, charlas invitadas:
- [ ] **Divulgación/outreach** (Setmana de la Ciència, etc.):
- [ ] **Revisora** de revistas, comités, gestión:
- [ ] ¿Quieres un **PDF del CV** descargable? Pásamelo y lo enlazo.

## 6. Proyectos y herramientas

- [ ] Revisa las fechas y tu rol en cada proyecto (sacados del Portal de Recerca UAB).
- [ ] ¿Otros proyectos o software tuyos que añadir? ¿Quieres quitar alguno?
- [ ] Webs de iMKT y DrosOmics: no respondían, así que enlazan al artículo. ¿Tienen URL activa?

## 7. Otros

- [ ] El **blog** está oculto del menú (y he borrado los posts de ejemplo). ¿Lo quieres activar?
- [ ] La URL será `marta-coronado.github.io/adaptomics`. ¿Te gusta el nombre "adaptomics" o prefieres otro (p. ej. un dominio propio)?
