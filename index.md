# Guide for oppdatering av innhold på autoplan med nytt design

I forbindelse med det nye designet, må innhold på alle sider oppdateres.

## Komponenter

Meste av innholdet som dere vil lage nå er via komponenter, med unntak av ren tekst og bilder. Det er for å gjøre det så lett som mulig å legge inn innhold som ser bra ut.
Anbefaler å legge inn innhold i samme row (rad) ettersom noen av komponenter har forskjellig mellomrom mellom seg, og dette fungerer bare hvis de er i samme rad. Det eneste unntaket på dette er ved bruk av et bilde som skal blør i raden over.

Komponenter legges inn i rader med fullbredde (knappen til venstre).

![Screenshot 2022-04-08 at 12 35 01](https://user-images.githubusercontent.com/28294971/162419181-aa44d085-2392-4978-95bf-7fb7c0670154.png)

Eneste unntak til dette er med komponentet "A-FORMET BILDE", hvor det fungerer best med bredde 8 på desktop og 12 på mobil. Dette er for at det skal være plass til innhold på siden av bildet:

![Screenshot 2022-04-08 at 12 38 24](https://user-images.githubusercontent.com/28294971/162419631-b91a18f8-edcf-4b86-80ba-3efc53987610.png)
![Screenshot 2022-04-08 at 12 38 54](https://user-images.githubusercontent.com/28294971/162419701-02a0ff76-fe47-4e8e-8a6a-affc20380688.png)

Teksten som skal være ved siden av en "A-FORMET BILDET" må ha klassen "A-formet bilde tekst" slik:

![Screenshot 2022-04-08 at 12 44 11](https://user-images.githubusercontent.com/28294971/162420635-a82a4f69-725a-45f8-8ca7-7cb915711b64.png)

For å endre teksten i seksjonene til komponentet "TOPPSEKSJON FOR FORSIDER", gjøres dette via menypunktet "Seksjoner". Du kan redigere innholdet i seksjonene "Frontpage header section" 1, 2, og 3.

![Screenshot 2022-04-08 at 14 25 14](https://user-images.githubusercontent.com/28294971/162435150-d3cbf555-1e54-441b-bf83-b6d2ac1f59b8.png)

***MERK:*** Merk at komponentet "TOPPSEKSJON FOR FORSIDER" bare skal brukes på forsiden, på alle andre sider kan komponentet "TOPPSEKSJON" benyttes.


### Toppseksjon

Ved bruk av toppseksjon kan det byttes bakgrunnsfarge. Det er bare tatt høyde for bruk av blå eller hvit. Den vil være hvit uten at man velger farge, men hvis bakgrunnsfargen skal være blå velger man å redigere selve raden hvor toppseksjonen finnes og velger blåfarge.

![Screenshot 2022-04-08 at 14 19 04](https://user-images.githubusercontent.com/28294971/162434186-b63e1822-d015-4e7e-a67e-ecf080d13bcf.png)

Alle andre komponenter, tekst og bilder som skal ha samme bakgrunnsfrage legges bare i samme rad. Velger man klassen "Tekstinnhold" på kolonnen vil fargen på teksten automatisk passe til bakgrunnsfargen på raden. Hvit bakgrunn vil gi svart tekst og blå bakgrunn vil gi hvit tekst.


## Tekst og bilder
### Tekst

Tekst legges inn ved å legge til en kolonne som er fullbredde og legger til klassen "Tekstinnhold" som gir innholdet riktig formatering:

![Screenshot 2022-04-08 at 12 44 59](https://user-images.githubusercontent.com/28294971/162420718-b082bd7e-a3d3-4661-b16a-f73e4e3bd0ef.png)

Hvis dere opplever at det er litt lite pusterom i topp eller bunn av en rad så finnes det klasser for dette: "Padding Bunn" og "Padding Topp".


### Bilder

Bilder legges til som tidligere, det er lagt til noen nye klasser som kan brukes på bilder.

![Screenshot 2022-04-08 at 12 47 22](https://user-images.githubusercontent.com/28294971/162421104-b5f05170-65a5-48f0-9955-127e7b2a913a.png)

"Innholdsbilde" gir bildet en maksbredde for å passe designet:

![Screenshot 2022-04-08 at 12 48 28](https://user-images.githubusercontent.com/28294971/162421253-3840d6e5-28e7-40f8-93ca-3f81f59dc109.png)

"Bilde blør i rad over" gjør at bildet flyttes halvveis inn i rad over:

![Screenshot 2022-04-08 at 12 51 56](https://user-images.githubusercontent.com/28294971/162421864-dfdeefbd-f251-4c65-931a-a8583323a761.png)

Dette krever at det brukes to rader hvor bildet er i raden under og hvor raden over som den skal blø inn i har en spesiell klasse "Pading bunn for blødende bilde"

![Screenshot 2022-04-08 at 13 00 19](https://user-images.githubusercontent.com/28294971/162423058-fcd1cb82-38ae-4165-8b6f-9efb7bf6a827.png)


### Meny

Menyen er delt inn i tre menyer "Leasing og biladministrasjon", "Bruktbil, leie og auksjon" og "Om oss".
Endring av menyene fungerer som tidligere.
