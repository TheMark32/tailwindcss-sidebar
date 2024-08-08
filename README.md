# HTML Template with Tailwind CSS

Acesta este un template HTML simplu care folosește Tailwind CSS pentru a crea un fundal gradient și un sidebar care apare/dispare la activarea unui checkbox.

## Descriere

Codul HTML include un simplu document care conține următoarele elemente:

- **Checkbox fixat**: Este plasat în colțul din stânga sus al paginii. Când este bifat, va activa sidebar-ul.
- **Sidebar ascuns**: Acesta este plasat în stânga ecranului și apare/dispare printr-o tranziție lină atunci când checkbox-ul este bifat.

## Structura codului

- **head**: Include Tailwind CSS pentru stilizarea paginii.
- **body**: Conține un checkbox care controlează apariția sidebar-ului și un aside care reprezintă sidebar-ul.

## Funcționalități

- **Checkbox**: Când este bifat, sidebar-ul se va muta de la poziția ascunsă (în afara ecranului) la poziția vizibilă.
- **Sidebar**: Este stilizat cu o culoare de fundal întunecată și apare cu o tranziție lină de 500ms.

## Utilizare

1. Deschide fișierul `index.html` în browserul tău.
2. Bifează checkbox-ul din colțul stânga-sus pentru a vizualiza sidebar-ul.

## Dependențe

- **Tailwind CSS**: Este folosit pentru stilizarea rapidă a paginii. Este inclus din CDN.
