# Prompty do generatorów AI — hero-grafiki Domowe AI

## WAŻNE: proporcje 16:9, ustaw PRZED generowaniem

Docelowy format to szerokie hero pod artykułem (16:9, np. 1600x900), NIE
kwadrat. Proporcje ustawia się w INTERFEJSIE generatora, nie w tekście
promptu — model prawie zawsze ignoruje słowa typu "widescreen" w opisie.

**W NightCafe**: w kreatorze (nie na stronie z opisem narzędzia, tylko po
wejściu w "AI Image Generator" → wybór stylu/modelu) jest pole/suwak
"Aspect ratio" lub "Image size" obok pola z promptem — ustaw 16:9 tam
przed kliknięciem generowania.

**W OpenArt / innych**: szukaj pola "Aspect ratio", "Size" lub presetu
"Landscape" / "16:9" w panelu ustawień obok promptu.

**Jeśli generator akceptuje parametry w tekście** (np. Midjourney): dopisz
`--ar 16:9` na końcu promptu.

## Rdzeń stylu (dokładaj do każdego promptu)

Flat vector travel poster illustration, layered overlapping organic hills/shapes
creating depth (foreground, midground, background), soft glowing circular sun or
moon as central focal point, single small dark silhouette as focus element,
muted desaturated color palette, subtle paper grain texture, minimalist
composition, no photorealism, no text, 1970s Polish travel poster aesthetic,
poster art, illustration.

## Paleta kolorów (dołącz frazę)

Color palette: near-black background (#000000), teal-cyan accent (#54cec8),
warm orange glow (#ea8f21), muted dark tones. Limited palette, 3-4 colors only.

## Negatywny prompt (jeśli narzędzie to wspiera)

photorealistic, 3D render, glossy, neon, cyberpunk, text, watermark, signature,
busy detail, cluttered, gradient mesh, comic book style

---

## ZAAKCEPTOWANY WZORZEC (2026-08-15)

Prompt 1 poniżej wygenerował zaakceptowany wynik w NightCafe, 16:9 —
zapisany w projekcie jako `public/hero/test-osoba-wzgorza-16x9.jpg`.
Kompozycja: mała ciemna sylwetka stojąca na szczycie centralnego wzgórza,
duży miękki świecący pomarańczowy dysk bezpośrednio za/nad sylwetką,
warstwy zachodzących na siebie zielono-czarnych wzgórz tworzące głębię,
drobny akcent w rogu (generator sam dodał mały księżyc — dobry, można
świadomie prosić o podobny drugi mały element). Prompty 2 i 3 poniżej
przepisane, żeby trzymać się TEJ SAMEJ sprawdzonej kompozycji (sylwetka +
centralny dysk + warstwy wzgórz), zmieniając tylko co reprezentuje
sylwetka/dysk pod dany temat — nie eksperymentować ze zupełnie inną
kompozycją bez potrzeby, sprawdzony wzorzec działa.

## Prompt 1 — temat: origin story / start projektu (ZWERYFIKOWANY, użyj bez zmian)

```
Flat vector travel poster illustration, layered overlapping organic hills
creating depth, a small dark silhouette of a person standing on top of a
central hill, a large soft glowing orange circular sun directly behind the
silhouette, a small moon or planet accent in one corner, muted desaturated
teal and dark green color palette for the hills, subtle paper grain
texture, minimalist composition, no photorealism, no text, 1970s Polish
travel poster aesthetic. Color palette: near-black background (#000000),
teal-cyan accent (#54cec8), warm orange glow (#ea8f21). Limited palette,
3-4 colors only.
```

## Prompt 2 — temat: sieć/integracje (węzły połączeń)

```
Flat vector travel poster illustration, layered overlapping organic hills
creating depth, a small dark silhouette of a person standing on top of a
central hill, small glowing geometric nodes connected by thin lines
floating above the silhouette like a constellation, one node larger and
brighter than the rest at the center, muted desaturated teal and dark
green color palette for the hills, subtle paper grain texture, minimalist
composition, no photorealism, no text, 1970s Polish travel poster
aesthetic. Color palette: near-black background (#000000), teal-cyan
accent (#54cec8), warm orange glow (#ea8f21). Limited palette, 3-4 colors
only.
```

## Prompt 3 — temat: dane/prywatność (warstwy/ochrona)

```
Flat vector travel poster illustration, layered overlapping organic hills
creating depth, a small dark silhouette of a person standing on top of a
central hill, a soft glowing circular shield shape surrounding the
silhouette instead of a sun, thin protective concentric rings around the
glow, muted desaturated teal and dark green color palette for the hills,
subtle paper grain texture, minimalist composition, no photorealism, no
text, 1970s Polish travel poster aesthetic. Color palette: near-black
background (#000000), teal-cyan accent (#54cec8), warm orange glow
(#ea8f21). Limited palette, 3-4 colors only.
```

---

## Prompt 0 — HERO STRONY GŁÓWNEJ (marka, nie pojedynczy temat)

WAŻNE: strona nakłada tytuł "Domowe AI" + tagline na DOLNĄ jedną trzecią
tego obrazka (biały/jasny tekst na gradiencie do czerni). Kompozycja MUSI
mieć główny motyw (dom, rodzina, świecący dysk) w GÓRNEJ dwóch trzecich
kadru, z prostszym/ciemniejszym pierwszym planem na dole, żeby tekst był
czytelny — stąd dopisek "empty dark foreground at the bottom third" w
prompcie poniżej.

```
Flat vector travel poster illustration, layered overlapping organic hills
creating depth, a small house silhouette on a central hill with a few
small dark family silhouettes standing together in front of it, a large
soft glowing orange circular sun directly behind the house, a small moon
or planet accent in one corner, the main scene positioned in the upper
two thirds of the frame, empty dark foreground hill with no detail in the
bottom third of the frame, muted desaturated teal and dark green color
palette for the hills, subtle paper grain texture, minimalist composition,
wide panoramic framing, no photorealism, no text, 1970s Polish travel
poster aesthetic. Color palette: near-black background (#000000),
teal-cyan accent (#54cec8), warm orange glow (#ea8f21). Limited palette,
3-4 colors only.
```

## Narzędzia do wypróbowania

- **NightCafe** (creator.nightcafe.studio/tools/retro-poster-design-generator)
  — dobra kontrola nad tekstowym promptem, wiele modeli do wyboru
- **OpenArt** (openart.ai/generator/retro-poster) — darmowy generator,
  dobry punkt startowy
- Jeśli dostępny: Midjourney z parametrem `--style raw` dla mniej
  "wygładzonego" AI-look, bliżej ręcznej ilustracji

## Format docelowy

Proporcje 16:9 (np. 1600x900) pod hero na stronie posta — większość
generatorów pozwala ustawić proporcje w interfejsie lub przez parametr
`--ar 16:9`.
