# 📊 Projekt: Zmiany klimatyczne w miastach – analiza danych meteorologicznych

## 🎯 Cel

Celem projektu jest analiza długoterminowych zmian parametrów klimatycznych (temperatura, występowanie opadów, występowanie ekstremalnych zjawisk pogodowych) w wybranych miastach europejskich. Analiza oparta jest na danych meteorologicznych z wieloletnich serii czasowych, a celem jest:

- identyfikacja lokalnych trendów klimatycznych,
- porównanie zmian pomiędzy różnymi miastami,
- detekcja istotnych statystycznie trendów,
- ocena sezonowości i zmienności parametrów klimatycznych.

## 🧪 Metody

Projekt opiera się na eksploracyjnej analizie danych (EDA), analizie statystycznej oraz modelowaniu szeregu czasowego.

### 1. Wczytanie i przygotowanie danych
- Dane przechowywane są w plikach `.pkl` oraz `.csv`
- Struktura danych to słownik z nazwami miast jako kluczami i odpowiadającymi szeregami czasowymi
- Dodatkowe metadane zawierają m.in. współrzędne stacji

### 2. Eksploracyjna analiza danych (EDA)
- Analiza braków danych i jakości pomiarów
- Agregacja miesięczna i roczna danych
- Wizualizacja trendów i rozkładów

### 3. Analiza trendu i zmienności
- Dopasowanie modeli trendu (LOWESS)
- Dekonstrukcja sezonowości metodą STL
- Obliczanie i wizualizacja zmienności rocznej i sezonowej

### 4. Testy statystyczne
- Testy normalności (Shapiro-Wilka)
- Porównanie rozkładów między miastami i okresami (testy t-Studenta, Manna–Whitneya, Levene’a)

## 🛠 Techniczna implementacja

Projekt został zrealizowany w języku **Python 3.12**, z wykorzystaniem notatników **Jupyter**. Wykorzystane biblioteki:

- `pandas`, `numpy` – przetwarzanie danych
- `matplotlib`, `seaborn` – wizualizacja
- `statsmodels` – dekompozycja szeregu czasowego i analiza trendów
- `scipy.stats` – testy statystyczne
- `pickle`, `os`, `re` – obsługa danych i automatyzacja operacji

---

Szczegółowy kod i wyniki analiz znajdują się w notatnikach w sekcji **Kod**.