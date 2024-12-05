---
title: Jak się przygotować na testy łączności awaryjnej?
draft: false
date: 2024-12-05T20:33:00+01:00
---
**Testy łączności awaryjnej** podbijają Polskę, zachęcając coraz większą rzeszę ludzi do prowadzenia łączności. Odbywają się one każdego 13-tego dnia miesiąca oraz w ostatnie soboty miesiąca. Ale jak się do nich przygotować? 🤔

![Zdjęcie z testów](/images/testy.jpeg)

Radiem zajmuję się od ponad dwóch lat. W tym czasie dowiedziałem się wiele na ten temat, ale tak naprawdę moja przygoda zaczęła się po pójściu na pierwsze testy (około rok temu)! Chcę podzielić się z Tobą super przydatną dawką informacji, które chciałbym znać, idąc na testy po raz pierwszy.

## Miejsce, Ekwipunek i Pogoda ☁️

W tym wpisie nie chcę za bardzo rozpisywać się o radiach. Powiem tylko, że każde radio **PMR** i **CB** jest w porządku. 

> **WAŻNA UWAGA!**
> Każde radio, które **legalnie** nadaje na tych pasmach, jest dobre. Dla PMR oznacza to radia o mocy maksymalnie 0,5W i bez wymiennej anteny ;) Wszelkie baofengi, quashengi i tym podobne nie powinny być używane w testach!

Dlaczego nie chcę mówić za dużo o radiach? Bo żeby efektywnie nadawać w testach, najważniejsza jest lokalizacja. Fala na paśmie 446MHz (PMR) to fala przyziemna, więc każda przeszkoda może stanowić problem. Dobre miejsce do testów to takie, które jest relatywnie wysoko i bez przeszkód wokół.

Oczywiście, fajnie jest nadawać z własnego domu, ale zachęcam do wyjścia na świeże powietrze i zdobycia lokalnej górki! 🏞️ 

### Jak Szukać Takich Miejsc?

Zacznij od przeszukania map. Szukaj punktów widokowych, szczytów, kopców. W terenach zurbanizowanych poszukaj otwartych dla wszystkich dachów, np. parkingów wielopiętrowych.

**Podpowiedź** 💡
Sprawdź stronę [HeyWhatsThat](https://www.heywhatsthat.com/). Jeśli masz dużo czasu, spróbuj napisać zapytanie do [Overpass Turbo](https://overpass-turbo.eu/) (pamiętaj, żeby przed wyjazdem sprawdzić te miejsca na Street View). Oto moje zapytanie:
```
[out:json][timeout:25];
// Użycie bbox
(
  node["natural"="peak"](bbox);
  node["tourism"="viewpoint"](bbox);
);

// Pobranie wyników
out body;
>;
out skel qt;
```

![Mapa z overpass turbo](/images/overpassturbo.png)
*Potencjalne miejscówki wygenerowane przez Overpass Turbo*

## Co Ze Sobą Zabrać? 🎒

Gdy już zdecydujemy się wyjść w teren, warto pomyśleć, co zabrać, żeby było nam jak najlepiej. Oto moja lista:
- **Radio** - Bez niego nie zrobisz łączności!
- **Długopis i Logbook** - Logbook to zeszyt, w którym zapisujesz swoje łączności. Nie jest to wymagane, ale fajnie jest sprawdzić, z kim się rozmawiało.
- **Ciepłe ubranie** - Pamiętaj, że spędzisz dużo czasu w jednym miejscu. Nawet latem może zrobić się zimno.
- **Latarka** - To była moja pomyłka na pierwszych testach. Kilka minut po 20:00 zrobiło się tak ciemno, że musiałem wracać wcześniej do domu.
- **Karimata** - Zawsze biorę ze sobą karimatę. Często na miejscu nie znajdziesz ławki.
- **Środek transportu** - Zastanów się, jak dojedziesz na miejsce. Ja zwykle korzystam z roweru lub komunikacji miejskiej, ale Ty możesz mieć samochód.

## Pogoda 🌩️🌞

Pogoda to rzecz, która najczęściej psuje plany na testowe wyjazdy. Pamiętaj, żeby dzień przed sprawdzić prognozę pogody (szczególnie jeśli wybierasz się na wyższą górę) i mieć zapasowe miejsce na wypadek niepogody.

*Podobał Ci się ten wpis? Wyślij go komuś dalej! Jeśli masz pytania, napisz do mnie na **datamikolaj@protonmail.com***
