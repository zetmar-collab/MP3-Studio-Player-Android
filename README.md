# MP3-Studio Player na Androida

Odtwarzacz muzyki, radia internetowego i podcastów na Androida 8.0 lub nowszego.

## Pobieranie

Plik APK znajdziesz w sekcji [Releases](https://github.com/zetmar-collab/MP3-Studio-Player-Android/releases/latest).

Telefon poprosi o zgodę na instalację z nieznanego źródła, bo aplikacja nie pochodzi ze sklepu.

Suma SHA-256 wersji 1.2.1:

```
a7d7b0d11ad4a12cf3c6987a74bf9a4b8c8532350d309b12397b3436d9d5b580
```

## Co potrafi

- Odtwarza muzykę z telefonu, także w tle
- Playlisty: tworzenie, import plików M3U, PLS i XSPF oraz eksport do M3U
- Radio internetowe: wyszukiwanie według nazwy, kraju i gatunku oraz ulubione stacje
- Podcasty: wyszukiwanie, dodawanie po adresie, kategorie, oznaczanie odsłuchanych odcinków oraz import i eksport listy podcastów (OPML)
- Last.fm: po połączeniu konta wysyła słuchane utwory z telefonu (opcjonalne)
- Korektor dźwięku, jeśli urządzenie go udostępnia
- Motyw jasny, ciemny lub systemowy, język polski i angielski

## Stan wersji 1.2.1

Ta wersja zamyka lukę z wersji 1.2: inna aplikacja na telefonie mogła dodać utwór do kolejki odtwarzania, także z podanym przez siebie wykonawcą i tytułem, które trafiłyby do Last.fm. Zalecana jest aktualizacja.

Od wersji 1.2 są też Last.fm i kategorie podcastów. Kategorie przenoszą się w plikach OPML jako foldery. Instalacja na wcześniejszą wersję zachowuje dane.

Ta wersja była testowana na emulatorze z Androidem 37. Wysyłanie utworów na prawdziwe konto Last.fm nie zostało jeszcze sprawdzone.

- Odsłuchane odcinki nie przenoszą się na inne urządzenie.
- Część stacji radiowych odmawia połączenia. Aplikacja pokazuje wtedy komunikat.

## Prywatność

Aplikacja nie ma konta ani reklam. Internetu używa do radia i podcastów: łączy się z usługami wyszukiwania oraz z serwerami wybranych stacji i podcastów, które widzą przy tym adres IP urządzenia. Do Last.fm trafiają wykonawca, tytuł, album i czas słuchania, ale tylko po połączeniu konta i tylko przy włączonym wysyłaniu. Część stacji nadaje przez nieszyfrowane połączenie http.

Kod źródłowy nie jest publikowany w tym repozytorium. Wszelkie prawa zastrzeżone.
