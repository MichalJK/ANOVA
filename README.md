Jest to raport Quarto w postaci dokumentu HTML na temat zastosowania analizy wariancji w  analizie danych.  

 

Temat i forma dokumentu są wynikiem moich zainteresowań zastosowaniami Pythona i R w analizie danych i ich współpracą w ramach jednego projektu: sposobem uaktywniania R i Pythona oraz sposobem przekazywania obiektów pomiędzy R i Pythonem. Programowanie przeprowadzono w RStudio. 

 

Dokument jest dostępny pod adresem: https://michaljk.github.io/ 

 

# Temat: Dwuczynnikowa Anova - przykład 

Problemem, który należało przeanalizować jest ewentualny wpływ dwu rodzajów chłodziwa na średnicę elementu produkowanego na pięciu różnych maszynach. Wykonano po 5 pomiarów dla każdej maszyny i dla każdego chłodziwa. 

 

Zastosowano dwuczynnikową analizę wariancji, którą przeprowadzono w R. Anova wykazała, że rodzaj chłodziwa nie wywiera znaczącego statystycznie wpływu na wynik pomiaru, natomiast czynnik maszyny jest statystycznie istotny. 

 

Wskazanie maszyny, której produkcja odbiega od reszty maszyn wymagała przeprowadzenia porównania parami wyników uzyskanych na badanych maszynach. Takie porównanie zostało przeprowadzone z wykorzystaniem narzędzi Pythona, po pobraniu obiektów R z wcześniejszego etapu obliczeń.  

 

Na koniec zautomatyzowano w R przegląd wyników uzyskanych w Pythonie. 

 

 

 

 

 

 

 

 

 

 

 

 
