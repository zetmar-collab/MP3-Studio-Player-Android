# MP3-Studio Player na Androida

Odtwarzacz muzyki, radia internetowego i podcastów na Androida 8.0 lub nowszego.

## Pobieranie

Plik APK znajdziesz w sekcji [Releases](https://github.com/zetmar-collab/MP3-Studio-Player-Android/releases/latest).

Telefon poprosi o zgodę na instalację z nieznanego źródła, bo aplikacja nie pochodzi ze sklepu.

Suma SHA-256 wersji 1.3:

```
24909e5d0b6aa2d8a38fe7786ba6f5b742e609856b73e38223d3e9d3de756755
```

## Co potrafi

- Odtwarza muzykę z telefonu, także w tle
- Playlisty: tworzenie, odtwarzanie całej playlisty, import plików M3U, PLS i XSPF oraz eksport do M3U
- Radio internetowe: wyszukiwanie według nazwy, kraju i gatunku, ulubione stacje oraz ich import i eksport
- Podcasty: wyszukiwanie, dodawanie po adresie, kategorie, oznaczanie odsłuchanych odcinków oraz import i eksport listy podcastów (OPML)
- Last.fm: po połączeniu konta wysyła słuchane utwory z telefonu (opcjonalne)
- Korektor dźwięku, jeśli urządzenie go udostępnia
- Motyw jasny, ciemny lub systemowy, język polski i angielski

## Stan wersji 1.3

Nowości w tej wersji to import i eksport ulubionych stacji, przycisk odtwarzania całej playlisty i usuwanie wszystkich playlist naraz. Plik ze stacjami można przenosić między telefonem a programem MP3-Studio Player na Windows. Instalacja na wcześniejszą wersję zachowuje dane.

Nowe funkcje były testowane na emulatorze z Androidem 37. Wysyłanie utworów do Last.fm działa na telefonie, co potwierdzono na wersji 1.2.2.

- Odsłuchane odcinki nie przenoszą się na inne urządzenie.
- Część stacji radiowych odmawia połączenia. Aplikacja pokazuje wtedy komunikat.

## Prywatność

Aplikacja nie ma konta ani reklam. Internetu używa do radia i podcastów: łączy się z usługami wyszukiwania oraz z serwerami wybranych stacji i podcastów, które widzą przy tym adres IP urządzenia. Do Last.fm trafiają wykonawca, tytuł, album i czas słuchania, ale tylko po połączeniu konta i tylko przy włączonym wysyłaniu. Część stacji nadaje przez nieszyfrowane połączenie http.

Kod źródłowy nie jest publikowany w tym repozytorium. Wszelkie prawa zastrzeżone.
