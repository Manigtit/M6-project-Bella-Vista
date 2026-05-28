Teknisk dokumentation

## Kort beskrivelse

Bella Vista Restaurant er en statisk hjemmeside bygget med HTML, CSS, Bootstrap og lidt JavaScript.

Projektet består af flere HTML-sider, to CSS-filer, en JavaScript-fil og en mappe med billeder.

## Filstruktur

```text
Bella Vista Restaurant/
│
├── index.html
├── menu.html
├── about.html
├── gallery.html
├── reservations.html
├── reviews.html
├── faq.html
├── contact.html
│
├── css/
│   ├── global.css
│   └── style.css
│
├── js/
│   └── booking-confirmation.js
│
└── assets/
    └── images/
```

## HTML

HTML-filerne bruges til de forskellige sider på hjemmesiden. Hver side har sin egen funktion, for eksempel menu, reservation eller kontakt.

De vigtigste sider er:

- `index.html`: Forsiden
- `menu.html`: Restaurantens menu
- `reservations.html`: Side til bordreservation
- `contact.html`: Kontaktinformation

## CSS

Projektet har to CSS-filer:

- `global.css`
- `style.css`

CSS bruges til at styre farver, layout, knapper, kort, tekst og det generelle visuelle udtryk.

`global.css` indeholder styling for hele hjemmesiden, herunder farvevariabler, typografi osv., som genbruges på tværs af alle sider. `style.css` indeholder derimod styling til specifikke sider. Denne opdeling gør strukturen mere overskuelig og lettere at vedligeholde.

## JavaScript

Projektet bruger filen `booking-confirmation.js`.

JavaScript bruges til at give brugeren en bekræftelse ved reservation. Det gør siden lidt mere interaktiv, selvom projektet stadig primært er en statisk hjemmeside.

## Bootstrap

Vi har brugt Bootstrap til at hjælpe med layout, genbruglige komponenter og responsivt design. Det gør det nemmere at oprette komponenter såsom knapper, inputfelter og cards, der fungerer på forskellige skærmstørrelser.

## Sådan køres projektet

Projektet kræver ikke installation af database eller server.

Man kan åbne projektet sådan:

1. Download eller klon projektet fra GitHub
2. Åbn projektmappen
3. Dobbeltklik på `index.html`
4. Hjemmesiden åbner i browseren

## Versionsstyring

Vi har brugt Git og GitHub til versionsstyring. Det betyder, at ændringer i projektet kunne gemmes undervejs, og at gruppen kunne arbejde sammen i samme repository.

Vi har også arbejdet med branches for at mindske konflikter, når flere arbejdede på forskellige dele af projektet.
