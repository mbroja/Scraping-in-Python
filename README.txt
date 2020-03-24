Cel: pobranie nazwy produktu wraz z cen¹ i przechowanie ich w s³owniku

Dane: dane ze strony:
https://mediamarkt.pl/rtv-i-telewizory/telewizory?sort=0&limit=100&page=1

Programy: Python 3 z bibliotek¹ BeautifulSoup w Jupyter

Przebieg "scrapingu":
- pobranie danych ze strony w formie surowej
- u¿ycie BeautifulSoup do ograniczenia kodu html z ponad 20 000 linijek do 450
- u¿ycie prostej funkcji na ³añcuchach znaków
- wrzucenie danych do s³ownika
