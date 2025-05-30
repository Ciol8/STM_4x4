# STM_4x4

# 🚗 Autonomiczny Pojazd z STM32

Projekt semestralny z przedmiotu **Systemy Wbudowane i Mikrokontrolery**  
Autor: _[Twoje imię i nazwisko]_  
Numer indeksu: _[Twój numer]_  
Data rozpoczęcia: _[Data]_  
Repozytorium zawiera kod, dokumentację oraz materiały projektowe.

---

## 📌 Opis projektu

Celem projektu jest opracowanie modelu autonomicznego pojazdu sterowanego za pomocą mikrokontrolera STM32. Pojazd porusza się w trybie półautomatycznym lub automatycznym, omija przeszkody i/lub śledzi linię. Komunikacja z użytkownikiem odbywa się przez UART (Bluetooth lub przewodowo).

---

## 🛠️ Zastosowane technologie i narzędzia

- **Mikrokontroler:** STM32 (model np. STM32F103C8T6)
- **IDE:** STM32CubeIDE
- **Programowanie:** C (HAL / LL)
- **Sensory:**
  - HC-SR04 (ultradźwiękowy)
  - Sensory optyczne (IR)
- **Zasilanie:** Akumulator Li-Ion / Powerbank
- **Sterownik silników:** np. L298N
- **Komunikacja:** UART (Bluetooth HC-05 / USB)

---

## ⚙️ Funkcjonalności

- ✅ Napęd sterowany przez PWM z użyciem Timerów
- ✅ Obsługa sensorów ultradźwiękowych (pomiar odległości)
- ✅ Odczyt wartości z sensorów IR (linia / przeszkody) przy użyciu ADC
- ✅ Detekcja kolizji i unikanie przeszkód
- ✅ Sterowanie ruchem przez UART (komendy tekstowe)
- ✅ Zasilanie bateryjne – pełna autonomia
- ✅ Regularne wersjonowanie kodu (min. 1 commit/tydzień)

---

## 📁 Struktura repozytorium


---

## 🔌 Komendy UART

| Komenda | Opis                    |
|--------:|-------------------------|
| `START` | Uruchamia pojazd       |
| `STOP`  | Zatrzymuje pojazd      |
| `LEFT`  | Skręt w lewo           |
| `RIGHT` | Skręt w prawo          |
| `DIST?` | Zwraca odczyt z HC-SR04 |

---

## 🧪 Scenariusze testowe

- [x] Detekcja przeszkody z przodu (sensor HC-SR04)
- [x] Reakcja na białą/czarną linię (IR)
- [x] Komunikacja przez Bluetooth
- [x] Test zasilania bateryjnego
- [x] Sterowanie ruchem w czasie rzeczywistym

---

## 📸 Demo i zdjęcia

- Zdjęcia pojazdu: [`/Media/photos/`](./Media/photos/)
- Nagranie testów: [Demo Video](#) *(link do YouTube lub Dysku Google)*

---

## 📄 Dokumentacja

Pełna dokumentacja projektu znajduje się w folderze [`Docs/`](./Docs/), w tym:
- Raport końcowy (PDF)
- Schematy układów
- Lista komponentów

---

## 📅 Harmonogram pracy

- Tydzień 1–2: Koncepcja i lista komponentów  
- Tydzień 3–5: Budowa pojazdu i montaż elektroniki  
- Tydzień 6–9: Programowanie sensorów i napędu  
- Tydzień 10–12: Komunikacja UART + testy  
- Tydzień 13–14: Finalizacja, dokumentacja, raport  

---

## 🧠 Wnioski

_(Tutaj uzupełnij po zakończeniu projektu)_

---

## 📬 Kontakt

W razie pytań:
- Email: _twoj.email@uczelnia.edu.pl_
- GitHub: [Twoja nazwa użytkownika](https://github.com/TwójProfil)

---

**Licencja:** MIT  
