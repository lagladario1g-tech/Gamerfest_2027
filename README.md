# Gamer Fest ESPE 2027

Landing page responsiva (enfoque **Mobile First**) de un torneo universitario de videojuegos.
Proyecto académico de la asignatura **Programación Web**.



- Repositorio: <https://github.com/lagladario1g-tech/Gamerfest_2027>
- Código del documento de requisitos: ERS-GF-2027

## Tecnologías

- HTML5 semántico
- Bootstrap 5.3.8 (CDN): Grid, utilidades, navbar y componentes de formulario


## Cómo ejecutarlo

1. Clona el repositorio:
   ```
   git clone https://github.com/lagladario1g-tech/Gamerfest_2027.git
   ```
2. Abre `index.html` en un navegador moderno (Chromium o Firefox).
3. Se necesita conexión a Internet: Bootstrap y el mapa de Google Maps se cargan desde servicios externos.

## Estructura del repositorio

```
Gamerfest_2027/
├── index.html
├── README.md
├── diseno-movil.png          
├── diseno-escritorio.png     
└── images/
    ├── logo.png
    ├── hero.jpg, hero3.jpg
    ├── cat-battle-royale.jpg, cat-carreras2.jpg, cat-futbol.jpg, cat-estrategia.jpg
    ├── premio-1.jpg, premio-2.jpg, premio-3.jpg
    ├── espe.png, espe-neon.jpg, ausp-1.png, ausp-2.png
    └── red-instagram.png, red-facebook.png, red-tiktok.png
```

## Secciones de la página

1. **Encabezado y navbar:** logo, nombre del evento y menú con enlaces ancla (colapsa bajo `lg`).
2. **Hero / invitación:** título, descripción, fecha, horario, lugar y botón «Inscríbete ahora».
3. **Categorías:** Battle Royale, Carreras, Fútbol virtual y Estrategia en equipo.
4. **Premios:** 1.er, 2.º y 3.er lugar, con sus condiciones.
5. **Auspiciantes:** ESPE, PixelByte y NeoLan Café.
6. **Ubicación:** mapa de Google Maps, texto de respaldo y enlace alternativo.
7. **Inscripción:** tres pasos previos y formulario
8. **Pie de página:** identificación del evento y redes sociales (Instagram, Facebook y TikTok).




## Diseño responsivo

Los cambios de distribución se activan desde el breakpoint `lg` (≥ 992 px) con clases de Bootstrap.
La verificación se realiza a **375 px** (móvil) y **1440 px** (escritorio).

| Componente   | Móvil 375 px               | Escritorio 1440 px                       |
|--------------|----------------------------|------------------------------------------|
| Navbar       | Menú colapsado             | Menú horizontal                          |
| Hero         | Texto e imagen apilados    | Dos columnas                             |
| Categorías   | Una tarjeta por fila       | Cuatro tarjetas por fila                 |
| Premios      | Bloques verticales         | Tres bloques en línea (podio)            |
| Auspiciantes | Uno por fila               | Tres por fila                            |
| Mapa         | 100 % del ancho disponible | Columna izquierda, junto al formulario   |
| Formulario   | Un campo por fila          | Columna derecha, dos campos por fila     |
| Footer       | Centrado y apilado         | Distribución horizontal                  |

## Requisitos cubiertos

| Requisito | Descripción | Estado |
|-----------|-------------|--------|
| RF-01 | Encabezado y navegación | ✅ |
| RF-02 | Invitación e información | ✅ |
| RF-03 | Categorías y premios | ✅ |
| RF-04 | Auspiciantes (señalados como simulados) | ✅ |
| RF-05 | Mapa  del evento con respaldo textual | ✅ |
| RF-06 | Campos del formulario | POR DEFINIR |
| RF-07 | Validaciones del formulario | POR DEFINIR |
| RF-08 | Confirmación demostrativa | POR DEFINIR |
| RF-09 | Pie de página y redes | ✅ |
| RF-10 | Navegación por secciones | ✅ |
| RNF-01 / 02 | Mobile First y escritorio | ✅ |
| RNF-03 | Grid Bootstrap e `img-fluid` | ✅ |
| RNF-04 | Accesibilidad básica | ✅ |
| RNF-05 | Compatibilidad | ✅ |
| RNF-06 | Mantenibilidad y README | ✅ |
| RNF-07 | Privacidad de la demostración | POR DEFINIR |
| RNF-08 | Versionamiento en Git y GitHub | ✅|

## Pruebas

Las evidencias con capturas a 375 px y 1440 px estarán en `pruebas.doc`.

| Caso | Prueba | Resultado |
|------|--------|-----------|
| CP-01 | Abrir en 375 px: diseño vertical sin desplazamiento horizontal | ☐ |
| CP-02 | Abrir en 1440 px: navbar y tarjetas en columnas | ☐ |
| CP-03 | Abrir el menú móvil | ☐ |
| CP-04 | Pulsar «Inscríbete ahora» (va al formulario) | ☐ |
| CP-05 | Enviar el formulario vacío | ☐ |
| CP-06 | Correo con dominio distinto a ESPE | ☐ |
| CP-07 | Archivo mayor a 2 MB o de tipo inválido | ☐ |
| CP-08 | Datos simulados válidos (confirmación) | ☐ |
| CP-09 | Abrir el mapa y las redes | ☐ |
| CP-10 | Revisar GitHub: archivos, README y al menos 4 commits | ☐ |

## Control de versiones

Estado actual: 2 commits en la rama `main`. 

## Privacidad

La página no guarda datos. Las pruebas del formulario deben hacerse solo con datos
ficticios, y no se suben comprobantes de pago ni datos de terceros al repositorio.

## Autor

- Nombre: DARIO MOISES LAGLA ABATA
- Usuario de GitHub: [lagladario1g-tech](https://github.com/lagladario1g-tech)
- Asignatura: Programación Web
- Universidad de las Fuerzas Armadas ESPE