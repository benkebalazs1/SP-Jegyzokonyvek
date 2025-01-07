# Tranzisztor működésének vizsgálata

 - A mérést végezte: Benke Balázs
 - A mérés helye. V3 labor
 - A mérés időpontja: 2025.01.07

# A tranzisztor mérésének folyamata:
A tranzisztor működését az NI myDAQ eszközzel vizsgáltam, amely lehetővé tette a különböző áramkör-paraméterek pontos mérését. A vizsgálat során egy tranzisztort integráltam az áramkörbe, és a vezérlőjelet egy bázisellenálláson keresztül biztosítottam. A mérés alatt az emitter- és kollektoráramok változásait figyeltem meg, hogy meghatározzam az áramkör viselkedését. A kísérlet végén a kollektor-ellenálláson eső feszültség segítségével sikerült felmérnem a tranzisztor működési állapotát és a vezérlőáram hatását. Az adatok elemzése során meghatároztam a tranzisztor erősítési tényezőjét, valamint a kapcsolás jellemzőit. **A mérési eredmények azt mutatták, hogy 1.5V körüli feszültségnél az értékek stabilizálódnak, és nem változnak tovább**.

# A kapcsolás
-A kapcsolási rajz:

![Screenshot_5](https://github.com/user-attachments/assets/753f3a6e-6f71-487a-8829-33335f478c65)

-A kapcsolás megvalósítása:
![IMG_20250107_125701](https://github.com/user-attachments/assets/ecd65e28-8caa-43b5-8823-1bfd6f86ff90)


# A mérési műszerek:
| Műszer neve: | NI myDAQ | Metek M38 |
|---------|----------|----------|
| Gyártási szám: | 305E1ED | 736015 | 

# A mérési eredmények:
| Ube (V) | URC (V)  | I (mA)   |
|---------|----------|----------|
| 0       | 0        | 0.000    |
| 0.5     | 0.003    | 0.014    |
| 0.6     | 0.113    | 0.514    |
| 0.7     | 0.9      | 4.091    |
| 0.8     | 2.3      | 10.455   |
| 0.9     | 2.63     | 11.955   |
| 1       | 2.65     | 12.045   |
| 1.5     | 2.73     | 12.409   |
