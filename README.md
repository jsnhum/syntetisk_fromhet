# Syntetisk fromhet

Data och analyskod till artikeln *Syntetisk fromhet: Diskursiv operationalisering av ett religiöst begrepp i en stor språkmodell* (Jonas Svensson, Linnéuniversitetet).

[![Öppna i Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jsnhum/syntetisk_fromhet/blob/main/syntetisk_fromhet_analys.ipynb)

## Innehåll

| Fil | Innehåll |
|---|---|
| `merged_file.csv` | Huvudmaterialet: 30 syntetiska narrativ genererade av Claude Sonnet 4.5 den 24 oktober 2025, tio per fromhetsnivå (LÅG, MEDEL, HÖG), med programgenererade demografiska profiler. |
| `K1.csv`–`K6.csv` | Explorativa testkörningar (oktober 2026), tio narrativ vardera, där instruktionen om informantens religiositet varierades. Kolumnen `Prompt` innehåller hela prompten och `Prompt_källa` anger om den är loggad (K3–K6) eller rekonstruerad (K1–K2). |
| `syntetisk_fromhet_analys.ipynb` | Notebook som återskapar samtliga kvantitativa analyser och citatkontroller i artikeln. |

## Körning

Klicka på *Öppna i Colab* ovan och välj *Runtime → Run all*. Notebooken hämtar datafilerna direkt från detta arkiv; ingen uppladdning behövs. Den kan också köras lokalt (Python 3, pandas, NumPy, SciPy) med datafilerna i samma katalog.
