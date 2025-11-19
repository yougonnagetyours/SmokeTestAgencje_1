# Changelog

## 2025-11-19

### Naprawione błędy
-   Naprawiono przepełnienie formularza Tally poprzez usunięcie zbędnego elementu `div` opakowującego i dostosowanie paddingu kontenera.

### Nowe funkcje
-   Dodano favicon (ikona strony) w formacie SVG dla lepszego brandingu.

## 2025-11-18

### Nowe funkcje
- Dodano nowoczesny gradient do sekcji "Hero" dla lepszego efektu wizualnego.

### Ulepszenia
- **Nagłówek:**
    - Przeniesiono zdjęcie profilowe użytkownika ze stopki do nagłówka, umieszczając je jako logo obok imienia i podtytułu.
    - Zoptymalizowano nagłówek pod kątem responsywności mobilnej poprzez dostosowanie paddingu, rozmiaru obrazu oraz rozmiarów czcionek dla nazwy, podtytułu i przycisku CTA.
- **Sekcja "Brzmi znajomo?" (Problem):**
    - Zwiększono wysokość kafelków i nadano im bardziej kwadratowy kształt (zwiększono padding do `p-10`, dodano `min-h-[200px]`).
    - Zastąpiono emoji profesjonalnymi ikonami SVG z Heroicons.
    - Zmniejszono rozmiar ikon SVG z `text-7xl` do `text-5xl`.
    - Ostatnia ikona (powtarzalne zadania) została zmieniona na ikonę "listy zadań" (`ClipboardListIcon`) dla lepszej czytelności.
- **Sekcja "Jak mogę pomóc?" (Rozwiązanie):**
    - Przekształcono trzy punkty w nowoczesne, minimalistyczne kafelki z jasnym tłem, cieniem i efektem hover.
- **Sekcja "Przykładowe usprawnienia":**
    - Zaktualizowano treść i zmieniono prostą listę na bardziej atrakcyjną wizualnie, z niestandardowymi ikonami SVG i opisowym tekstem.
- **Stopka:**
    - Usunięto zdjęcie profilowe użytkownika i przywrócono prosty, wyśrodkowany układ tekstowy.
- **Ogólne:**
    - Przeniesiono skrypt CDN Tailwind CSS na koniec sekcji `<head>`, aby zapewnić prawidłowe ładowanie stylów.

### Naprawione błędy
- Naprawiono błąd składni w zamykającym tagu `<script>` w pliku `index.html`.
- Rozwiązano problem z brakiem stylów na stronie poprzez przeniesienie skryptu CDN Tailwind CSS.
- Poprawiono układ stopki na desktopie, aby była wyśrodkowana.
