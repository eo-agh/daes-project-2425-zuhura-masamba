# 📊 Projekt: Zmiany klimatyczne w miastach – analiza trendów w danych z Copernicus Climate Data Store

## 🎯 Cel

Celem projektu jest analiza długoterminowych trendów wybranych parametrów meteorologicznych (takich jak temperatura powietrza, suma opadów i prędkość wiatru) w polskich miastach wojewódzkich na podstawie danych z ERA5 dostępnych w Copernicus Climate Data Store. Badanie pozwoli na:

- identyfikację zmian klimatycznych w ujęciu lokalnym (miejskim),
- porównanie tempa i charakteru zmian w miastach o różnych warunkach klimatycznych,
- ocenę sezonowości i ekstremalnych wartości,
- przygotowanie prostych prognoz przyszłych wartości na podstawie analizy szeregów czasowych.

---

## 🧪 Metody

Projekt będzie realizowany z użyciem metod analizy danych szeregów czasowych i eksploracyjnej analizy danych (EDA):

### 1. Wstępne przetwarzanie danych
- Wczytanie danych z plików `.nc`
- Ekstrakcja danych dla współrzędnych miast wojewódzkich
- Agregacja dziennych danych do miesięcznych i rocznych

### 2. Eksploracyjna analiza danych (EDA)
- Wykresy trendów (liniowych i nieliniowych)
- Sezonowość i rozkłady roczne
- Wykresy pudełkowe, mapy cieplne, korelacje

### 3. Analiza statystyczna trendu
- Dopasowanie regresji liniowej do danych rocznych
- Testy statystyczne (np. test Manna-Kendalla) do oceny istotności trendu

### 4. Modelowanie prognostyczne
- Model ARIMA do prognozy temperatury/opadów na kilka lat w przód
- Walidacja modelu na danych z ostatnich lat (podział na zbiór treningowy/testowy)
- Ocena niepewności prognoz

---

## 🛠 Techniczna implementacja

Projekt zostanie zrealizowany z wykorzystaniem języka **Python** i następujących bibliotek:

- `xarray`, `netCDF4` – wczytywanie i przetwarzanie danych `.nc`
- `pandas`, `numpy` – manipulacja danymi i agregacja czasowa
- `matplotlib`, `seaborn`, `plotly` – wizualizacja danych
- `statsmodels` – analiza statystyczna i modelowanie ARIMA
- `scikit-learn` – podział danych i walidacja modelu
