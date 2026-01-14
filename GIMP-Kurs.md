# 📚 Mini Kurs GIMP - Kompletny Przewodnik

## Spis treści
1. [Wstęp do GIMP](#wstęp-do-gimp)
2. [Czym jest GIMP?](#czym-jest-gimp)
3. [Podstawowe informacje](#podstawowe-informacje)
4. [Kluczowe koncepty](#kluczowe-koncepty)
5. [Maski warstwowe](#maski-warstwowe)
6. [Ścieżka edukacyjna](#ścieżka-edukacyjna)
7. [Zasoby dodatkowe](#zasoby-dodatkowe)

---

## 🎨 Wstęp do GIMP

GIMP (GNU Image Manipulation Program) to jedno z najpotężniejszych narzędzi do przetwarzania grafiki cyfrowej dostępnych za darmo. Niezależnie od tego, czy jesteś początkującym twórcą czy doświadczonym grafikiem, GIMP oferuje profesjonalne możliwości porównywalne z płatną aplikacją Adobe Photoshop.

### Dlaczego GIMP?
- **Całkowicie bezpłatny** – nie ma opłat licencyjnych
- **Open-source** – kod źródłowy jest dostępny publicznie
- **Wieloplatformowy** – działa na Windows, macOS i Linux
- **Szerokie możliwości** – od retuszu zdjęć po tworzenie grafiki
- **Rozszerzalny** – obsługuje wtyczki i skrypty

---

## 📖 Czym jest GIMP?

GIMP to profesjonalny edytor grafiki rastrowej (pikselowej) przeznaczony do:
- Retuszu i obróbki fotografii
- Tworzenia ilustracji cyfrowych
- Projektowania grafiki webowej
- Obróbki zdjęć (poprawianie koloru, wyostrzanie, usuwanie zabrudzań)
- Tworzenia animacji w formacie GIF
- Montażu i kolaży fotograficznych
- Tworzenia efektów graficznych i renderowania

### Porównanie z innymi narzędziami
GIMP jest alternatywą dla:
- **Adobe Photoshop** – najpopularniejszego płatnego edytora
- **Photopea** – edytora online (wymaga internetu)
- **Krita** – narzędzia do malarstwa cyfrowego

---

## 🛠️ Podstawowe Informacje

### Interfejs GIMP

#### Główne panele:
- **Pasek menu** – dostęp do wszystkich funkcji (Plik, Edycja, Obraz, Warstwa, Wybór, Widok, Obraz, Filtry, Kolory)
- **Pasek narzędzi** – narzędzia do zaznaczania, rysowania, zamalowywania
- **Panel warstw** – zarządzanie warstwami projektu
- **Panel kanałów** – obsługa kanałów kolorów (RGB, kanały alfa)
- **Panel historii** – cofanie i ponawianie akcji

### Formaty plików

#### Format natywny:
- **XCF** – format GIMP, zachowuje wszystkie warstwy i informacje edytowalne

#### Obsługiwane formaty eksportu:
- **JPG** – fotografie, obrazy bez przezroczystości
- **PNG** – obrazy z przezroczystością, grafika webowa
- **GIF** – animacje, grafika webowa
- **TIFF** – archiwizacja fotografii wysokiej jakości
- **PSD** – kompatybilność z Adobe Photoshop
- I wiele innych...

### Podstawowe kroki pracy z GIMP:

1. **Otwarcie projektu**: Plik → Otwórz
2. **Tworzenie nowego projektu**: Plik → Nowy
3. **Zabawianie warstwami**: Panel Warstw (prawy bok)
4. **Zaznaczanie obszarów**: Narzędzia zaznaczania (prostokąt, ellipsa, swobodne)
5. **Modyfikacja koloru**: Kolory → zmień barwę, nasycenie, jasność
6. **Eksport wyniku**: Plik → Eksportuj jako...

---

## 🔑 Kluczowe Koncepty

### 1. Warstwy (Layers)

Warstwy to fundamental koncepty w GIMP, podobnie jak karty grafiku nakładane na siebie:

- Każdy projekt może mieć wiele warstw
- Warstwy można pokazywać/ukrywać klikając w ikonkę oka
- Można zmieniać kolejność warstw (przeciąganie)
- Każda warstwa ma swoją nieprzezroczystość (opacity)
- Można zmieniać tryb mieszania kolorów między warstwami

**Operacje z warstwami:**
- Dodawanie nowej warstwy: Warstwa → Nowa warstwa
- Duplikowanie: Prawy przycisk myszy na warstwie → Duplikuj warstwę
- Scalanie: Obraz → Spłaszcz obraz (łączy wszystkie warstwy)
- Usuwanie: Prawy przycisk myszy → Usuń warstwę

### 2. Zaznaczenia (Selections)

Zaznaczenia określają, który obszar obrazu zostanie zmieniony:

- **Prostokątne zaznaczenie** – zaznaczanie obszarów prostokątnych
- **Elliptyczne zaznaczenie** – zaznaczanie okrągłych lub eliptycznych obszarów
- **Zaznaczenie swobodne** – ręczne rysowanie zaznaczenia
- **Zaznaczenie poprzez kolor** – automatyczne zaznaczenie pikseli o podobnym kolorze
- **Zaznaczenie przez krzywiznę** – zaznaczanie złożonych kształtów
- **Zaznacz wszystko**: Wybór → Zaznacz wszystko (Ctrl+A)
- **Odznacz**: Wybór → Odznacz (Ctrl+Shift+A)

### 3. Narzędzia edycyjne

#### Narzędzia rysowania:
- **Pędzel** – freehand rysowanie
- **Ołówek** – rysunek o ostrych krawędziach
- **Gumka** – usuwanie pikseli
- **Kredka** – miękkie pędzle airbrush
- **Stempel klonujący** – kopiowanie fragmentów obrazu
- **Łatka** – inteligentne wypełnianie obszarów

#### Narzędzia zamalowywania:
- **Wiadro farby** – zamalowywanie zamkniętych obszarów
- **Gradient** – tworzenie przejść kolorów
- **Ołówek** – dokładne pixelowanie

### 4. Kanały i Maski

**Kanały RGB:**
- Obraz kolorowy składa się z trzech kanałów: Czerwony, Zielony, Niebieski
- Każdy kanał zawiera informacje o jasności tej barwy

**Kanał Alfa:**
- Określa przezroczystość pikseli
- Wartość 255 = pełna nieprzezroczystość
- Wartość 0 = pełna przezroczystość

---

## 🎭 Maski Warstwowe

Maski warstwowe to jeden z najpotężniejszych narzędzi w GIMP. Pozwalają na selektywne kontrolowanie przezroczystości warstwy bez trwałego usuwania pikseli.

### Co to jest maska warstwowa?

Maska warstwowa to **szary obraz** (skala szarości), gdzie:
- **Biel (255)** = piksele w pełni widoczne
- **Szarość (128)** = piksele częściowo widoczne
- **Czerń (0)** = piksele całkowicie niewidoczne

### Dlaczego maskę są ważne?

1. **Nieinwazyjność** – nie usuwasz faktycznie pikseli z warstwy
2. **Elastyczność** – można edytować maskę bez wpływu na zawartość warstwy
3. **Wygładzone przejścia** – łatwiej tworzyć naturalne przejścia między elementami
4. **Składność** – można mieć wiele wariantów tego samego efektu

### Jak dodać maskę warstwową?

**Krok po kroku:**

1. **Wybierz warstwę** – kliknij na warstwę w panelu Warstwy
2. **Dodaj maskę**: Prawy przycisk myszy na warstwie → Dodaj maskę warstwy (lub Warstwa → Maska → Dodaj maskę warstwy)
3. **Wybierz inicjalizację maski:**
   - **Biała (pełna opacity)** – cała warstwa jest widoczna (początkowy stan)
   - **Czarna (pełna przezroczystość)** – cała warstwa jest ukryta
   - **Wybór rzeczywisty warstwy (Layer's alpha channel)** – maska będzie oparta na przezroczystości warstwy
   - **Transfer warstwy do maski** – użyj jasności pikseli jako maski
4. **Kliknij "Dodaj"**

### Edytowanie maski warstwowej

Po dodaniu maski:
- **Maska jest aktywna** – możesz ją edytować (białe obramowanie wokół miniatury maski)
- **Maluj czernią**, aby ukryć fragmenty (obniżyć przezroczystość)
- **Maluj bielą**, aby pokazać fragmenty (zwiększyć przezroczystość)
- **Używaj szarości** dla przejść (półprzezroczystość)

### Praktyczny przykład: Czyszczenie efektu

```
1. Otwórz dwa obrazy w GIMP
2. Skopiuj jeden do drugiego jako nową warstwę
3. Dodaj maskę biała do górnej warstwy
4. Maluj czernią na masce, gdzie chcesz pokazać dolną warstwę
5. Efekt: płynne przejścia między obrazami bez usuwania oryginalnych pikseli
```

### Przydatne opcje maski:

- **Włączyć/wyłączyć maskę**: Prawy przycisk na masce → Wyłącz maskę (lub Ctrl+Alt+klik)
- **Zastosuj maskę**: Warstwa → Maska → Zastosuj maskę (bezpowrotnie łączy z warstwą)
- **Usuń maskę**: Warstwa → Maska → Usuń maskę
- **Edytuj maskę / zawartość warstwy**: Kliknij na odpowiednią miniaturkę (warstwa lub maska)

### Wskazówki zaawansowane:

- Możesz używać **gradientów** na masce dla gładkich przejść
- **Niewyraźne zaznaczenie (feather)** przed dodaniem maski tworzy miękksze krawędzie
- Kombinuj maski z **trykami mieszania warstw** dla zaawansowanych efektów
- Maski mogą mieć własne warstwy – możesz je modyfikować do woli bez utraty oryginalnych danych

---

## 📚 Ścieżka Edukacyjna

Poniżej znajduje się rekomendowana sekwencja nauki GIMP z linkami do praktycznych ćwiczeń:

### Moduł 1: Podstawy GIMP

Zapoznaj się z interfejsem i podstawowymi narzędziami.

👉 [Podstawy GIMP](https://rrogacz.pl/gimp-podstawy)

### Moduł 2: Praca z Warstwami

Naucz się zarządzać warstwami – fundamentem pracy w GIMP.

👉 [Warstwy w GIMP](https://rrogacz.pl/gimp-warstwy)

### Moduł 3: Tekst w Grafice

Dodawanie i edycja napisów na obrazach.

👉 [Napisy w GIMP](https://rrogacz.pl/gimp-napisy)

### Moduł 4: Retusz Fotografii

Usuwanie wad, wygładzanie skóry i korekcja twarzy.

👉 [Retusz fotografii](https://rrogacz.pl/retusz)

### Moduł 5: Montaż Obrazów

Łączenie wielu warstw w jeden obraz (composite).

👉 [Montaż w GIMP](https://rrogacz.pl/montaz)

### Moduł 6: Kolaż Fotograficzny

Tworzenie kolaży z nieregularnych kształtów i przejść.

👉 [Kolażowanie](https://rrogacz.pl/krajobrazy)

Dodatkowy przykład kolaża:
👉 [Kolaż - Zamki](https://rrogacz.pl/zamki)

### Moduł 7: Renderowanie Grafiki

Tworzenie efektów i wzorów poprzez renderowanie.

👉 [Renderowanie](https://rrogacz.pl/renderowanie)

### Moduł 8: Filtry i Efekty

Stosowanie zaawansowanych filtrów do modyfikacji obrazów.

👉 [Filtry w GIMP](https://rrogacz.pl/gimpfiltry)

### Moduł 9: Grafika 3D

Tworzenie efektów perspektywy i grafiki trójwymiarowej.

👉 [Grafika 3D - Perspektywa](https://rrogacz.pl/obraz3d)

### Moduł 10: Animacje

Tworzenie animowanych GIF-ów przy użyciu warstw.

👉 [Animacje w GIMP](https://rrogacz.pl/animacje)

---

## 🎓 Zasoby Dodatkowe

### Oficjalne źródła:
- **Strona GIMP**: https://www.gimp.org/
- **Dokumentacja**: https://docs.gimp.org/
- **Forum społeczności**: https://www.gimp.org/discuss/

### Rekomendowane kanały YouTube:
- Wyszukaj "GIMP tutorial" w swoim języku
- Przyczynę się do kanałów edukacyjnych z lokalnymi materiałami

### Najczęściej używane skróty klawiszowe:

| Skrót | Funkcja |
|-------|---------|
| Ctrl+Z | Cofnij |
| Ctrl+Y | Powtórz |
| Ctrl+C | Kopiuj |
| Ctrl+V | Wklej |
| Ctrl+A | Zaznacz wszystko |
| Ctrl+Shift+A | Odznacz |
| Ctrl+S | Zapisz (XCF) |
| Ctrl+Shift+E | Eksportuj jako |
| D | Reset kolorów (czarny/biały) |
| X | Zamień kolory |
| Ctrl+T | Transformacja |
| M | Narzędzie zaznaczania prostokątnym |
| E | Narzędzie gumki |
| B | Narzędzie pędzla |

---

## 🚀 Następne Kroki

1. **Zainstaluj GIMP** – pobierz ze strony https://www.gimp.org/
2. **Przejdź moduły** – zacznij od podstaw, idź systematycznie
3. **Ćwicz** – każdy moduł zawiera praktyczne ćwiczenia
4. **Eksperymentuj** – otwarte myślenie prowadzi do najlepszych efektów
5. **Udostępniaj** – dziel się swoimi pracami i uczyj się od innych

---

## 📝 Notatki Autora

Kurs oparty jest na materiałach edukacyjnych serwisu **rrogacz.pl** autorstwa **Ryszarda Rogacza** (1999–2025), zawierającego profesjonalne ćwiczenia dla uczniów technikum informatycznego.

Mini kurs ten stanowi kompilację teoretyczną do praktycznych ćwiczeń dostępnych na oryginalnej stronie.

---

**Happy Creating! 🎨**
