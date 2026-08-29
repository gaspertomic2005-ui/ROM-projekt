# Analiza globalnega segrevanja

Projekt je izdelan v programskem okolju Wolfram Mathematica in prikazuje analizo dolgoročnih sprememb temperature ter padavin z uporabo podatkov funkcije `WeatherData`.

## Namen projekta

Namen projekta je analizirati spremembe vremenskih razmer skozi daljše časovno obdobje. Analiza vključuje več izbranih mest iz različnih delov sveta ter primerja njihove dolgoročne temperaturne trende.

Obravnavana mesta so:
- Ljubljana
- London
- New York
- Tokyo
- Sydney

Za analizo temperature je uporabljeno obdobje 1990–2024. Poleg temperaturne analize projekt vsebuje tudi analizo letne količine padavin za Ljubljano.

## Vsebina projekta

Glavna datoteka projekta je:

- `Analiza_globalnega_segrevanja.nb` – Mathematica beležnica z izvorno kodo, analizami, tabelami, grafi in interpretacijo rezultatov.

Mapa `data` vsebuje:

- `temperature_monthly.wl` – shranjene podatke o mesečnih temperaturah,
- `trend_summary.csv` – povzetek izračunanih temperaturnih trendov,
- `annual_temperature_ljubljana.csv` – letne povprečne temperature za Ljubljano,
- `annual_precipitation_ljubljana.csv` – letne količine padavin za Ljubljano.

## Uporabljene metode

Pri projektu so uporabljene funkcionalnosti jezika Wolfram Language, med drugim:

- `WeatherData` za pridobivanje vremenskih podatkov,
- `Association` in `Dataset` za organizacijo podatkov,
- `Map`, `Apply` in `Query` za obdelavo podatkov,
- `LinearModelFit` za ocenjevanje linearnih temperaturnih trendov,
- grafični prikazi za vizualizacijo rezultatov,
- izvoz rezultatov v datoteke CSV.

## Rezultati

Za vsako izbrano mesto je izračunan linearni temperaturni trend in koeficient R². Rezultati omogočajo primerjavo dolgoročnih sprememb povprečnih letnih temperatur med posameznimi lokacijami.

Podrobneje je prikazan trend za Ljubljano, dodatno pa je analizirana tudi letna količina padavin.

Projekt predstavlja analizo izbranih lokalnih vremenskih podatkov in ne neposrednega izračuna globalne povprečne temperature Zemlje.

## Zagon projekta

Za uporabo projekta je potreben Wolfram Mathematica oziroma okolje, ki podpira Wolfram Language.

1. Prenesite oziroma klonirajte repozitorij.
2. Odprite datoteko `Analiza_globalnega_segrevanja.nb`.
3. Beležnico izvajajte od začetka proti koncu.
4. Za ponovno pridobivanje podatkov prek `WeatherData` je potrebna internetna povezava.

Projekt uporablja relativne poti, zato naj datoteka `Analiza_globalnega_segrevanja.nb` in mapa `data` ostaneta v enaki strukturi kot v repozitoriju.

## Video predstavitev

Video predstavitev projekta je dostopna na YouTubu:

[Ogled video predstavitve](https://youtu.be/9VceUiwrBT8)
