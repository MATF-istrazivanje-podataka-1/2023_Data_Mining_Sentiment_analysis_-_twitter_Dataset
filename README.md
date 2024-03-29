# Twitter Sentiment Analysis 

Projekat napravljen na kursu Istrazivanje podataka 1  
Autor: `Filip Jovanovic 336/2018`  
Profesor: `Prof. Dr. Nenad Mitic`  
Asistent: `Marija Eric`

## Ukratko o projektu

Zadatak projekta je da se na osnovu tweet-a zakljuci da li dati tweet sadrzi govor mrznje ili ne  
Za detaljniju analizu materijali se mogu naci na [Kaggle-u](https://www.kaggle.com/datasets/arkhoshghalb/twitter-sentiment-analysis-hatred-speech)  

## Instalacija

Pre samog pokretanja projekta potrebno je instalirati koriscene biblioteke:
```bash
pip3 install -r requirements.txt
```
Ako se projekat pokrece na Google Colab-u onda u prvoj celiji izvrsiti komandu na sledeci nacin:
```bash
!pip3 install -r requirements.txt
```

## Struktura projekta

- `models`
    - `association_rules` - Pravila pridruzivanja u SPSS-u
    - `classification` - Algoritmi klasifikacija
    - `clustering` - Algoritmi klasterovanja
- `dataset` - Podaci za treniranje i testiranje modela
- `images` - Slike za vizuelni prikaz podataka
- `preprocessing.ipynb` - Pretprocesiranje podataka
- `requirements.txt` - Lista potrebnih biblioteka za rad na projektu
