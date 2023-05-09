# scraping
# Primer skrejpovanja sajta - IMDB

** Snimak prezentacije : [Scraping](https://mega.nz/file/WbYF2Tba#TNvbfojsUKlgMpzwZNqiBc3MIFb4QQYXGPUXjEUe4YA)

Na snimku se radi o:
+ Korišćenju scrapy biblioteke za rekurzivno skrejpovanje podataka koja ima komandu scrapy startproject _project-name_ 
+ Kada se program kreira u virtualnom okruzenju definišemo glavnu metodu parse koja skrejpuje podatke idući po naredbama u kodu
+ Naredbe dohvataju html elemente pomoću komande response.css(.class child...) kao neka vrsta query selector-a.
+ Pokretanje se vrši komandom crawl name -o(output) ime|izvedenog|fajla.extension(.csv , .json , .xml)
+ Na ovom primeru smoo izveli .csv jer je kompatibilan sa Excelom 
+ U Excelu smo za primer uradili statistiku koliko je filmova snimljeno po godinama, broj filmova po žanrovima.
+ Knime analitika


## Nikola Timotijevic 63/18 RN
