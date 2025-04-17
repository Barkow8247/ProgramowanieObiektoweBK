Dokumentacja projektu kalkulatora Qt
Wprowadzenie

Projekt "Kalkulator" to prosta aplikacja desktopowa zbudowana w Qt, oferująca podstawowe funkcje kalkulatora oraz konwersję między systemami liczbowymi.
Wymagania systemowe

    Qt 5.12 lub nowszy
    Kompilator C++11 lub nowszy
    50 MB miejsca na dysku
    2 GB RAM

Instalacja

    Otwórz Kalkulator.pro w Qt Creator
    Skonfiguruj projekt
    Zbuduj (Ctrl+B) i uruchom (Ctrl+R)

Struktura projektu

    main.cpp - punkt wejścia
    mainwindow.h/cpp - główne okno
    mainwindow.ui - interfejs
    kalkulator.h/cpp - logika kalkulatora
    Kalkulator.pro - plik projektu

Interfejs użytkownika

    Pole wyświetlacza
    Przyciski cyfr (0-9)
    Przyciski operacji (+, -, *, /, %)
    Przycisk kropki (.)
    Przycisk równości (=)
    Przycisk czyszczenia (C)
    Menu (Plik, Narzędzia, Pomoc)

Funkcjonalność

    Podstawowe operacje arytmetyczne
    Konwersja systemów liczbowych (2-10)
    Czyszczenie obliczeń

Główne klasy
MainWindow

    Obsługa interfejsu i interakcji
    Metody: dodajCyfre(), on_btnEquals_clicked(), on_btnClear_clicked()

Kalkulator

    Logika kalkulatora
    Metody: wykonajOperacje(), konwertujDoSystemu(), konwertujZSystemu()

Instrukcja użytkowania
Podstawowe obliczenia

    Wprowadź pierwszą liczbę
    Wybierz operację
    Wprowadź drugą liczbę
    Kliknij =

Konwersja systemów

    Wybierz "Narzędzia -> Konwersja systemów"
    Wybierz typ konwersji
    Wprowadź dane
    Kliknij OK

Ograniczenia

    Tylko podstawowe operacje
    Konwersja ograniczona do baz 2-10
    Brak obsługi nawiasów i złożonych wyrażeń
    Brak historii obliczeń

Planowane rozszerzenia

    Funkcje trygonometryczne
    Obsługa nawiasów
    Rozszerzona konwersja systemów
    Historia obliczeń
    Tryb naukowy
