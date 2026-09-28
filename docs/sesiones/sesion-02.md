# Sesión 02: Historia, proceso y técnica de sonomontaje

## Objetivos

- Reconocer las etapas del proceso de postproducción y los roles del equipo.
- Comprender los conceptos de **masa** y **factura** a partir del análisis del objeto sonoro.
- Diferenciar sonidos de masa **tónica, compleja y variable**.
- Diferenciar objetos de factura **impulsiva, formada e iterativa**.
- Aplicar continuidad, contraste y transformación en un sonomontaje.

## Contenidos

La postproducción sonora tiene una historia que va del acompañamiento del cine mudo a los flujos digitales actuales. Conocer esa evolución permite entender **por qué** hoy el sonido audiovisual se organiza como un proceso de selección, transformación, montaje y mezcla.

El proceso puede dividirse en cinco etapas:

1. **Preproducción**: análisis del guion, *spotting* y planificación de necesidades.
2. **Edición**: selección, orden y limpieza de los materiales.
3. **Diseño**: creación, síntesis y transformación de sonidos específicos.
4. **Mezcla**: balance, espacio, perspectiva y coherencia entre capas.
5. **Entrega**: formatos, recopilación y verificación final.

Detrás de estas etapas aparecen distintos roles: **supervisor de sonido, editor de diálogo, editor de efectos, artista Foley, diseñador de sonido, compositor y mezclador**. En producciones pequeñas una misma persona puede asumir varios.

---

## Pierre Schaeffer y el *Tratado de los objetos musicales*

Pierre Schaeffer (1910–1995) fue un ingeniero, compositor e investigador francés, considerado una de las figuras fundamentales de la **música concreta** y del pensamiento electroacústico del siglo XX.

Su obra teórica más importante, el *Traité des objets musicaux* (1966), propone estudiar el sonido no solamente a partir de su causa o de la fuente que lo produce, sino también como un **objeto de percepción** con cualidades propias.

Este enfoque invita a escuchar un sonido preguntándonos, por ejemplo:

- ¿tiene una altura definida o una masa espectral compleja?
- ¿es breve, formado o iterativo?
- ¿cómo evoluciona su energía en el tiempo?
- ¿qué tipo de grano, dinámica o fluctuación presenta?

Esta manera de escuchar es especialmente útil en **postproducción, diseño sonoro y sonomontaje**, porque permite organizar sonidos por sus propiedades perceptivas y no únicamente por su origen.

!!! quote "Idea central"
    El interés no está solo en saber **qué produjo el sonido**, sino en comprender **cómo se comporta y cómo es percibido**.

---

## El objeto sonoro

Para Pierre Schaeffer, un sonido puede estudiarse como **objeto sonoro**: atendiendo a sus cualidades perceptivas y no solamente a la fuente que lo produjo.

Esto permite escuchar una puerta, una voz, un motor o un sintetizador no solo como “cosas que suenan”, sino como materiales que poseen determinadas características internas.

Dos preguntas resultan especialmente útiles para comenzar el análisis:

> **Masa:** ¿cómo se distribuye el sonido en el campo de alturas y frecuencias?

> **Factura:** ¿cómo se constituye y evoluciona ese sonido en el tiempo?

!!! note "Una idea importante"
    Masa y factura son **criterios perceptivos**. No son simplemente sinónimos de “frecuencia” y “envolvente”, aunque tengan correlatos acústicos.

---

## Masa: la materia espectral del sonido

La **masa** generaliza la noción tradicional de altura. En lugar de preguntar únicamente “¿qué nota es?”, podemos preguntar **qué lugar ocupa el sonido dentro del campo de alturas** y si esa organización permanece estable o cambia.

### Masa tónica

Posee una altura claramente reconocible. Puede cantarse o relacionarse con una nota.

**Ejemplos:** flauta, piano, voz cantada, onda sinusoidal.

<div style="max-width:760px;margin:1.5rem auto;">
<svg viewBox="0 0 760 230" width="100%" role="img" aria-label="Representación esquemática de masa tónica">
  <rect x="0" y="0" width="760" height="230" rx="18" fill="currentColor" opacity="0.04"/>
  <line x1="70" y1="185" x2="710" y2="185" stroke="currentColor" opacity="0.35"/>
  <line x1="70" y1="40" x2="70" y2="185" stroke="currentColor" opacity="0.35"/>
  <line x1="250" y1="185" x2="250" y2="70" stroke="currentColor" stroke-width="8"/>
  <line x1="430" y1="185" x2="430" y2="120" stroke="currentColor" stroke-width="5" opacity="0.65"/>
  <line x1="610" y1="185" x2="610" y2="145" stroke="currentColor" stroke-width="4" opacity="0.45"/>
  <text x="235" y="60" font-size="18" fill="currentColor">altura dominante</text>
  <text x="320" y="216" font-size="16" fill="currentColor">frecuencia →</text>
  <text x="12" y="30" font-size="16" fill="currentColor">energía</text>
</svg>
</div>

Aunque un piano tenga numerosos armónicos, el oído puede integrarlos alrededor de una altura principal. Por eso **masa tónica no significa espectro simple**.

#### Escucha · masa tónica

**Tecla de piano · Do4 (C4)**

<audio controls preload="none" style="width:100%">
  <source src="https://raw.githubusercontent.com/mcapodici/pianosounds/master/Piano.mf.C4.ogg" type="audio/ogg">
  Tu navegador no soporta reproducción de audio.
</audio>

*Escucha una altura definida, pero con un espectro más rico que una onda sinusoidal. El ataque y la resonancia propios del piano permiten reconocer con claridad una masa tónica. Fuente: repositorio `mcapodici/pianosounds` en GitHub.*

### Masa compleja

No posee una altura precisa, aunque puede localizarse globalmente como grave, media o aguda.

**Ejemplos:** platillo, golpe metálico, ruido filtrado, fricción.

<div style="max-width:760px;margin:1.5rem auto;">
<svg viewBox="0 0 760 230" width="100%" role="img" aria-label="Representación esquemática de masa compleja">
  <rect x="0" y="0" width="760" height="230" rx="18" fill="currentColor" opacity="0.04"/>
  <line x1="70" y1="185" x2="710" y2="185" stroke="currentColor" opacity="0.35"/>
  <line x1="70" y1="40" x2="70" y2="185" stroke="currentColor" opacity="0.35"/>
  <rect x="180" y="95" width="360" height="70" rx="18" fill="currentColor" opacity="0.18"/>
  <line x1="225" y1="185" x2="225" y2="110" stroke="currentColor" stroke-width="5" opacity="0.6"/>
  <line x1="285" y1="185" x2="285" y2="135" stroke="currentColor" stroke-width="4" opacity="0.55"/>
  <line x1="350" y1="185" x2="350" y2="100" stroke="currentColor" stroke-width="6" opacity="0.7"/>
  <line x1="430" y1="185" x2="430" y2="125" stroke="currentColor" stroke-width="4" opacity="0.5"/>
  <line x1="505" y1="185" x2="505" y2="145" stroke="currentColor" stroke-width="3" opacity="0.45"/>
  <text x="250" y="80" font-size="18" fill="currentColor">zona espectral amplia</text>
  <text x="320" y="216" font-size="16" fill="currentColor">frecuencia →</text>
</svg>
</div>

Una masa compleja **no tiene que ser ruido puro**. Puede contener componentes discretos e inarmónicos y seguir sin ofrecer una altura única reconocible.

#### Escucha · masa compleja

**Crash de platillo**

<audio controls preload="none" style="width:100%">
  <source src="https://commons.wikimedia.org/wiki/Special:Redirect/file/Crash_cymbal.ogg" type="audio/ogg">
  Tu navegador no soporta reproducción de audio.
</audio>

*Observa que podemos percibir una región espectral y un brillo característico, pero no una nota única. Fuente: Wikimedia Commons · Clngre · GFDL.*

### Masa variable

La organización espectral cambia a lo largo del tiempo.

Puede ocurrir con una altura definida —por ejemplo, un glissando— o con una masa compleja que cambia de región espectral.

**Ejemplos:** glissando de violín, chirrido, barrido de filtro, ruido que asciende progresivamente de grave a agudo.

<div style="max-width:760px;margin:1.5rem auto;">
<svg viewBox="0 0 760 250" width="100%" role="img" aria-label="Representación esquemática de masa variable">
  <rect x="0" y="0" width="760" height="250" rx="18" fill="currentColor" opacity="0.04"/>
  <line x1="70" y1="205" x2="710" y2="205" stroke="currentColor" opacity="0.35"/>
  <line x1="70" y1="40" x2="70" y2="205" stroke="currentColor" opacity="0.35"/>
  <path d="M120 180 C240 170, 330 130, 430 105 S600 70, 675 55" fill="none" stroke="currentColor" stroke-width="10" stroke-linecap="round"/>
  <text x="275" y="88" font-size="18" fill="currentColor">la masa cambia con el tiempo</text>
  <text x="335" y="235" font-size="16" fill="currentColor">tiempo →</text>
  <text x="8" y="35" font-size="16" fill="currentColor">registro</text>
</svg>
</div>

#### Escucha · masa variable

**Glissando de arpa**

<audio controls preload="none" style="width:100%">
  <source src="https://commons.wikimedia.org/wiki/Special:Redirect/file/Gliss.ogg" type="audio/ogg">
  Tu navegador no soporta reproducción de audio.
</audio>

*La posición de la masa cambia claramente en el registro a lo largo del tiempo. Fuente: Wikimedia Commons · Daniel Musiklexikon · dominio público.*

---

## Factura: cómo existe el sonido en el tiempo

La **factura** describe la manera en que el objeto se constituye temporalmente: cómo aparece, se sostiene, desaparece o se repite.

Para esta sesión trabajaremos tres comportamientos fundamentales:

### Impulsión

Objeto muy breve, dominado por un ataque.

**Ejemplos:** palmada, clic, golpe de madera, pizzicato seco.

<audio controls preload="none" style="width:100%">
  <source src="https://commons.wikimedia.org/wiki/Special:Redirect/file/Clap1.ogg" type="audio/ogg">
  Tu navegador no soporta reproducción de audio.
</audio>

*Ejemplo: palmada breve. Fuente: Wikimedia Commons · WikiGrower1 · CC BY 4.0.*

### Formado

El sonido presenta continuidad perceptible en el tiempo.

**Ejemplos:** nota larga de violín, vocal sostenida, ruido continuo, resonancia prolongada de un gong.

### Iteración

Una serie de impulsos próximos se percibe como un solo objeto organizado por repetición.

**Ejemplos:** redoble, trémolo, maraca, vibración mecánica.

**Maracas**

<audio controls preload="none" style="width:100%">
  <source src="https://commons.wikimedia.org/wiki/Special:Redirect/file/Maracas.ogg" type="audio/ogg">
  Tu navegador no soporta reproducción de audio.
</audio>

**Redoble**

<audio controls preload="none" style="width:100%">
  <source src="https://commons.wikimedia.org/wiki/Special:Redirect/file/Drum_Roll_Intro.ogg" type="audio/ogg">
  Tu navegador no soporta reproducción de audio.
</audio>

*En ambos casos, múltiples impulsos próximos se integran perceptivamente como un objeto iterativo. Fuentes: Wikimedia Commons; Maracas, dominio público; Drum Roll Intro, CC0.*

<div style="max-width:860px;margin:1.5rem auto;">
<svg viewBox="0 0 860 330" width="100%" role="img" aria-label="Comparación gráfica entre impulsión, mantenimiento e iteración">
  <rect x="0" y="0" width="860" height="330" rx="18" fill="currentColor" opacity="0.04"/>

  <text x="28" y="72" font-size="19" fill="currentColor">Impulsión</text>
  <line x1="160" y1="70" x2="815" y2="70" stroke="currentColor" opacity="0.22"/>
  <path d="M185 70 L245 70 L258 22 L272 70 L800 70" fill="none" stroke="currentColor" stroke-width="5"/>

  <text x="28" y="166" font-size="19" fill="currentColor">Formado</text>
  <line x1="160" y1="165" x2="815" y2="165" stroke="currentColor" opacity="0.22"/>
  <path d="M185 165 L230 165 Q250 115 285 115 L650 115 Q690 115 720 165 L800 165" fill="none" stroke="currentColor" stroke-width="5"/>

  <text x="28" y="260" font-size="19" fill="currentColor">Iteración</text>
  <line x1="160" y1="258" x2="815" y2="258" stroke="currentColor" opacity="0.22"/>
  <path d="M185 258 L215 258 L225 215 L238 258 L270 258 L280 215 L293 258 L325 258 L335 215 L348 258 L380 258 L390 215 L403 258 L435 258 L445 215 L458 258 L490 258 L500 215 L513 258 L545 258 L555 215 L568 258 L600 258 L610 215 L623 258 L655 258 L665 215 L678 258 L800 258" fill="none" stroke="currentColor" stroke-width="4"/>

  <text x="430" y="312" font-size="16" fill="currentColor">tiempo →</text>
</svg>
</div>

---

## Cruzar masa y factura

La utilidad del sistema aparece cuando describimos simultáneamente **qué tipo de materia sonora tenemos** y **cómo se comporta temporalmente**.

| Sonido | Masa | Factura |
|---|---|---|
| Nota de piano | Tónica | Impulsiva / resonante |
| Violín sostenido | Tónica | Formada |
| Trémolo de mandolina | Tónica | Iterativa |
| Golpe de platillo | Compleja | Impulsiva / resonante |
| Ruido blanco continuo | Compleja | Formada |
| Maraca | Compleja | Iterativa |
| Glissando | Tónica variable | Formada |
| Barrido de ruido filtrado | Compleja variable | Formada |

<div style="max-width:760px;margin:1.5rem auto;">
<svg viewBox="0 0 760 390" width="100%" role="img" aria-label="Matriz de masa y factura">
  <rect x="0" y="0" width="760" height="390" rx="18" fill="currentColor" opacity="0.04"/>
  <text x="300" y="35" font-size="20" fill="currentColor">FACTURA →</text>
  <text x="18" y="210" font-size="20" fill="currentColor" transform="rotate(-90 18 210)">MASA →</text>

  <line x1="130" y1="70" x2="700" y2="70" stroke="currentColor" opacity="0.45"/>
  <line x1="130" y1="150" x2="700" y2="150" stroke="currentColor" opacity="0.25"/>
  <line x1="130" y1="230" x2="700" y2="230" stroke="currentColor" opacity="0.25"/>
  <line x1="130" y1="310" x2="700" y2="310" stroke="currentColor" opacity="0.45"/>

  <line x1="130" y1="70" x2="130" y2="310" stroke="currentColor" opacity="0.45"/>
  <line x1="320" y1="70" x2="320" y2="310" stroke="currentColor" opacity="0.25"/>
  <line x1="510" y1="70" x2="510" y2="310" stroke="currentColor" opacity="0.25"/>
  <line x1="700" y1="70" x2="700" y2="310" stroke="currentColor" opacity="0.45"/>

  <text x="185" y="58" font-size="16" fill="currentColor">Impulsiva</text>
  <text x="375" y="58" font-size="16" fill="currentColor">Formada</text>
  <text x="575" y="58" font-size="16" fill="currentColor">Iterativa</text>

  <text x="58" y="115" font-size="16" fill="currentColor">Tónica</text>
  <text x="38" y="195" font-size="16" fill="currentColor">Compleja</text>
  <text x="42" y="275" font-size="16" fill="currentColor">Variable</text>

  <text x="175" y="115" font-size="15" fill="currentColor">piano</text>
  <text x="365" y="115" font-size="15" fill="currentColor">violín</text>
  <text x="555" y="115" font-size="15" fill="currentColor">trémolo</text>

  <text x="168" y="195" font-size="15" fill="currentColor">platillo</text>
  <text x="355" y="195" font-size="15" fill="currentColor">ruido</text>
  <text x="565" y="195" font-size="15" fill="currentColor">maraca</text>

  <text x="160" y="275" font-size="15" fill="currentColor">impacto + cambio</text>
  <text x="355" y="275" font-size="15" fill="currentColor">glissando</text>
  <text x="555" y="275" font-size="15" fill="currentColor">pulso variable</text>
</svg>
</div>

---

## Del análisis al sonomontaje

Montar sonido no consiste únicamente en colocar clips uno detrás de otro. Consiste en establecer relaciones perceptivas entre objetos.

Podemos trabajar tres operaciones:

### Continuidad

Unir sonidos que comparten alguna característica.

Por ejemplo:

- masa semejante;
- registro semejante;
- factura semejante;
- dinámica similar;
- textura o grano próximos.

### Contraste

Yuxtaponer sonidos que presentan diferencias claras.

Por ejemplo:

- tónico → complejo;
- grave → agudo;
- impulsivo → formado;
- silencio → sonido denso;
- estable → variable.

### Transformación

Construir un paso gradual entre estados.

Por ejemplo:

**golpe aislado → repetición → textura continua**

o:

**masa grave → masa media → masa aguda**

Esto convierte el sonomontaje en una forma de organización musical del sonido, incluso cuando el material original proviene de objetos cotidianos.

---

## Más allá de masa y factura

Masa y factura son una entrada al análisis. Otros criterios de la morfología schaefferiana permiten describir el objeto con mayor detalle:

- **timbre armónico**
- **grano**
- **allure** o fluctuación característica
- **dinámica**
- **perfil melódico**
- **perfil de masa**

En esta sesión nos concentraremos en masa y factura para construir una primera herramienta de escucha y montaje.

---

## Actividades

!!! tip "Ejercicio rápido de escucha"
    Reproduce los ejemplos anteriores **sin mostrar inicialmente su clasificación**. Pide al grupo que responda primero:  
    1. ¿Hay una altura definida?  
    2. ¿La masa permanece estable o cambia?  
    3. ¿Es un impulso, un sonido formado o una iteración?

1. **Escucha inicial:** identificar rápidamente si distintos sonidos son tónicos, complejos o variables.
2. **Clasificación temporal:** reconocer impulsión, mantenimiento e iteración.
3. **Matriz masa × factura:** clasificar entre 8 y 12 sonidos proporcionados por el docente.
4. Audición y discusión de la obra *Fragtraz* u otro referente de montaje sonoro.
5. Demostración en Ableton Live de:
   - corte;
   - fundidos;
   - superposición;
   - cambios de ganancia;
   - inversión;
   - *time-stretching*;
   - organización temporal.
6. **Práctica guiada:** crear un sonomontaje de 30 segundos utilizando al menos:
   - un objeto de masa tónica;
   - un objeto de masa compleja;
   - un objeto de comportamiento variable;
   - una impulsión;
   - un sonido formado;
   - una iteración.
7. Escucha colectiva: cada grupo explica una decisión de **continuidad**, una de **contraste** y una de **transformación**.

---

## Actividad autónoma

Realizar un **sonomontaje de un minuto** construido a partir de **seis a diez sonidos**.

El montaje debe incluir conscientemente:

- al menos **dos tipos distintos de masa**;
- al menos **dos tipos distintos de factura**;
- una relación de **continuidad**;
- una relación de **contraste**;
- una **transformación gradual**.

### Entrega

1. Audio final.
2. Proyecto de Ableton Live recopilado.
3. Una breve descripción en la que se identifique:
   - masa de los sonidos principales;
   - factura de los sonidos principales;
   - criterio utilizado para unirlos o contrastarlos.

---

## Preguntas de cierre

- ¿Dos sonidos producidos por fuentes completamente diferentes pueden tener una masa semejante?
- ¿Un sonido puede cambiar de masa durante su duración?
- ¿Cuándo una serie de impulsos comienza a percibirse como una textura?
- ¿Qué ocurre si montamos sonidos según sus propiedades perceptivas y no según su fuente?
- ¿Cómo puede un cambio de masa o factura ayudar a construir una transición audiovisual?

---

## Recursos

- Schaeffer, Pierre. *Traité des objets musicaux* (1966).
- Schaeffer, Pierre. *Treatise on Musical Objects: An Essay Across Disciplines*. University of California Press, 2017.
- Obra de referencia: *Fragtraz* u otro montaje sonoro seleccionado para la clase.
- Material complementario sobre tipología y morfología del objeto sonoro disponible en Classroom.
- [GitHub · mcapodici/pianosounds · Piano.mf.C4.ogg](https://github.com/mcapodici/pianosounds/blob/master/Piano.mf.C4.ogg)
- [Wikimedia Commons · Crash cymbal](https://commons.wikimedia.org/wiki/File:Crash_cymbal.ogg)
- [Wikimedia Commons · Gliss](https://commons.wikimedia.org/wiki/File:Gliss.ogg)
- [Wikimedia Commons · Clap1](https://commons.wikimedia.org/wiki/File:Clap1.ogg)
- [Wikimedia Commons · Maracas](https://commons.wikimedia.org/wiki/File:Maracas.ogg)
- [Wikimedia Commons · Drum Roll Intro](https://commons.wikimedia.org/wiki/File:Drum_Roll_Intro.ogg)

---

*Herramientas: Ableton Live, Google Classroom.*
