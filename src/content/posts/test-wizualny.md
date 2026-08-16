---
title: "Test wizualny: jak wygląda typografia, obrazki i kod"
description: "Wpis testowy do sprawdzenia stylu strony — nagłówki, obrazki, cytaty, listy, blok kodu. Nie jest to prawdziwy artykuł."
pubDate: 2026-08-15
draft: true

---

To jest akapit wprowadzający. Sprawdzamy jak wygląda zwykły tekst — długość linii, odstępy między wierszami, kontrast na tle. Ten fragment powinien być wystarczająco długi, żeby zobaczyć zawijanie tekstu na kilku liniach i ocenić czy czyta się wygodnie.

## Nagłówek drugiego poziomu

Kolejny akapit pod nagłówkiem H2. Tu sprawdzamy odstęp między nagłówkiem a treścią oraz jak nagłówek wygląda na tle reszty strony.

![Przykładowy obrazek krajobrazu](https://picsum.photos/800/450?random=1)

Obrazek powyżej to placeholder w proporcji 16:9 — sprawdzamy jak strona radzi sobie z szerokością obrazka względem kolumny tekstu, zaokrąglenie rogów (jeśli jest), i odstępy nad/pod.

### Nagłówek trzeciego poziomu

Fragment kodu, żeby zobaczyć czy blok kodu jest czytelny:

```python
def anonimizuj_kolumne(wartosci, typ):
    """Generuje losowe dane tego samego typu i zakresu."""
    if typ == "liczba":
        return [random.randint(min(wartosci), max(wartosci)) for _ in wartosci]
    if typ == "data":
        return [losowa_data_w_zakresie(wartosci) for _ in wartosci]
    return [losowy_tekst() for _ in wartosci]
```

I trochę tekstu z `kodem inline` w środku zdania, żeby zobaczyć jak to się komponuje z resztą.

> To jest cytat blokowy — na przykład fragment czyjejś wypowiedzi albo ważne zdanie, które chcemy wyróżnić z reszty tekstu.

Lista wypunktowana:

- Pierwszy punkt listy
- Drugi punkt, trochę dłuższy, żeby sprawdzić zawijanie tekstu w elemencie listy
- Trzeci punkt

Lista numerowana:

1. Krok pierwszy
2. Krok drugi
3. Krok trzeci

![Drugi obrazek, portretowy](https://picsum.photos/500/700?random=2)

Drugi obrazek jest w proporcji pionowej (portret) — sprawdzamy czy strona sama go ograniczy do szerokości kolumny, czy trzeba to zrobić ręcznie w stylach.

Ostatni akapit na koniec, żeby zobaczyć odstęp między treścią a linkiem powrotnym na dole strony.
