QUIZ MĄDRALA – jak wrzucić na GitHub i zainstalować na telefonie
================================================================

PLIKI (wszystkie w jednym folderze, bez podfolderów):
  index.html                – cała aplikacja (otwiera się pod samym adresem strony)
  manifest.webmanifest      – dane do instalacji (nazwa, kolory, ikony)
  sw.js                     – działanie offline
  icon-192.png, icon-512.png, icon-maskable-512.png, apple-touch-icon.png, favicon.png, favicon.ico – ikony
  .nojekyll                 – pusty plik (GitHub Pages ma nie przetwarzać plików)

JAK WRZUCIĆ NA GITHUB (GitHub Pages, za darmo):
  1. Zaloguj się na github.com i kliknij „New repository” (np. nazwa: quiz-madrala, ustaw Public).
  2. Kliknij „uploading an existing file” i przeciągnij WSZYSTKIE pliki z tego folderu
     (razem z .nojekyll; jeśli przeglądarka nie pokazuje plików zaczynających się od kropki, możesz go pominąć).
  3. Kliknij „Commit changes”.
  4. Wejdź w Settings → Pages. W „Branch” wybierz main i folder /(root), kliknij Save.
  5. Po 1–2 minutach aplikacja będzie pod adresem:
       https://TWOJA-NAZWA.github.io/quiz-madrala/

JAK ZAINSTALOWAĆ IKONĘ NA TELEFONIE:
  Android (Chrome):  otwórz adres aplikacji → menu ⋮ → „Zainstaluj aplikację” lub „Dodaj do ekranu głównego”.
  iPhone (Safari):   otwórz adres aplikacji → przycisk Udostępnij → „Do ekranu początkowego”.
  Po instalacji aplikacja działa na pełnym ekranie, a po pierwszym otwarciu także bez internetu.

AKTUALIZACJA APLIKACJI:
  Wgraj nowy plik index.html na GitHub (zastąp stary). Jeśli telefon pokazuje starą wersję,
  zmień w pliku sw.js numer „quiz-madrala-v1” na „quiz-madrala-v2” i też wgraj.

UWAGI:
  - Postęp (gwiazdki, punkty) zapisuje się w telefonie, w przeglądarce, w której grasz.
  - Czcionka Fredoka ładuje się z internetu; bez sieci aplikacja użyje czcionki zastępczej.
