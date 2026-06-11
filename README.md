# System Planowania Tras Kuriera

Aplikacja desktopowa wspomagająca pracę kuriera poprzez planowanie i aktualizację tras dostaw.

## Funkcjonalności

- Dodawanie adresów dostaw,
- Usuwanie adresów dostaw,
- Zapisywanie danych w bazie SQLite,
- Wczytywanie zapisanych adresów po ponownym uruchomieniu aplikacji,
- Wyznaczanie kolejności dostaw z wykorzystaniem algorytmu Nearest Neighbor,
- Wprowadzanie adresu startowego kuriera,
- Dynamiczna aktualizacja trasy po dostarczeniu paczek,
- Generowanie mapy OpenStreetMap z oznaczonymi punktami dostaw,
- Wyświetlanie aktualnego punktu startowego,
- Wyświetlanie liczby pozostałych punktów dostawy,
- Numerowanie punktów trasy,
- Potwierdzenie rozpoczęcia nowej trasy.

## Technologie

- Python
- Tkinter
- SQLite
- Folium
- Geopy
- OpenStreetMap

## Uruchomienie

1. Zainstaluj wymagane biblioteki:

```bash
pip install folium geopy
```

2. Uruchom aplikację:

```bash
python main.py
```

## Autor

Marcel Szafraniec

Projekt wykonany w ramach zajęć akademickich.