# Wrzosowisko — szkółka jeździecka i stadnina koni
Projekt strony internetowej fikcyjnej szkółki jeździeckiej i stadniny koni „Wrzosowisko”.
## Technologie
- HTML5
- CSS3
- JavaScript
- Git
- GitHub

## Wykorzystanie AI
W projekcie wykorzystano narzędzie AI- > ' ChatGPT', do:
- pomocy w planowaniu struktury strony,
- przygotowywania przykładowych tekstów,
- doborze kolorystyki,
- tworzenia i wyjaśniania fragmentów CSS`,
- konsultowania poprawek dostępności i responsywności,
- analizy zgodności projektu z wymaganiami.
Szczegółowe informacje dotyczące wykorzystania AI znajdują się w pliku `AI_LOG.md`.

## Planowane strony

### Publiczne
- Strona główna
- Nasze konie
- Oferta
- O stadninie
- Kontakt

### Użytkownik
- Logowanie
- Profil użytkownika

### Administracja
- Panel administracyjny
- Ogłoszenia
- Użytkownicy
- Statystyki

## Funkcjonalności JavaScript
Planowane funkcjonalności:
- walidacja formularza,
- komunikaty o błędach,
- filtrowanie koni,
- interaktywny element poza formularzem.

## Dostępność i responsywność
W aktualnej wersji projektu uwzględniono:
- semantyczny HTML,
- opisy alternatywne zdjęć,
- widoczny wskaźnik fokusu,
- obsługę klawiaturą,
- odpowiedni kontrast tekstu i tła,
- dostosowanie układu strony do różnych szerokości ekranów,
- wykorzystanie CSS Grid i Flexbox.

### Audyt dostępności — Lighthouse
Wersja strony z dnia` 22.XI.2026 została sprawdzona za pomocą narzędzia Lighthouse
w kategorii Accessibility (Ułatwienia dostępu).
Uzyskany wynik: **100/100 punktów**.
![Wynik audytu dostępności Lighthouse](images/lighthouse-accessibility.png)

### Testy responsywności
Strona została sprawdzona przy szerokościach:
- 320 px,
- 375 px,
- 768 px,
- 1920 px.
Podczas testów poprawiono układ nagłówka, menu, kart koni oraz sekcji kontaktowej na mniejszych ekranach.

## Status projektu

### Obecnie zrobiłam:
- [13.XI.2026] - Utworzyłam podstawową strukturę projektu i plików.
- [16.XI,206] - Utworzyłam podstawowe sekcje strony { : „O nas”, „Nasze konie” , „Oferta” , „Kontakt”}.
- [19.XI.2026] - Podstawowe style CSS,  układ kart dla koni i oferty oraz układ bloków w sekcji kontaktowej.
- [21`.XI.2026] - Stworzyłam nawigację z rozwijanymi elementami.
- [22.XI.2026] - Uporządkowałam i uprościłam* kod CSS.
- [22.XI.2026] - Poprawiłam responsywności strony.
- [23.XI.2026] - Dostosowałam stronę do urządzeń mobilnych i większych ekranów w zakresie 320-1920px}
- [23.XI.2026] - wykonałam audyt(I) dostępności Lighthouse z wynikiem 100/100 punktów.
- [28.XI.2026] Uporządkowałam dokumentację projektu README.md i AI_LOG.md.
- [28.XI.2026] Doprecyzowałam opis wykorzystania narzędzia ChatGPT oraz uporządkowałam historię jego wykorzystania.
- [28.11.2026] Zaplanowałam strukturę pozostałych podstron projektu, w tym strony informacyjnej, logowania, wylogowania i panelu administracyjnego.

### Do wykonania:
- Strona informacyjna,
- Plik PDF ze specyfikacją,
- Strony ogłoszeń i edycji ogłoszeń,
- Strony użytkowników i edycji użytkowników,
- Profil zalogowanego użytkownika,
- Statystyki serwisu,
- Formularz logowania i wylogowania,
- Formularz kontaktowy,
- Walidacja formularza w JavaScript,
- Interaktywny element poza formularzem.