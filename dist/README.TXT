========================
BUILD OUTPUT DESCRIPTION
========================

1. Skopiować folder dist i jego zawartość do wskazanej lokalizacji, np. C:\PDFGenerator
2. Sprawdzić, czy skopiowano wszystkie zbiory
3. Przejść komendą cd do katalogu, gdzie mają być wygenerowane zbiory pdf
4. Uruchomić z linii komend program następującym poleceniem:
java -cp C:\PDFGenerator\dist\*;C:\PDFGenerator\dist\lib\* pdfgenerator.PDFGenerator 3
Uwaga: parametr (jeden), czyli ostatnia cyfra w opisanym wywołaniu powyżej oznacza 
- liczbę generowanych zestawów po 4-ry PDF-y (!), z których każdy zawiera losowo generowane ciągi znaków nad tabelami (3 wiersze) plus długi tekst,
- dodatkowo liczba stron każdego z dokumentów jest w zestawi określona (4,7,18,30). 
 


 
