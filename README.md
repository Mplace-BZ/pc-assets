# pc-assets

Zdjęcia produktowe nowej kolekcji Perfekt Cięcie, wrzesień 2026.
Repozytorium jest publiczne, bo BaseLinker i Allegro pobierają obrazki po adresie URL.

## Struktura

```
<grupa>/<wybarwienie>/<konto>-<n>.jpg
<grupa>/wymiary.jpg
wspolne/noga.jpg
```

Grupy: `komoda-1plus3`, `komoda-2plus3`, `rtv`, `witryna`, `stolik-vox`,
`stolik-frik`, `mirror-3`, `mirror-4`.

Wybarwienia: `artisan`, `bialy`, `craft`, `kaszmir`, `lancelot`, `sonoma`, `wotan`.

Konta: `mobelkap`, `perfekt`, `naczasie`, `wspolne` (zdjęcia bez brandingu),
`viz` (rendery aranżacyjne).

## Parametry plików

JPEG, dłuższy bok maks. 1600 px, jakość 70. 961 plików, 283 MB.
Źródło: katalog `PC Nowe produkty` w repozytorium `Meble-Allegro`.
Spis w `manifest.json` - każdy plik z nazwą oryginału.

Generowane skryptem `tools/pc-assets-build.py` z repozytorium `Meble-Allegro`.
