# Tranzisztor működésének vizsgálata
---
 -A mérést végezte: Benke Balázs
 -A mérés helye. V3 labor
 -A mérés időpontja: 2025.01.07
---
# A tranzisztor mérésének folyamata:
A tranzisztor működésének vizsgálatához az NI myDAQ műszert alkalmaztam. A mérési áramkörbe egy tranzisztort építettem, melynek bázisához egy ellenálláson keresztül tápláltam be a vezérlőjelet. A mérés során figyelemmel kísértem az emitter- és kollektoráramok értékeit, hogy értékeljem az áramkör működését. A mérési folyamat végén a kollektor-ellenálláson eső feszültséget mértem, amely lehetővé tette számomra a tranzisztor működési állapotának és a vezérlőáram hatásának meghatározását. Az adatok alapján elemeztem a tranzisztor erősítési tényezőjét és a kapcsolási jellemzőit is.A méréskor NI myDAQ-t használtam. A méréskor azt is észre vettem, hogy 1.5V után konstans eredményt kapok.

# A kapcsolás
-A kapcsolási rajz: 
![Screenshot_5](https://github.com/user-attachments/assets/8f14f7e9-3a73-4738-9e68-97ffeb64a8f5)
-A kapcsolás megvalósítása: 
![IMG_20250107_125701](https://github.com/user-attachments/assets/ecd65e28-8caa-43b5-8823-1bfd6f86ff90)


# A mérési műszerek:
| Műszer neve: | NI myDAQ | Metek M38 |
|---------|----------|----------|
| Gyártási szám: | 305E1ED | 736015 | 

# A mérési eredmények:
| Ube (V) | URc (V)  | I (mA)   |
|---------|----------|----------|
| 0       | 0        | 0.000    |
| 0.5     | 0.003    | 0.014    |
| 0.6     | 0.113    | 0.514    |
| 0.7     | 0.9      | 4.091    |
| 0.8     | 2.3      | 10.455   |
| 0.9     | 2.63     | 11.955   |
| 1       | 2.65     | 12.045   |
| 1.5     | 2.73     | 12.409   |
