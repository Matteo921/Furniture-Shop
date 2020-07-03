<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <title>Furnitures shop</title>
    <link rel="stylesheet" href="./sass/style.scss" />
  </head>

  <body>
    <include src="10_header.html"></include>

    <include src="20_home.html"></include>

    <include src="30_section-features.html"></include>
    <include src="40_section-markup.html"></include>
    <include src="50_section-products.html"></include>

    <include src="70_section-blog-posts.html"></include>
    <include src="80_section-feedback.html"></include>
    <include src="90_footer.html"></include>

    <script src="./scripts/bootstrap.min.js"></script>
    <script src="./scripts/app.js"></script>

  </body>
</html>
# WDP Projekt Zespołowy
## Użyto
HTML CSS/SASS NPM AdobeXd  Jira Kanban 
## Opis projektu

Po sklonowaniu projektu, zainstaluj wymagane paczki komendą `npm install`.

Teraz możesz zacząć pracę, korzystając z przygotowanych zadania `npm run watch`.

Wszystkie potrzebne do pracy pliki źródłowe znajdują się w folderze `src/`.

## NPM Scripts

Dostępne są 3 główne skrypty przyspieszające pracę:

- `build`: na bazie plików z folderu `src` buduje project w folderze `dist`
- `watch`: odpala `browser-sync`, obserwuje zmiany w folderze `src` i przebudowuje projekt
- `code-quality`: skrypt dokonuje automatycznego formatowania plików w folderze `src/`
  zgodnie z przyjętą konwencją formatowania kodu i sprawdza błędy w JS.

## Git Hooks

Projekt korzysta z Git Hooks - możliwości uruchamiania skryptów w reakcji na wybrane zdarzenia programu Git.

Za każdym razem gdy wykonasz komendę `git commit` zostanie uruchomiony skrypt `code-quality`
dla plików, które zostały wybrane do za-commit'owania.

#Konwencje i dobre praktyki
