STM_4x4
🚗 Autonomiczny Pojazd z STM32
Projekt semestralny z przedmiotu Systemy Wbudowane i Mikrokontrolery

Autor: [Twoje imię i nazwisko]
Numer indeksu: [Twój numer]
Data rozpoczęcia: [Data]

Repozytorium zawiera kod, dokumentację oraz materiały projektowe.

📌 Opis projektu
Celem projektu jest opracowanie modelu autonomicznego pojazdu sterowanego za pomocą mikrokontrolera STM32 Nucleo-F303RE.

Pojazd realizuje tryby pracy:

automatyczny — jazda po linii + unikanie przeszkód,

półautomatyczny — zdalne sterowanie z aplikacji przez Bluetooth.

Komunikacja z użytkownikiem odbywa się przez UART (Bluetooth HC-05).
Dodatkowo pojazd posiada funkcję sygnalizacji świetlnej i dźwiękowej oraz jest wyposażony w obudowę z blachy aluminiowej dla ochrony i estetyki.

🛠️ Zastosowane technologie i narzędzia
Mikrokontroler: STM32 Nucleo-F303RE

IDE: STM32CubeIDE

Programowanie: C (HAL)

Sensory:

HC-SR04 (czujnik ultradźwiękowy)

3 x cyfrowe sensory optyczne IR (linia)

Zasilanie: Akumulator Li-Ion (pakiet 2S 7.4V)

Sterownik silników: L298N (mostek H)

Komunikacja: UART (Bluetooth HC-05)

⚙️ Funkcjonalności
✅ Napęd sterowany przez PWM (4 silniki DC)
✅ Obsługa czujnika ultradźwiękowego (pomiar odległości)
✅ Odczyt stanu sensorów IR (jazda po linii)
✅ Detekcja przeszkody i automatyczne zatrzymanie
✅ Sterowanie ruchem przez Bluetooth (komendy tekstowe i przyciski w aplikacji mobilnej)
✅ Sygnalizacja świetlna (LED) oraz dźwiękowa (buzzer)
✅ Zasilanie bateryjne – pełna autonomia
✅ Regularne wersjonowanie kodu

📁 Struktura repozytorium
bash
Kopiuj
Edytuj
STM_4x4/
├── Docs/                   # Dokumentacja (raport PDF, schematy)
├── Media/photos/           # Zdjęcia pojazdu
├── Media/video/            # Nagranie testów (mp4)
├── Src/                    # Źródła oprogramowania (STM32CubeIDE)
├── Inc/                    # Pliki nagłówkowe
└── README.md               # Niniejszy plik
🔌 Komendy UART
Komenda	Opis
START	Uruchamia tryb jazdy
STOP	Zatrzymuje pojazd
LEFT	Skręt w lewo
RIGHT	Skręt w prawo
DIST?	Zwraca odczyt z HC-SR04
MODE	Zmiana trybu (auto/manual)

🧪 Scenariusze testowe
Detekcja przeszkody z przodu (czujnik HC-SR04)

Jazda po czarnej linii na białym tle (IR)

Komunikacja Bluetooth (manualne sterowanie + zmiana trybu)

Test zasilania bateryjnego (autonomia)

Sygnalizacja świetlna i dźwiękowa

Test sterowania 4 silnikami (PWM + kierunek)

📸 Demo i zdjęcia
Zdjęcia pojazdu: /Media/photos/

Nagranie testów: /Media/video/demo.mp4 (lub link do YouTube / Dysk Google)

📄 Dokumentacja
Pełna dokumentacja projektu znajduje się w folderze Docs/, w tym:

Raport końcowy (PDF)

Schematy układów

Lista komponentów

📅 Harmonogram pracy
Tydzień 1–2: Koncepcja i wybór komponentów

Tydzień 3–5: Budowa pojazdu (sklejka + montaż elektroniki)

Tydzień 6–9: Programowanie sensorów, jazdy po linii, unikanie przeszkód

Tydzień 10–12: Bluetooth + manualne sterowanie

Tydzień 13–14: Finalizacja (obudowa z blachy, testy, dokumentacja)

🧠 Wnioski
Projekt zakończony sukcesem:

Pojazd działa zgodnie z założeniami — jazda po linii, unikanie przeszkód, sterowanie przez Bluetooth, sygnalizacja.

Obudowa z blachy poprawia wygląd i chroni elektronikę.

Całość funkcjonalności jest ukończona — planowane są jedynie ewentualne zmiany wizualne.

📬 Kontakt
Email: twoj.email@uczelnia.edu.pl
GitHub: Twoja nazwa użytkownika

Licencja: MIT
