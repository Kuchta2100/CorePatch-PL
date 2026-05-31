# CorePatch-PL
Moduł xposed dla Vector (dawniej LSPosed), który wyłącza weryfikację podpisów w systemie Android.

![Wydanie GitHub (najnowsze według daty)](https://img.shields.io/github/v/release/coderstory/CorePatch)
![CRAN/METACRAN](https://img.shields.io/cran/l/devtools)
### Obsługiwane wersje Androida

Ta wersja jest przeznaczona wyłącznie dla systemu **Android 9–16.**
<br>![](https://img.shields.io/badge/INFO-Używaj%20najnowszej%20wersji%20aplikacji%20Vector-blue)

## Funkcje

CorePatch oferuje kilka kluczowych funkcji pozwalających ominąć standardowe kontrole instalacji systemu Android.

**Zezwól na obniżenie wersji**:
<br>Umożliwia zainstalowanie starszej wersji aplikacji, eliminując błąd: 
<br>![](https://img.shields.io/badge/INFO-INSTALL__FAILED__VERSION__DOWNGRADE-green)


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

### Pobieranie

**Najnowsze wydanie**: Możesz pobrać najnowszą stabilną wersję ze strony [GitHub Releases](https://github.com/Kuchta2100/CorePatch-PL/releases).  

**Wersje rozwojowe**: Pobierz najnowsze wersje testowe bezpośrednio z [GitHub Actions](https://github.com/Kuchta2100/CorePatch-PL/actions).  

### Podziękowania

Specjalne podziękowania dla następujących osób za ich wkład w projekt:
- [weishu](https://github.com/tiann): Za udostępnienie kodu źródłowego.
- [LSPosed](https://github.com/LSPosed/LSPosed): Za strukturę przechwytywania ART.
- [yujincheng08](https://github.com/yujincheng08): Za wsparcie techniczne.

### Społeczność i wsparcie

Dołącz do społeczności na [Telegramie](https://t.me/core_patch_chat), aby podyskutować o module i uzyskać pomoc.  
Jeśli uważasz ten projekt za przydatny, rozważ wsparcie programisty poprzez [pomagam.pl](pomagam.pl/ahkhwy).

### Licencja

CorePatch jest wydawany na licencji GPL V2. Więcej szczegółów znajdziesz w pliku `LICENSE`.
