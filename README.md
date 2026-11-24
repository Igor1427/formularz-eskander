# Formularz danych do umowy (wersja testowa)

Formularz online, w którym zleceniobiorca lub wykonawca dzieła podaje dane potrzebne do umowy zlecenia albo umowy o dzieło. Obejmuje oświadczenie ZUS, PIT-2 i rezygnację z PPK. Po kliknięciu „Prześlij zgłoszenie” dane są wysyłane e-mailem przez usługę [FormSubmit](https://formsubmit.co).

- `index.html`: cały formularz (HTML, CSS i JS w jednym pliku).
- `dane/dane.json`: województwa, powiaty i gminy (TERYT GUS, stan na 2026-01-01) oraz 400 urzędów skarbowych (kody MF).
- Tryb testowy: dopisz `?test` do adresu. Pojawią się wtedy przyciski z przykładowymi danymi i opcja pominięcia sprawdzania pól.

**Wersja testowa.** Dane przechodzą przez zewnętrzną usługę FormSubmit, dlatego testuj wyłącznie na danych fikcyjnych. Docelowa wersja dla prawdziwych danych będzie działać na własnym serwerze.

Plik `index.html` jest generowany skryptem `build_live.py` z makiety projektu. Nie edytuj go ręcznie.
