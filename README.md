<p align="center">
  <img src="assets/wocaclick-logo.png" alt="WocaClick" width="480">
</p>

# WocaClick

Moderní desktop nástroj pro procvičování **WocaBee** na **Fedora**. Běží
v jednom okně s vestavěným prohlížečem (QtWebEngine) – žádný Firefox,
Selenium ani instalace ovladačů.

## Proč WocaClick

Algoritmus WocaClick je navržený tak, aby jeho chování bylo **nero­zpoznatelné
od lidské práce**:

- trusted Qt vstupy (klik, klávesy i dvojklik mají `isTrusted: true`),
- žádný WebDriver/geckodriver, `navigator.webdriver` je `false`,
- normální Chrome user-agent a persistentní profil,
- lidské tempo, náhodné pauzy a přestávky,
- diakritika přes IME,
- po každých 160 správných odpovědích „Uložit a odejít“ → forward → 2 WocaPoints.

## Stav projektu

Aplikace zatím **není veřejně dostupná**. Až bude hotový systém licencí a limitů,
vyjde RPM pro Fedora. Tento repozitář obsahuje pouze informace o projektu a
branding; zdrojový kód aplikace není zveřejněný.

## Funkce

- vestavěný prohlížeč v jednom okně,
- ovládání Start/Stop, limit správných odpovědí, statistiky kliknutí,
- potvrzovací dialog s podmínkami při každém Startu,
- moderní tmavě/oranžový design a loading screen.

## Upozornění

Používání je na vlastní riziko a na vlastní odpovědnost. Nástroj může porušovat
podmínky WocaBee a vést k **zablokování účtu**. Autoři nenesou odpovědnost za
ztrátu účtu, body ani jiné škody. Žádný nástroj nemůže garantovat 100%
neodhalitelnost.

## Made by

[github.com/jerry256254](https://github.com/jerry256254)
