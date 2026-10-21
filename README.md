# CarGuy

Prototyp aplikacji dla car guyów: garaż, wydatki i koszty posiadania auta, spoty, wyszukiwanie firm w okolicy (przez Google Maps / Apple Maps), wydarzenia, zapisane miejsca i panel admina.

Działa w całości w przeglądarce (jeden plik `index.html`, bez serwera i bez kluczy API).

## Ważne
- Dane zapisują się tylko w przeglądarce danej osoby (localStorage) i nie synchronizują się między urządzeniami.
- Logowanie jest sprawdzane po stronie przeglądarki (w kodzie są tylko skróty SHA-256 haseł demo). To nie jest prawdziwe zabezpieczenie. Nie wpisuj tu prawdziwych haseł ani wrażliwych danych.
- Opcjonalnie: wrzuć własne zdjęcie do `img/hero.jpg`, a pojawi się na stronie głównej.
- Dane oznaczone `[PRZYKŁAD]` są fikcyjne.
- Konta założone w aplikacji istnieją tylko w przeglądarce, w której powstały (hasła są solone i haszowane PBKDF2). Nie działają na innych urządzeniach, a hasła nie da się odzyskać.
- Zdjęcia na stronie głównej są w folderze `img/` (hero.jpg, mod.jpg, spoty.jpg, warsztaty.jpg, trasy.jpg). Upewnij się, że masz prawo je publikować.
