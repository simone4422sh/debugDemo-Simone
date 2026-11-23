# debugDemo-Simone

Problem 1:
Skibet var kun horisontalt, aldrig vertikalt. Jeg lavede en breakpoint ud fra methoden hvori jeg ved problemet er, og så gik jeg ind på debug, hvor jeg kunne finde frem til problemet ved at hoppe hen til det næste stykke kode som programmet ville fuldføre, vha. "step into" og "step over". Jeg fandt stedet hvor problemet var, og brugte "evaluate expression" til at undersøge det, og finde frem til løsningen.  

Problem 2:
Selvom skibet var ramt 3 gange, så stod der er skibet vandt. Ligesom før, lavede jeg en breakpoint og brugte "step into" og "step over" til at finde frem til hvor problemet opstod. Fordi metoden før er en while loop, som metoden der skaber problemet giver en værdi til, så laver jeg en conditional breakpoint, fordi jeg er kun intereseret et specifik scenarie hvor tallet er 3, og hvor den burde blive true. Derudfra kunne jeg se at den ikke blev true, fordi at den var sat til tallet skulle være større end 3 for at være true.   

Problem 3:
Spillet mislykkedes fordi skibet blev skabt delvist uden for kortet. Her oprettede jeg mit eget break point ved at kopier exceptionen ind i "java exception breakpoint". Herefter trykkede jeg debug indtil at exceptionen blev triggeret. Nu kan jeg se alle relateret informationer. Den siger at x-placeringen er 10, men den størst mulig indeks er 9. Jeg fiksede det ved at lave noget ekstra code, der gør så at skibet ikke bliver skabt uden for kortet.  
