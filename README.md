# CorePatch-PL
Moduł Xposed Framework, który wyłącza weryfikację podpisów w systemie Android.

![Android CI](https://github.com/coderstory/CorePatch/workflows/Android%20CI/badge.svg)
![Wydanie GitHub (najnowsze według daty)](https://img.shields.io/github/v/release/coderstory/CorePatch)
![CRAN/METACRAN](https://img.shields.io/cran/l/devtools)
### Obsługiwane wersje Androida

Ta wersja jest przeznaczona wyłącznie dla systemu Android 9–16.
Używaj najnowszej wersji aplikacji Vector.

## Funkcje

CorePatch oferuje kilka kluczowych funkcji pozwalających ominąć standardowe kontrole instalacji systemu Android.

**Zezwól na obniżenie wersji**: 
Umożliwia zainstalowanie starszej wersji aplikacji, eliminując błąd `INSTALL_FAILED_VERSION_DOWNGRADE`.

**Wyłącz weryfikację skrótu**:
Umożliwia instalację aplikacji po zmodyfikowaniu pliku APK
(ignoruje błąd nieprawidłowego skrótu)

**Wyłącz porównywanie podpisów**
Zezwala na ponowną instalację aplikacji z innymi podpisami

**Wyłącz dokładne dopasowanie podpisu**
Wyłącza dokładne dopasowanie podpisu między pakietami APK, umożliwiając instalacje, w których każdy fragment APK ma inny podpis. Włączaj tylko w razie potrzeby!

**Użyj zainstalowanych podpisów**
Zawsze podczas instalacji będą używane podpisy już zainstalowanych aplikacji.
Jest to niezwykle niebezpieczne.
Włączaj tylko wtedy, gdy jest to absolutnie konieczne!

**Obejście blokady**
Pomija listę blokowanych instalacji na niektórych urządzeniach, np. Nothing Phone.

**Pomiń weryfikację wspólnego użytkownika**
Umożliwia instalację aplikacji z podpisem innym niż współdzielony przez nich użytkownik.
("Wyłącz porównywanie podpisów” musi być również włączona)

**Wyłącz agenta weryfikacji pakietów**
np. Google Play Protect