Jest to raport Quarto w postaci dokumentu HTML na temat zastosowania analizy wariancji w  analizie danych. 

Temat i forma dokumentu są wynikiem moich zainteresowań zastosowaniami Pythona i R w analizie danych i ich współpracą w ramach jednego projektu: sposobem uaktywniania R i Pythona oraz sposobem przekazywania obiektów pomiędzy R i Pythonem. Programowanie przeprowadzono w RStudio.

Dokument jest dostępny pod adresem: https://michaljk.github.io/

# Temat: Dwuczynnikowa Anova - przykład
Problemem, który należało przeanalizować jest ewentualny wpływ dwu rodzajów chłodziwa na średnicę elementu produkowanego na pięciu różnych maszynach. Wykonano po 5 pomiarów dla każdej maszyny i dla każdego chłodziwa.

Zastosowano dwuczynnikową analizę wariancji, którą przeprowadzono w R. Anova wykazała, że rodzaj chłodziwa nie wywiera znaczącego statystycznie wpływu na wynik pomiaru, natomiast czynnik maszyny jest statystycznie istotny.

Wskazanie maszyny, której produkcja odbiega od reszty maszyn wymagała przeprowadzenia porównania parami wyników uzyskanych na badanych maszynach. Takie porównanie zostało przeprowadzone z wykorzystaniem narzędzi Pythona, po pobraniu obiektów R z wcześniejszego etapu obliczeń. 

Na koniec zautomatyzowano w R przegląd wyników uzyskanych w Pythonie.


&nbsp;

--------------------------------------------------------------------------------------------------------------------------------------



&nbsp;




This is a Quarto report in the form of an HTML document about the application of variance analysis in data analysis.

The topic and the form of the document are the result of my interest in the applications of Python and R in data analysis and their cooperation within a single project: how to enable R and Python and how to pass objects between R and Python. Programming was done in RStudio.

The document is available at: https://michaljk.github.io/

# Topic: Two-Way Anova – Example

The problem to be analyzed is the possible effect of two types of coolant on the diameter of the element produced on five different machines. 5 measurements were taken for each machine and for each coolant.

A two-factor analysis of variance was used, performed in R. Anova showed that the type of coolant had no statistically significant effect on the measurement result, while the machine factor was statistically significant.

To identify the machine whose production differed from the rest of the machines, a paired comparison of the results obtained on the tested machines was required. Such a comparison was carried out using Python tools, after downloading R objects from the earlier stage of the calculations.

Finally, the results overview obtained in Python was automated in R.





