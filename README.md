# MAP-labosi
Laboratory exercises for the course Multivariate Data Analysis on FER

# MAP – Multivarijatna analiza podataka

Laboratorijske vježbe iz kolegija Multivarijatna analiza podataka (FER, Zagreb), riješene u Pythonu (Jupyter Notebook).

## Sadržaj

* **`Labosi/1`** – geometrija uzorka, slučajno uzorkovanje, multivarijatna normalna razdioba i statističko zaključivanje. Uzoračka matrica kovarijance i korelacije, statistička (Mahalanobisova) udaljenost, generalizirana varijanca, uzorkovanje iz multivarijatne normalne razdiobe s prikazom elipsi gustoće, Hotellingov T² test te simultani, Bonferronijevi i univarijatni intervali pouzdanosti.
* **`Labosi/2`** – diskriminantna analiza, višedimenzionalno skaliranje i analiza korespondencije na skupu od oko 1500 poznatih klasičnih skladbi (`classical_data`). Linearna diskriminantna analiza (LDA) za klasifikaciju skladatelja po stilskim razdobljima, metričko i nemetričko višedimenzionalno skaliranje stilskih razdoblja te analiza korespondencije (skladatelji i kategorije skladbi, države i stilska razdoblja).

## Tehnologije

Python, NumPy, pandas, SciPy, scikit-learn, Matplotlib, seaborn, prince

## Pokretanje

```bash
pip install numpy pandas scipy scikit-learn matplotlib seaborn prince
```

Zatim otvori željenu bilježnicu u Jupyteru. Bilježnica u mapi `Labosi/2` učitava podatke iz datoteke `classical_data` koja se nalazi u istoj mapi.

## Autor

Karla Budimir
