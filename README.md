# Sito personale, Beruch Ibala

Sito portfolio personale realizzato in HTML, CSS (Sass) e Bootstrap, nell'ambito del Master in IA e Agenti IA per il Business (Università degli Studi Guglielmo Marconi con start2impact).

Sito online: https://beruchbordey-glitch.github.io/progetto-HTML-E-CSS/

## Pagine

- `index.html`, Home : bio, competenze, progetti
- `cv.html`, CV in formato HTML
- `contact.html`, pagina contatti con form

## Requisiti tecnici soddisfatti

| Requisito | Dove e come |

| HTML e CSS | Tutte le pagine |
| Almeno 2 pagine (di cui CV in HTML) | 3 pagine, CV incluso |
| Pagina "Contattami" con form | `contact.html` (campi `required`) |
| Framework front end | Bootstrap 5 (navbar, griglia, utility) |
| Favicon | SVG inline nel `<head>` |
| Menu sticky | `.navbar { position: sticky }` (desktop e mobile) |
| Flexbox e Grid | Grid (competenze, progetti) e Flexbox (hero, card) |
| Sass | `scss/style.scss` compilato in `css/style.css` |
| Responsive 100% | Viewport, Grid auto fit, Bootstrap, unità fluide |
| Open Graph | Meta tag OG in ogni pagina |

## Struttura


progetto-HTML-E-CSS/
├── index.html
├── cv.html
├── contact.html
├── README.md
├── scss/
│   └── style.scss      (sorgente Sass, commentato)
├── css/
│   └── style.css       (CSS compilato, caricato dalle pagine)
└── img/
    └── photoprofil.jpg


## Compilare il Sass

```bash
sass scss/style.scss css/style.css
```

## Autore

Beruch Ibala, Data Analyst & Junior Data Scientist
