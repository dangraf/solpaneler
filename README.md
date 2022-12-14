
# Solpaneler överblick


## Delar som krävs för en solcellsanläggning:
- https://www.energimyndigheten.se/fornybart/solelportalen/har-mitt-hus-ratt-forutsattningar/det-har-ingar-i-en-solcellsanlaggning/
- Solceller
- Monteringssystem
- växelriktare
- Anslutning

## Kalkyl inkomster/utgifter för egenproducerad el:
https://www.solcellskollen.se/blogg/sa-mycket-sparar-du-pa-elrakningen-med-solceller-en-genomgang

## Får man göra jobbet själv?
Man får montera upp solcellerna själv men själva inkopplingen av el måste gjöras av behörig elektriker
https://hemsol.se/solceller/montera-sjalv/

## Föranmälan till elbolaget
https://www.ellevio.se/privat/solceller/solceller-steg-for-steg/innan-installation/
Man behöver hitta en elektriker som kan göra jobbet med att koppla in solcellsanläggningen. Denna behöver ta kontakt med Ellevio för att få ett godkännande/nekande om man kan koppla in celler i anläggningen.

## Bygglov:
här finns reglerna för [bygglov](https://www.boverket.se/sv/PBL-kunskapsbanken/lov--byggande/anmalningsplikt/byggnader/andring/sol/).
Det verkar inte som att man behöver ett bygglov men reglerna är luddiga:
"Solfångare eller solcellspaneler som monteras utanpå en byggnads fasadbeklädnad eller taktäckningsmaterial är i vissa fall bygglovsbefriade även om de medför att byggnadens yttre utseende avsevärt påverkas. Undantaget från krav på bygglov gäller för alla typer av byggnader. Följande kriterier ska vara uppfyllda för att sådana solfångare och solcellspaneler ska vara bygglovsbefriade:

    de ska monteras utanpå en byggnads fasadbeklädnad eller taktäckningsmaterial
    de ska följa byggnadens form
    de får inte monteras på byggnader eller inom bebyggelseområden som är särskilt värdefulla
    de får inte monteras inom eller i anslutning till områden som är av riksintresse för totalförsvaret
    att solenergianläggningen inte kräver bygglov enligt den detaljplan som gäller för området
"
Todo: hur får man svar på detta? byggnadskontoret har en svarstid på flera månader. Finns det andra sätt att få svar på frågan för att snabbare?

# Solceller:
## Info för Top 3 paneler
* Test över olika solpaneler: https://www.solcellsofferter.se/solceller-bast-i-test/

| namn | pris/panel:20st | url för betällning | storlek | effekt | W/€ |
|---|---|---|---|---|---|
| Maxeon 3 | 370€ (inc frakt) |  [https://www.europe-solarstore.com/sunpower-spr-max3-400.html| 1046x1690 | 400Wp | 1.08W/€ |
| LG neon r | 317€ (inc frakt) | https://www.europe-solarstore.com/solar-panels/manufacturer/lg/lg-neon-r-lg360q1c-a5.html | 1016x1700 | 365Wp | 1.15W/€ |
| REC Alpha | 335€ (inc frakt) | https://www.mg-solar-shop.com/rec-solar-alpha-pure-series-405-solar-panel-405wp-monocrystalline | 1016x1821 | 405Wp | 1.21 W/€ |

Faktorer som borde beaktas när man väljer solpanel:
- **Storleken:** nästan samma mellan tillverkarna. vi vill ha så många paneler som möjligt på vårt tak.
- **övriga faktorer:** kanske kolla mer på de olika teknikerna (t.ex monokristalin) för att se vilka som ger bäst effekt vid mulet väder eller skugga (med tanke på träden)

## Storlek på anläggningen:
Rottnerosbacken 36 har plats för 19-20st paneler vilket ger en effekt av 8kW. Uträkningen gjordes [här](Ritningar_tak.md)
## Summering solceller:
- 20 paneler: 20 * 335€ * 10.63kr/€=71200:-

# Inverter/växelriktare.
https://www.solcellskollen.se/blogg/sa-valjer-du-en-bra-vaxelriktare
Det verkar finnas hybridväxlare om man vill använda sig av ett batteri (kan lägga till batteri senare) eller "vanliga" växelriktare. Man kan även använda sig av "optimerare" som man monterar på varje eller vartannan panel. Växelriktaren dimentioneras normal till ca 20% under anläggningens effekt eftersom det är sällan som den producerar max effekt. 8*0.8 = 6.4Kw 
- Huawei 6kW, 3-fas 1470€: https://www.mg-solar-shop.com/huawei-sun2000-6ktl-m1-hybrid-inverter
- Kostal PIKO 7kW, 1902€, https://www.mg-solar-shop.com/kostal-piko-7.0-iq-pv-inverter

### Switchar till slingor:
Det behövs även införskaffas switchar så att man kan utföra service på boxen.
Hur räknar man ut hur många slingor man behöver?
### Kabeldragning
Det behövs kablar från taket ner till inverteraren kabelarean borde ligga på ca 6m2 eller mer beroende på strömmen och hur många slingor.

### Optimerare:
https://www.solcellskollen.se/blogg/optimerare-till-solcellsanlaggningen-vi-reder-ut-vad-som-ar-bra-att-tanka-pa
Hanterar och ger status per solcellspanel så att inte någon panel begränsar övriga vid t.ex skugga av löv eller annat. Men de brukar kosta extra att sätta in dessa, ca 5-10% ökad installationskostnad

# Batterier:
Här finns en [bra guide](https://www.solcellskollen.se/blogg/med-lagre-kostnader-och-gront-avdrag-ar-det-lage-att-skaffa-batterier-till-sina-solceller)
En villa förbrukar mellan 25-40kWh /dag. Ett batteri kostar ung 11000:-/kWh. Det finns ett grönt avdrag för batterier på ca 48.5% vilket gör att ett batter som kostar 70.000:- blir priset ca 36.000kr efter avdrag.
Enligt artikeln skiljer sig priset mellan att sälja el och köpa el ca 15 öre samt att batteriet klarar max 4000 laddningar vilket gör att det ännu inte är lönt att skaffa batteri till anläggningen. Alternativt kan batteriet användas för att jämna ut strömspikar på elnätet vilket kan reducera nätavgifter med ca 1-2000kr. men det är inte aktuellt i vårt fall då vi inte har någon t.ex elbil som kräver mycket ström.

# Monteringsdetaljer
??

# Plan:
1. Ta reda på allt material och en idee om hur anläggningen skall se ut samt kapacitet och kostnad för material
1. Ta reda om om man behöver bygglov för solceller här på rottnerosbacken.
1. Hitta en elektriker som kan göra jobbet med att installera elen för solcellerna samt kostnad.
1. avgöra om man vill gjöra jobbet själv eller om man vill lägga ut allt på någon annan. 
3. Göra beställningen av alla delar.
... Hur göra med grannens stege som är inne på vårt tak just nu?
... Hur göra med takbrygga om vi är det enda huset som skaffar solceller?

# Kostnader
1. flytta/byta ut takbrygga (10.000:-), stege skorsten (ca 7000:-), stege gavel (6000:-/3) : **Totalt 20.000:-** 
#### alt 1: 8kWp anläggning (20 paneler)
2. material solpaneler: (paneler8kWp: 72000:-), växelriktare (15.000:-), optimerare (12.000:-), DC switchar (1200:-), kablar(1000:- ??): **Totalt  102,000:-**
### alt 2: 6.4kWp anläggning
material solpaneler: (paneler8kWp: 57000:-), växelriktare (15.000:-), optimerare (12.000:-), DC switchar (1200:-), kablar(1000:- ??): **Totalt  87,000:-*

ej inräknat material för infästning av solceller

15% grönt avdrag kan göras av installatören, oklart hur man gör detta avdrag om man köper material själv.

# alternativ:
[Ikea solcellspaket 10.1kWp:](https://www.ikea.com/se/sv/clean-energy/solar-systems/) 126.000:-
