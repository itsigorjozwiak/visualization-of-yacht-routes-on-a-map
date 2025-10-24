# Wizualizacja Tras Jachtu na mapie 🛥️

Projekt analizuje i wizualizuje trasę rejsu jachtem na podstawie danych z pliku `.gpx`. Aplikacja pobiera historyczne dane pogodowe dla każdego punktu na trasie, a następnie przedstawia je na interaktywnej mapie oraz czytelnych wykresach.

## Jak uruchomić projekt?

Najprostszym sposobem na przetestowanie projektu jest skorzystanie z przygotowanego środowiska w Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/17kww6pJVn8pJdgMmSd2zSWXyIrORuo_w?usp=sharing)

**1. Otwórz projekt w Google Colab**  
Kliknij powyższy przycisk, aby otworzyć notatnik w nowej karcie.

**2. Uruchom pierwsze komórki**  
Uruchom dwie pierwsze komórki kodu, aby zainstalować wszystkie wymagane biblioteki i załadować funkcje.

**3. Wgraj własny plik trasy (`.gpx`)**  
* Uruchom trzecią komórkę kodu, która zaczyna się od `from google.colab import files`.
* Pojawi się przycisk **"Choose Files"** – kliknij go.
* Wybierz z dysku swojego komputera plik z danymi w formacie `.gpx`.

**4. Uruchom resztę kodu**  
Wykonaj po kolei wszystkie pozostałe komórki, aby przetworzyć dane i wygenerować wizualizacje. Poczekaj, aż przy każdej z nich pojawi się informacja o powodzeniu operacji.

## Co zobaczysz na końcu?

### Wykresy analityczne
Projekt wygeneruje trzy wykresy, które pokazują, jak zmieniały się warunki pogodowe w trakcie rejsu:
* Prędkość wiatru
* Temperatura
* Ciśnienie atmosferyczne

### Interaktywna mapa trasy
Ostatnia komórka kodu wyświetli interaktywną mapę, na której:
* **Kolory punktów** oznaczają siłę wiatru:
    * 🟢 **Zielony:** Dobre warunki (słaby wiatr)
    * 🟡 **Żółty:** Umiarkowane warunki
    * 🔴 **Czerwony:** Trudne warunki (silny wiatr)
* **Strzałki** (widoczne po przybliżeniu) pokazują kierunek wiatru.
* **Klikalne punkty** otwierają okienko ze szczegółowymi danymi pogodowymi dla danej lokalizacji.

---

### Autorzy

* Jakub Pawlusek
* Igor Jóźwiak
* Adriana Jarosz
* Agnieszka Jagosz
