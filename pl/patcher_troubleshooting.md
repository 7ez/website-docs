---
title: "Rozwiązywanie problemów patchera"
---

## Nie mogę włączyć pudłowania/przegrywania na Relaxie podczas korzystania z patchera!
Jeśli nie widzisz dwóch opcji "Akatsuki" na górze menu opcji, oznacza to, że patcher nie został załadowany do gry. Zwykle jest to spowodowane błędnym oznaczeniem plików patchera przez Windows Defender jako złośliwe oprogramowanie. Ponieważ nie możemy tego naprawić, jedynym sposobem rozwiązania tego problemu jest **tymczasowe** wyłączenie Windows Defender:

- Otwórz menu ustawień **Windows Security**, klikając **Menu Start** i wpisując "Windows Security".
- Wybierz **Ochrona przed wirusami i zagrożeniami**.
- W sekcji **Ustawienia ochrony przed wirusami i zagrożeniami** wybierz **Zarządzaj ustawieniami**.
- Wyłącz **Ochronę w czasie rzeczywistym**.
- Ponownie pobierz patchera z [oficjalnej strony](https://akatsuki.gg/patcher).

Należy zauważyć, że ochrona w czasie rzeczywistym zostanie automatycznie ponownie włączona po pewnym czasie, więc aby zapobiec ponownemu wystąpieniu tego problemu, zaleca się dodanie pliku patchera do wykluczeń Windows Defender:

- W tym samym menu **Ustawienia ochrony przed wirusami i zagrożeniami**, przewiń w dół, aż zobaczysz **Wykluczenia**.
- Wybierz **Dodaj lub usuń wykluczenia** (możesz potrzebować przyznać aplikacji uprawnienia administratora).
- Wybierz **Dodaj wykluczenie** > **Plik** i wybierz plik wykonywalny patchera.
- Możesz również potrzebować wykluczyć folder temp, który zawiera pliki potrzebne do działania patchera:
- Wybierz **Dodaj wykluczenie** > **Folder**, a następnie wpisz `%temp%` w pasku adresu na górze.
- Kliknij **Wybierz folder**.

## Nie mogę grać w żadne mapy podczas korzystania z patchera! ("Mapa nie została pomyślnie załadowana")
Aby naprawić ten problem, musisz przenieść katalog osu! za pomocą patchera:

- Otwórz plik wykonywalny patchera.
- Kliknij opcję **Locate** i przejdź do katalogu osu!.
- Kliknij **Wybierz folder**.
- Uruchom osu! za pomocą patchera.

## Nie mogę uruchomić patchera! (Błąd systemu 10061)
Próbujesz uruchomić starszą wersję patchera, która nie jest już wspierana. Pobierz najnowszą wersję patchera ze [oficjalnej strony](https://akatsuki.gg/patcher).

## Wciąż mam problemy!
Jeśli nadal masz problemy po wykonaniu tego przewodnika, otwórz zgłoszenie na naszym [Discordzie](https://akatsuki.gg/discord) i opisz problem. Dołożymy wszelkich starań, aby pomóc!
