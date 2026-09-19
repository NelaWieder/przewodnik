# Przewodnik: Indonezja i Singapur

Jednoplikowa strona z przewodnikiem po Singapurze, Jawie, Borneo, Bali i Flores:
313 miejsc z opisami i ocenami, gotowe plany dni, mapa stref, rezerwacje,
budżet, listy „co zabrać” i dział praktyczny.

## Publikacja na GitHub Pages

1. Nowe repozytorium (**Public**), np. `indonezja`.
2. **Add file → Upload files** → wgraj `index.html` (i ten plik `README.md`) → **Commit changes**.
3. **Settings → Pages → Source: Deploy from a branch**, gałąź `main`, katalog `/ (root)` → **Save**.
4. Po 1–3 minutach strona działa pod `https://TWOJ-LOGIN.github.io/indonezja/`.

## Aktualizacja

Wgraj nowy `index.html` o tej samej nazwie (Upload files nadpisze stary) albo
kliknij ołówek przy pliku i wklej nową treść. Zmiany widać po chwili; w telefonie
warto odświeżyć stronę.

## Dane użytkownika

Plany dni, rezerwacje, wydatki, notatki i zaznaczenia zapisują się wyłącznie
w pamięci przeglądarki (localStorage) na urządzeniu, na którym je wpisano.
Nie trafiają do repozytorium ani na serwer, nie synchronizują się między telefonami.

Przeniesienie danych między adresami: zakładka **Moje** → kopia zapasowa →
skopiuj tekst → wklej na drugim urządzeniu i wczytaj. Warto zrobić kopię przed
każdą aktualizacją pliku.

## Działanie offline

Cała treść (opisy, plan, mapa poglądowa, filtry, listy) działa bez internetu.
Internetu wymagają tylko linki wychodzące: Mapy Google, zdjęcia i strony rezerwacji.

## Uwagi

- Mapa jest poglądowa: obrysy wysp są uproszczone, a współrzędne przybliżone.
- Ceny i godziny sprawdzono w internecie 16.09.2026 dla kluczowych miejsc; resztę
  potwierdzaj na miejscu.
- Ta wersja jest przeznaczona do publicznego hostingu: nie zawiera numerów rezerwacji,
  nazw hoteli ani imion.
