För att du som teknolog lättare ska få en översikt hur kurser på dtek relaterar till varandra  har vi skapat en graf där vi vill visa relationer mellan kurser på TKDAT-1,2,3,MPALL och MPCSN. När grafen är färdig kommer den tryckas upp på ett stort papper och sättas upp i basen.

Vi behöver hjälp med att fylla i relationer och kurser, speciellt från dig som läser CSN, men är glada för all feedback.

## Stilguide
Obestämt, kolla issues.

* Låt transitiva kanter som kan förtydliga vad som är viktigt för en kurs vara kvar. Skapa ett "issue" om osäkerhet uppstår.
* "Committa" inte PDF filer till arkivet, då det skapar merge-conflicts.

## Dependencies
* Graphviz
* DejaVu Sans TTF font

## Dtek?
Går du på DTEK?
Tycker du någon kurs saknas eller något beroende är fel? 
Ändra och skapa pull-requests!  

## Kompilera
För linux:

Med transitiva kanter:
```
./compile
```

Utan transitiva kanter:
```
./compile reduce
```
