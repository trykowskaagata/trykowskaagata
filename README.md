# 👋  
Jestem Agata i jestem studentką 3. roku kierunku **Analiza Danych**.  
---

## 📫 Kontakt
- LinkedIn: [www.linkedin.com/in/trykowskaagata/]
- E-mail: [trykowskaagata@gmail.com]  
---

## 🎯 Co robię  
- Studiuję Analizę Danych i z pasją podchodzę do wszystkiego, co związane z danymi, wizualizacją i insightami.  
- W swoich projektach łączę techniczne podejście (np. Power BI, SQL, Python) z osobistymi tematami — np. analizuję swoje dane ze Spotify, by sprawdzić, jak zmieniają się moje nawyki muzyczne. 
---

## 🛠 Technologie i narzędzia  

- **Języki programowania:** Python, R, SQL  
- **Analiza i wizualizacja danych:** Power BI, Excel, Power Query  
- **Umiejętności:** przygotowanie i czyszczenie danych, analiza eksploracyjna (EDA), raportowanie, tworzenie dashboardów  
- **Obszary zainteresowań:** analiza danych muzycznych (np. Spotify), personalne dashboardy, wizualne przedstawianie informacji  
- **Aktualnie rozwijam się w:**  
  - Python: **Pandas**, **NumPy**, **Scikit-learn**  
  - **NLP (Natural Language Processing)**  
  - **NoSQL** i modelowanie danych nienumerycznych  
  - Pogłębianie znajomości **R** (analiza danych, wizualizacja, automatyzacja)
---

## 📌 Wyróżniające projekty 
### 1.⚡ Real-time Spotify Data Pipeline & Dashboard
Projekt automatyzujący proces gromadzenia i analizy osobistych danych muzycznych, budujący niezależne od Spotify archiwum historyczne.
- **Automatyczny Pipeline ETL**: Zaprojektowanie systemu w Node.js/Python, który co 5 minut pobiera dane z API Spotify, eliminując konieczność ręcznego eksportu plików i zapewniając ciągłość danych.
- **Architektura Bazy Danych**: Implementacja relacyjnej bazy PostgreSQL z wykorzystaniem typu JSONB. System wykonuje automatyczną deduplikację rekordów na podstawie znacznika czasu played_at.
- **Transformacja**: Surowy format JSON jest mapowany na strukturę relacyjną z deduplikacją rekordów.
- **Load**: Dane trafiają do bazy PostgreSQL, tworząc unikalne archiwum (niezależne od limitów Spotify).
Dashboard wyświetla topowe utwory, gatunki oraz dynamiczną ikonę aktualnie najczęściej słuchanego artysty.

### 2. 🎧 **Spotify Data Analysis**
Projekt wykonany z ciekawości — chciałam sprawdzić, jak moje własne dane różnią się od corocznego podsumowania Spotify Wrapped oraz rozszerzyć tę analizę.
Dane pobrałam ze Spotify (Spotify Extended Streaming History) (.json → .csv).
Dane zostały oczyszczone i przygotowane w Power Query, a dashboard wykonany w Power BI z wykorzystaniem slicerów (fragmentatorów) dla interaktywności
**Analiza obejmuje:**
- podstawowe statystyki odtworzeń,
- porównanie rok do roku (YoY),
- analizę moich nawyków słuchania.


### 3. 🎶**Spotify–YouTube Analysis**
Projekt poświęcony analizie danych muzycznych z Spotify i YouTube, obejmujący eksplorację danych, redukcję wymiarów i klasteryzację bez nadzoru
Dane zawierają cechy utworów (popularność, energia, tempo, głośność i inne parametry dźwiękowe)
**W projekcie przeprowadziłam:**
- analizę statystyczną i korelacji,
- redukcję wymiarów metodą PCA,
- klasteryzację metodami k-średnich i hierarchiczną,
- ocenę jakości klasteryzacji i istotności cech (Random Forest)
Projekt zrealizowany w języku R z wykorzystaniem pakietów: tidyverse, ggplot2, corrplot, cluster, randomForest, factoextra, plotly.

### 4. 💳**Superstore Power BI Analysis**
- ***Projekt zespołowy*** poświęcony analizie danych sprzedaży detalicznej w celu zrozumienia struktury sprzedaży i identyfikacji kluczowych trendów,
- odpowiadałam za przygotowanie i czyszczenie danych, eksplorację, budowę modelu analitycznego oraz końcowy etap wizualizacji,
- dane zostały przekształcone w Power Query do struktury modelu gwiazdy (Star Schema) i zaimportowane do Power BI,
- stworzyłam interaktywny dashboard z wykorzystaniem slicerów, KPI, wykresów i tabel, wspierający decyzje biznesowe.

### 5. 🌱**Regresja Yacon**
Projekt regresji liniowej wykonany w języku R na danych rośliny yacon (z pakietu agricolae).
Celem analizy było zbadanie zależności poziomu glukozy od wybranych cech fizykochemicznych (m.in. fructose, sucrose, brix, roots).
**Zakres prac obejmował:**
- budowę i diagnostykę modelu regresji liniowej,
- analizę współzależności zmiennych i kolinearności,
- selekcję zmiennych metodą stepwise selection,
- walidację modelu z podziałem danych na zbiór uczący i testowy.
Projekt zrealizowany w R z wykorzystaniem narzędzi do modelowania statystycznego, wizualizacji i oceny jakości modeli
---
