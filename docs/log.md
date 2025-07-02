# 🗓️ Dziennik projektu

## 21.03.2025

**Postęp:**  
- Zapoznanie się z ogólnymi założeniami projektu semestralnego  
- Przegląd tematów i wybór: *Zmiany klimatyczne w miastach*

**Problemy / kwestie do przedyskutowania:**  
- Doprecyzowanie zakresu analizy i liczby miast  
- Wybór podejścia: notatniki vs struktura jako pakiet

---

## 28.03.2025

**Postęp:**  
- Przegląd potencjalnych źródeł danych (m.in. ERA5, dane udostępnione przez prowadzącego)  
- Wstępna koncepcja: analiza temperatury i opadów w wybranych miastach  
- Zapoznanie się ze strukturą gotowego repozytorium GitHub Classroom

**Problemy / kwestie do przedyskutowania:**  
- Format danych wejściowych i organizacja katalogów projektu  
- Sposób przygotowania dokumentacji (MkDocs)

---

## 04.04.2025

**Postęp:**  
- Wczytanie danych z pliku `climate_data.pkl`  
- Struktura danych: słownik miast oraz informacje o stacjach  
- Wstępna eksploracja danych (długości szeregów, obecność braków)

**Problemy / kwestie do przedyskutowania:**  
- Jak ujednolicić długości danych w miastach o dużych brakach  
- Czy analizować wszystkie miasta, czy tylko z pełnymi danymi

---

## 11.04.2025

**Postęp:**  
- Weryfikacja jakości danych: wyszukiwanie wartości odstających i braków (`9999.9`)  
- Identyfikacja przerw w danych (braki ciągłości)  
- Wstępne agregacje miesięczne i roczne

**Problemy / kwestie do przedyskutowania:**  
- Jak obchodzić się z brakami w agregacji (pomijać miesiące z brakami?)  
- Standaryzacja nazw i struktur dataframe’ów dla miast

---

## 25.04.2025

**Postęp:**  
- Czyszczenie danych i tworzenie funkcji do przetwarzania czasowego  
- Łączenie danych z metainformacjami o lokalizacji  
- Weryfikacja zmienności i sezonowości danych

**Problemy / kwestie do przedyskutowania:**  
- Czy wycinać miesiące z największymi brakami  
- Format plików pośrednich (pkl, feather, parquet?)

---

## 30.04.2025

**Postęp:**  
- Finalizacja przygotowania danych do analizy  
- Eksploracyjna analiza danych: wykresy pudełkowe, średnie roczne, sezonowość  
- Uporządkowanie struktury folderów i notatników

**Problemy / kwestie do przedyskutowania:**  
- Czy przekształcać dane do długiego formatu  
- Jak najlepiej prezentować dane wielowymiarowe (miasta × zmienne × czas)

---

## 09.05.2025

**Postęp:**  
- Wstępna analiza trendu: regresje liniowe dla temperatury i opadów  
- Testowanie dekompozycji sezonowej (STL)  
- Przygotowanie wykresów trendów

**Problemy / kwestie do przedyskutowania:**  
- Wybór skali czasowej dla analizy trendu (roczna vs sezonowa)  
- Weryfikacja założeń regresji

---

## 16.05.2025

**Postęp:**  
- Zastosowanie testów statystycznych: Shapiro, Levene, t-test, Mann–Whitney  
- Porównanie rozkładów między miastami  
- Identyfikacja miast z istotnymi różnicami i anomaliami

**Problemy / kwestie do przedyskutowania:**  
- Jak wizualizować wyniki testów porównawczych  
- Jak dobrać odpowiednie testy dla konkretnych pytań badawczych

---

## 23.05.2025

**Postęp:**  
- Doprecyzowanie wniosków z testów statystycznych  
- Konsolidacja wyników do wspólnych tabel i wykresów  
- Przygotowanie materiału do publikacji przez MkDocs

**Problemy / kwestie do przedyskutowania:**  
- Jak zintegrować wyniki w dokumentacji projektu  
- Sposób opisu i interpretacji statystyk

---

## 30.05.2025

**Postęp:**  
- Wizualizacja trendów i porównań między miastami  
- Tworzenie map cieplnych i wykresów z opisami  
- Ostateczne poprawki w kodzie analizy

**Problemy / kwestie do przedyskutowania:**  
- Czy dodać dodatkowe miary (np. zmienność międzylat)  
- Jak wyróżnić ciekawe przypadki miast

---

## 06.06.2025

**Postęp:**  
- Finalizacja wizualizacji  
- Tworzenie spójnego zestawu wykresów do prezentacji  
- Integracja wykresów w dokumentacji

**Problemy / kwestie do przedyskutowania:**  
- Jakie wizualizacje powinny trafić do strony głównej  
- Jak zorganizować treść w MkDocs

---