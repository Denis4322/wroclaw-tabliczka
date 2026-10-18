# Rozkład przystankowy — Wrocław

Prosta strona do generowania papierowego układu rozkładu jazdy na podstawie pliku GTFS.

## Uruchomienie
1. Otwórz `index.html` w przeglądarce albo opublikuj repozytorium przez GitHub Pages.
2. Pobierz aktualny plik ZIP z https://open-data.cui.wroclaw.pl/hdb/ft/6/
3. Na stronie wybierz ZIP, a potem linię, kierunek i przystanek.
4. Wybierz typ dnia i kliknij „Drukuj rozkład”.

Dane są przetwarzane lokalnie w przeglądarce. Biblioteka JSZip jest ładowana z CDN, więc do odczytu ZIP wymagane jest połączenie z internetem.

## Ważne
- GTFS zawiera kalendarze usług, ale dni świąteczne i wyjątki zależą od konkretnego pliku.
- Wyświetlanie kalendarza dopasowuje typ dnia do wybranego typu (roboczy/sobota/niedziela); przy testowaniu poza zakresem ważności danych wybierz aktualny plik.
- To projekt edukacyjny, nie oficjalna usługa MPK. Zawsze porównuj godziny z oficjalnym rozkładem: https://www.wroclaw.pl/komunikacja/rozklady-jazdy
