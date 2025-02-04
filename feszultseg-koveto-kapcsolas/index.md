# Feszültség követő kapcsolás

## Feszültség követő kapcsolás építése:
- A mérést végezte: Benke Balázs
- A mérés helye: V3 labor
- A mérés időpontja: 2025.02.04

## Jelemzője:
A feszültségkövető (más néven: feszültségkövető erősítő, vagy buffererősítő) egy olyan kapcsolás, amely a bemeneti feszültség pontos másolatát adja ki a kimeneten, miközben az áramot nem erősíti, hanem azt a bemenethez viszonyítva „követi”. Ennek a kapcsolásnak az alapvető jellemzője, hogy a kimeneti feszültség megegyezik a bemeneti feszültséggel, de nagy bemeneti impedanciával és alacsony kimeneti impedanciával rendelkezik.

## Kapcsolási rajz:
Kapcsolási rajz:

## Kép:
![Képkivágás](https://github.com/user-attachments/assets/023729c6-3748-48d1-a951-769d6851961e)

## Gyakorlati megvalósítása:
![IMG_6335](https://github.com/user-attachments/assets/27dbc496-e341-483d-bcd8-9b3fbaa0603b)

## TL071 IC:
A TL071 egy népszerű, alacsony zajszintű, egyszálas (single) operációs erősítő IC, amelyet gyakran használnak különböző analóg áramkörökben. A Texas Instruments gyártotta, és a TL071 az operációs erősítők egy jól ismert családjának a tagja. Az IC-t különböző alkalmazásokhoz tervezték, például erősítők, szűrők, analóg jelek feldolgozása és egyéb analóg áramkörökben.

Főbb jellemzők és paraméterek:
Bemeneti jellemzők:
- Alacsony bemeneti torzítás: A TL071 alacsony bemeneti torzítással rendelkezik, ami azt jelenti, hogy nem okoz jelentős eltéréseket a bemeneti jelben.
Nagyon magas bemeneti impedancia: Az IC rendkívül magas bemeneti impedanciát biztosít, amely elhanyagolható áramot vesz fel a bemeneti forrástól, így az nem befolyásolja a bemeneti jel erősségét.
Kimeneti jellemzők:
- Alacsony kimeneti impedancia: A kimeneti impedanciája alacsony, így képes nagy áramot szolgáltatni anélkül, hogy a kimeneti feszültség jelentősen csökkenne.
Feszültség és áram:
- Tápfeszültség: A TL071 típust az egyenfeszültségű tápegységekkel használják, és támogatja a ±3V és ±18V közötti tápfeszültséget (vagy 6V és 36V között is), így a sokoldalúsága kiemelkedő.

Nagyfokú érzékenység:
- A TL071 jól működik alacsony frekvenciájú alkalmazásokban, különösen amikor alacsony zajra van szükség. Alacsony offset feszültséggel és alacsony torzítással rendelkezik, ami különösen fontos precíz jelfeldolgozó áramköröknél.

Működési jellemzők:
- Alacsony zajszint: A TL071 kifejezetten alacsony zajt generál, ami fontos jelfeldolgozásnál, ahol minden kis zajkibocsátás hátrányos lehet.
- Kimeneti áram: A kimeneti áram korlátozott, de elegendő a legtöbb analóg alkalmazáshoz, például erősítő áramkörökhöz és jelerősítéshez.
- Frekvenciaválasz: A TL071 operációs erősítő frekvenciaválasza is elég jó, és képes kezelni a viszonylag magas frekvenciájú jeleket is, mivel nagy nyitott hurok erősítése van (open-loop gain), amely általában 100,000 vagy annál nagyobb.
- Használati alkalmazások:
A TL071 egy sokoldalú IC, amelyet széles körben alkalmaznak az elektronikai iparban és hobbi áramkörökben. Néhány példa a tipikus alkalmazásokra:

Alkalmazások:
- Jelerősítés: A TL071 gyakran használatos kis jelszintű jelek erősítésére, például mikrofonok, szenzorok és más alacsony szintű bemeneti jelek esetében.
- Szűrők: Aktív szűrőkben, mint például aluláteresztő, felüláteresztő, vagy sávszűrők, gyakran alkalmazzák a TL071-et, mivel jól kezeli a különböző analóg jelalakokat.
- Jelfeldolgozás: A precíz analóg jelfeldolgozás során, például jelfeldolgozó rendszerekben, ahol alacsony zaj és magas linearitás szükséges.
- Feszültségkövetők: A TL071 egy feszültségkövető (buffererősítő) szerepét is betöltheti, mivel magas bemeneti impedanciája és alacsony kimeneti impedanciája van, így alkalmas jelek átvitelére torzítás nélkül.
