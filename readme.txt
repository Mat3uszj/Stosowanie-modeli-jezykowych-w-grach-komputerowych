Niniejszy projekt dotyczy implementacji systemu interakcji gracza z postaciami niezależnymi (NPC) w grze, 
z wykorzystaniem modeli językowych opartych na AI. 

Główne komponenty projektu:

1.Projekt Unity - Projekt Unity zawiera implementację mechanik gry oraz systemu interakcji z NPC, który 
został zintegrowany z modelem językowym obsługującym polecenia gracza.
2.Serwer Flask i Model językowy - Backend odpowiedzialny za obsługę zapytań do gry oraz przetwarzanie ich 
za pomocą douczonego modelu językowego, potrzebne do integracji lokalnej.

Ze względu na rozmiar plików, wszystkie materiały zostały udostępnione na GitHub i podzielone na dwa główne foldery:

1.Pliki_Unity
Link do folderu: https://github.com/Mat3uszj/Stosowanie-modeli-jezykowych-w-grach-komputerowych.git
Zawiera pliki projektu Unity, w tym skrypty, zasoby oraz sceny gry.

2.Lokalna_integracja
Ze względu na zbyt duży plik douczonego modelu, nie można było go dodać do repozytorium więc został on dodany do dysku google.
Link: https://drive.google.com/drive/folders/1MSEdZGFOE9hjSm9uoI50iicV4Dsf34H9?usp=sharing
Zawiera:
-Plik serwer_flask.py - Skrypt odpowiedzialny za uruchomienie backendu obsługującego zapytania z gry.
-Folder Douczony_model - Pliki modelu przystosowane do specyfiki interakcji w grze.

Wymagania systemowe:

Unity Projekt:
-Unity wersja 2021.3 lub nowsza;
-System operacyjny: Windows, macOS lub Linux;
-Minimum 8 GB RAM.

Serwer Flask:
-Python 3.9 lub nowszy.
-Zainstalowane biblioteki: flask, transformers, torch.

Szczegółowa instrukcja uruchomienia opisana została w dodatku B pracy dyplomowej.
