### Obejście problemu z google_images_download

1. Instalujemy bibliotekę tqdm wykorzystując PyCharm lub wykonując polecenie w terminalu:
pip install tqdm

2. Klonujemy repozytorium:
git clone https://github.com/ultralytics/google-images-download

3. Przechodzimy do katalogu google-images-download:
cd google-images-download

4. Wykonujemy polecenie:
python bing_scraper.py --search "horse" --limit 10 --download --chromedriver C:\Users\krako\chrome-driver\chromedriver.exe

    Po --search podajemy termin o jaki chcemy zapytać, po --limit limit zdjęć do pobrania oraz po --chrmedriver odpowiednią ścieżkę do chromedriver.exe

5. Pobrane zdjęcia (pobieranie zakończone sukcesem) będą znajdować się w katalogu:
google-images-download\images\horse