---
title: "Jak się połączyć"
old_id: 1
---

## Jak się połączyć z Akatsuki: Patcher

- Pobierz Akatsuki Patcher, możesz go znaleźć [tutaj](https://akatsuki.gg/patcher).
- Uruchom Akatsuki Patcher.
- Baw się dobrze grając w osu! na Akatsuki!

## Jak się połączyć z Akatsuki: Skrót na Windowsie

- Znajdź plik `osu!.exe` na swoim komputerze.
- Kliknij prawym na plik `osu!.exe` i wybierz **Utwórz skrót**.
- Kliknij prawym na nowo utworzony skrót i wybierz **Właściwości**.
- W **Właściwościach**, dodaj `-devserver akatsuki.gg` w polu **Elementu docelowego**.
- Kliknij **Zastosuj** aby zapisać zmiany.
- Zamknij okienko **Właściwości**.
- Uruchom grę z skrótu.
- Baw się dobrze grając w osu! na Akatsuki!

Tutorial wideo możesz też znaleźć [tutaj](https://youtu.be/vN8zqgmN_kI)!

## Jak się połączyć z Akatsuki: Linux 

- Otwórz swój skrypt startowy osu!.
- Jeśli `"$@"` nie znajduje się po `osu!.exe`, dodaj to. np. zmień `wine osu\!.exe` na `wine osu\!.exe "$@"`.
- Kiedy odpalasz skrypt, dodaj `-devserver akatsuki.gg`. Na przykład, jeśli normalnie używasz `./osu.sh` aby uruchomić osu!, użyj `./osu.sh -devserver akatsuki.gg`.

Jeśli chcesz tylko grać na Akatsuki, możesz zamienić `"$@"` na `-devserver akatsuki.gg`. Tym sposobem, nie musisz wpisywać adresu serwera za każdym razem jak chcesz grać!

## Jak się połączyć z Akatsuki: MacOS

### Jeśli bezpośrednio uruchamiasz `osu!.exe`: 
- Poszukaj **Opcje EXE** w właściwościach pliku.
- Dodaj `-devserver akatsuki.gg` do pola argumentów.
- Zapisz zmiany i uruchom grę normalnie.
- Baw się dobrze grając w osu! na Akatsuki!

### Jeśli uruchamiasz `osu!.exe` przez plik bat (`execute.bat`):
- Otwórz **plik bat** w edytorze tekstowym.
- Dodaj `-devserver akatsuki.gg` w tej samej linijce co `start C:\osu!\osu!.exe`.
- Zapisz zmiany i uruchom grę normalnie.
- Baw się dobrze grając w osu! na Akatsuki!

## Jak wrócić na Bancho:

- Usuń komendę `-devserver akatsuki.gg` z skrótu którego używasz aby uruchomić osu!.

Jest to rekomendowane żeby posiadać dwa skróty: jeden dla [oficjalnego serwera](https://osu.ppy.sh) i drugi dla Akatsuki. Z powodów bezpieczeństwa, za każdym razem jak zmienisz serwer, będziesz musiał(-a) wpisać dane logowania ponownie.

## Rozwiązywanie problemów:

- Jeśli masz jakiś problem, czuj się swobodnie aby zkontaktować nas na naszym [Discordzie](https://akatsuki.gg/discord)!
