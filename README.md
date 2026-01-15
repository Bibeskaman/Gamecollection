# Game Collection Manager 🎮 (PRIVE GEBRUIK)

<img src="https://toppng.com/uploads/preview/ps3-png-11553942291zpowxqdmqw.png" align="right" width="150" alt="Game Logo" title="Game Logo">
Een moderne, interactieve web-app om je gameverzameling te beheren. Transformeer je simpele Excel-database in een visueel dashboard met automatische covers, prijsberekeningen en geavanceerde filters.

## 🌐 **[BEKIJK DE LIVE WEBSITE HIER](https://bibeskaman.github.io/Gamecollection/)**

### Table of Contents 🤸

- [Quick Start for Collectors 🐢](#quick-start-for-collectors)
    - [Requirements 📝](#requirements)
    - [Excel Structure 🛠️](#excel-structure)
    - [How to Use 🏃](#how-to-use)

- [Features 🐦‍🔥](#features)
    - [Filtering 🔍](#filtering)
    - [Sidebar Stats 📈](#sidebar-stats)

## <a name="quick-start-for-collectors">Quick Start for Collectors 🐢</a>

### <a name="requirements">Requirements 📝</a>

De applicatie werkt volledig in de browser. Je hebt geen ingewikkelde software nodig, alleen je eigen game-database.

Zorg dat je het volgende hebt voorbereid:

| Requirement               | Description                                          |
| ------------------------- | ---------------------------------------------------- |
| **Excel Bestand** | Een `.xlsx` bestand met je gamegegevens.             |
| **Modern Browser** | Chrome, Firefox of Edge voor de beste ervaring.      |
| **Internetverbinding** | Nodig om online database op te halen.                  |

### <a name="excel-structure"></a>Excel Structure 🛠️

Je Excel-bestand moet de volgende kolommen bevatten op de eerste rij:
```console
├── Console        (bijv. PS3, Switch, PC)
├── Foto_URL       (optioneel: je eigen afbeelding link)
├── Game_Titel     (de naam van het spel)
└── Prijs          (de waarde van het spel)
```

## <a name="how-to-use"></a>Hoe te gebruiken 🏃
1. **Voorbereiden**: Zorg dat je games in het bovenstaande Excel-formaat staan. Voor PlayStation-covers gebruik je de ID in de titel, bijv: `The Last of Us [BCES01584]`.
2. **Inladen**: Open de live website en selecteer je Excel-bestand via de upload-knop.
3. **Navigeren**: Gebruik de tabs om per merk te filteren en de sidebar voor je financiële overzicht.

## <a name="features"></a>Kernfunctionaliteiten 🐦‍🔥

### <a name="filtering"></a>Slimme Filters & Merken 🔍
De app groepeert je games automatisch op basis van merk-families en specifieke consoles:

* **Merk-groepering**: Schakel direct tussen categorieën zoals PlayStation Family, Nintendo World, PC Gaming en Xbox.
* **Sub-filters**: Verfijn je weergave binnen een merk (bijv. toon enkel je PS3 games binnen de PlayStation tab).
* **Real-time Zoekfunctie**: Filter je hele collectie op titel terwijl je typt.

### <a name="sidebar-stats"></a>Collectie Waarde & Stats 📈
Houd de financiële waarde van je hobby nauwkeurig bij via de interactieve sidebar:

* **Totaalwaarde**: Zie in één oogopslag wat je volledige collectie waard is in Euro's.
* **Sectie-analyse**: Bekijk de waarde en het aantal games specifiek per console (bijv. "Totaalwaarde PS2 games: €450,-").
* **Automatische Updates**: De bedragen worden direct herberekend zodra je een nieuw bestand inlaadt of filters aanpast.
