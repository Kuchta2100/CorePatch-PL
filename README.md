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
<br>Umożliwia zainstalowanie starszej wersji aplikacji, eliminując błąd: <br>**"INSTALL_FAILED_VERSION_DOWNGRADE".**

**Wyłącz weryfikację skrótu**:
<br>Umożliwia instalację aplikacji po zmodyfikowaniu pliku APK
<br>(ignoruje błąd nieprawidłowego skrótu)

**Wyłącz porównywanie podpisów**:
<br>Zezwala na ponowną instalację aplikacji z innymi podpisami

**Wyłącz dokładne dopasowanie podpisu**:
<br>Wyłącza dokładne dopasowanie podpisu między pakietami APK, umożliwiając instalacje, w których każdy fragment APK ma inny podpis. <br>**Włączaj tylko w razie potrzeby!**

**Użyj zainstalowanych podpisów**:
<br>Zawsze podczas instalacji będą używane podpisy już zainstalowanych aplikacji.
<br>**Jest to niezwykle niebezpieczne.**
<br>**Włączaj tylko wtedy, gdy jest to absolutnie konieczne!**

<table><tr><td><font color="red">Tutaj wpisz swój tekst</font></td></tr></table>


**Obejście blokady**:
<br>Pomija listę blokowanych instalacji na niektórych urządzeniach, np. Nothing Phone.

**Pomiń weryfikację wspólnego użytkownika**:
<br>Umożliwia instalację aplikacji z podpisem innym niż współdzielony przez nich użytkownik.
<br>("Wyłącz porównywanie podpisów” musi być również włączona)

**Wyłącz agenta weryfikacji pakietów**:
<br>np. Google Play Protect