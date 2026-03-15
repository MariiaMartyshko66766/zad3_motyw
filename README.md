# Zadanie 3 – Drugi motyw kolorystyczny (CSS)

## Autor
Martyshko Mariia  
ID studenta: 66766

## Opis projektu

Projekt przedstawia stronę CV stworzoną w HTML z możliwością zastosowania dwóch różnych motywów kolorystycznych przy użyciu dwóch arkuszy stylów CSS.

Celem zadania było pokazanie, że ta sama struktura HTML może mieć różny wygląd w zależności od podłączonego arkusza stylów.

## Struktura projektu

W katalogu `zad3_motyw` znajdują się następujące pliki:

- `index.html` – struktura strony CV
- `red.css` – motyw kolorystyczny w odcieniach czerwieni (domyślny)
- `green.css` – motyw kolorystyczny w odcieniach zieleni

## Działanie

Domyślnie strona korzysta z pliku `red.css`, dlatego wyświetla się w czerwonej kolorystyce.

Aby zobaczyć zielony motyw, należy w pliku `index.html` zmienić podłączony arkusz stylów z:

```html
<link rel="stylesheet" href="red.css">
