# Repozytorium projektu ROZPOZNAWANIE GENEROWANYCH KOMPUTEROWO OPINII ZA POMOCĄ MODELU NLP OPARTEGO NA BERT
## Instrukcja uruchomienia modelu
1. Należy otworzyć https://colab.research.google.com/drive/1T2WCxjBFZTlZ7sq5u7zronhavg0FuKL6?usp=drive_link
2. Zmienić *runtime type* aby wykorzystywał **T4 GPU**
3. Dodać do plików runtime plik o nazwie **fake reviews dataset.csv**, dostępny na [stronie Kaggle datasetu](https://www.kaggle.com/datasets/mexwell/fake-reviews-dataset/data)
4. Uruchomić pierwszą komórkę zawierającą przygotowanie środowiska, podział zbioru oraz budowę modelu
W tym momencie struktura modelu użyta w pracy oraz zbiór są załadowane do sesji Google Colab. Model jest gotowy do trenowania, które można wywołać uruchamiając komórki zawierające ```history = final_model.fit()```
Aby przetestować wytrenowany model należy najpierw uruchomić pierwszą komórkę pod nagłówkiem **Testowanie wygenerowanych opinii**, a następnie poniższe komórki zawierające opinie użyte do testów
