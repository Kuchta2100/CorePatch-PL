# CorePatch-PL
Moduł xposed dla Vector (dawniej LSPosed), który wyłącza weryfikację podpisów w systemie Android.

![Wydanie GitHub (najnowsze według daty)](https://img.shields.io/github/v/release/coderstory/CorePatch)
![CRAN/METACRAN](https://img.shields.io/cran/l/devtools)
### Obsługiwane wersje Androida

Ta wersja jest przeznaczona wyłącznie dla systemu Android 9–16.
<br>**Używaj najnowszej wersji aplikacji Vector.**

## Funkcje

CorePatch oferuje kilka kluczowych funkcji pozwalających ominąć standardowe kontrole instalacji systemu Android.

**Zezwól na obniżenie wersji**:
<br>Umożliwia zainstalowanie starszej wersji aplikacji, eliminując błąd: <br>
https://img.shields.io/badge/INFO-INSTALL%20FAILED%20VERSION%20DOWNGRADE-green


**Wyłącz weryfikację skrótu**:
<br>Umożliwia instalację aplikacji po zmodyfikowaniu pliku APK
<br>![](https://img.shields.io/badge/INFO-ignoruje%20błąd%20nieprawidłowego%20skrótu-green)



**Wyłącz porównywanie podpisów**:
<br>Zezwala na ponowną instalację aplikacji z innymi podpisami

**Wyłącz dokładne dopasowanie podpisu**:
<br>Wyłącza dokładne dopasowanie podpisu między pakietami APK, umożliwiając instalacje, w których każdy fragment APK ma inny podpis. 
<br>![](https://img.shields.io/badge/UWAGA!-Włączaj%20tylko%20w%20razie%20potrzeby!-red)



**Użyj zainstalowanych podpisów**:
<br>Zawsze podczas instalacji będą używane podpisy już zainstalowanych aplikacji.
<br>![](https://img.shields.io/badge/UWAGA!-Jest%20to%20niezwykle%20niebezpieczne-red)
<br>![](https://img.shields.io/badge/Włączaj%20tylko%20wtedy,%20gdy%20jest%20to%20absolutnie%20konieczne%21-red)


**Obejście blokady**:
<br>Pomija listę blokowanych instalacji na niektórych urządzeniach, np. Nothing Phone.

**Pomiń weryfikację wspólnego użytkownika**:
<br>Umożliwia instalację aplikacji z podpisem innym niż współdzielony przez nich użytkownik.
<br>![](https://img.shields.io/badge/INFO-Wyłącz%20porównywanie%20podpisów-blue)
<br>![](https://img.shields.io/badge/musi%20być%20również%20włączone-blue)


**Wyłącz agenta weryfikacji pakietów**:
<br>np. Google Play Protect