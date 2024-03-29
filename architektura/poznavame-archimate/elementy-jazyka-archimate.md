---
title: Český popis a zobrazení elementů jazyka Archimate
summary: "Pro nearchitekty a v češtině popis všech typů elementů v jazyce Archimate a především jak graficky vypadají. Tady se naučíte číst ty obrázky se čtverečky a šipčičkami..."
layout: page
nav_order: 3
date: 2020-04-09
parent: Poznáváme jazyk Archimate (česky)
---

# Seznam a popis a zobrazení elementů jazyka Archimate

Obsah tohoto dokumentu


- TOC
{:toc}

V tomto dokumentu najdete nejen přehledný popis všech důležitých elementů jazyka Archimate®, ale především zobrazení těchto elementů. Abyste dokázali přečíst jakýkoliv diagram v Archimate, musíte vědě nejen to, co element znamená a jaký je jeho význam a použití v architektuře, ale také to, jak vypadá graficky. Grafická prezentace objektů je totiž v Archimate velice důležitá.

Na tomto místě získáte zcela ojedinělý přehled o tom, jak vypadá vše v Archimate.


## Přehled všech elementů podle vrstev

Níže je seznam všech elementů podle jednotlivých vrstev. Seznam je záměrně řazen dle anglického originálního názvu. U každého elementu je uveden jeho český popis.

1. Strategická vrstva
    - Schopnost (Capability) - Poskytuje pohled na vysoké úrovni o současných a požadovaných schopnostech organizace ve vztahu k její strategii a prostředí. Schopnost je ucelenou sadou dovedností, znalostí, potřeb, kontraktů, procesů, služeb a dalších objektů na všech úrovních, které dohromady dávají definovatelný celek.
    - Prováděcí postup (CourseOfAction) - Prováděcí postup je přístup nebo plán pro konfiguraci některých schopností a zdrojů podniku, prováděných za účelem dosažení cíle. Prováděcí postup představuje to, co se podnik rozhodl udělat. Lze je kategorizovat jako strategie (dlouhodobé) a taktiky (krátkodobé).
    - Zdroj (Resource) - Představuje definovatelný zdroj, který je za potřebí mít k dodažení strategie a který se využije pro realizaci strategií, byznysu a procesů.
    - Tok (ValueStream) - Tok hodnot představuje sled činností, které vytvářejí celkový výsledek pro zákazníka, zúčastněné strany nebo koncového uživatele. Hodnotový tok popisuje, jak podnik organizuje své činnosti tak, aby vytvářel hodnotu. Proudy hodnot jsou obvykle realizovány podnikovými procesy, a případně dalšími klíčovými prvky chování. Proudy hodnot mohou být definovány na různých úrovních organizace, např. na úrovni podniku, obchodní jednotky nebo oddělení. Proudy hodnot mohou být složením nebo agregací činností s přidanou hodnotou. Tyto jsou také modelovány s prvkem hodnotového toku a jsou známé jako hodnotové (proudové) fáze, z nichž každá vytváří a přidává inkrementální hodnotu z jedné fáze do další. Tyto fáze jsou obvykle spojeny pomocí tokových vztahů k modelování toku hodnoty mezi nimi.
2. Byznysová vrstva
    - Aktér, Účastník (BusinessActor) - Aktér/Účastník je definován jako organizační jednotka schopna vykonávat aktivitu přiřazenou k jedné nebo více byznys rolím. Aktér je subjekt, může to být jedna organizace, organizační jednotka, OVM, nebo samozřejmě i osoba.
    - Spolupráce (BusinessCollaboration) - Spojení dvou a více rolí pracující společně k vykonání určitého kolektivního chování. Nebo jiná spolupráce rolí.
    - Událost, procesní událost (BusinessEvent) - Něco, co se stává (interně nebo externě) a ovlivňuje chování.
    - Funkce (byznysově) (BusinessFunction) - Prvek chování, který seskupuje chování podle vybraná sady kritérií (typicky požadovaných dovedností, znalostí, zdrojů).
    - Interakce (BusinessInteraction) - Prvek chování, který popisuje chování spolupráce.
    - Rozhraní (BusinessInterface) - Přístupový bod, kde je procesní služba dostupná okolnímu prostředí. Tedy kupříkladu terminál, uživatelské rozhraní, rozhraní služby, ale může to de facto být i formulář.
    - Objekt (BusinessObject) - Pasivní element, který má relevanci z předmětného pohledu. Jedná se o fyzický či logický objekt, o němž se vykonává proces či služba. Dokument, doklad, žádost, dávka, rozhodnutí, prakticky cokoliv, co se dá fyzicky či logicky reprezentovat.
    - Proces (BusinessProcess) - Prvek chování, který sdružuje skupiny chování na základě pořadí činností. Je určen k produkování sady produktů nebo byznys služeb.
    - Role (BusinessRole) - Role je fakticky zodpovědnost za vykonávání specifického chování, ke které může být přiřazen účastník procesu.
    - Byznysová služba (BusinessService) - Byznys služba je definována jako služba, která naplňuje potřeby zákazníka (interního nebo externího vůči poskytující organizaci).
    - Kontrakt, předpis (Contract) - Formální nebo neformální specifikace dohody, která specifikuje práva a povinnosti spojené s produktem.
    - Produkt (Product) - Produkt je soubor služeb definovaných kontraktem (zákonem), které jsou společně poskytovány klientovi (pro jeho životní situaci).
    - Reprezentace (Representation) - Smyslově vnímatelná forma informací spojených s byznys objektem. Tedy kupříkladu fyzický dokument, plastová kartička občanského průkazu apod.
3. Aplikační vrstva
    - Aplikační spolupráce (ApplicationCollaboration) - Souhrn dvou nebo více komponent aplikací, které pracují společně za účelem vykonání kolektivního chování
    - Aplikace, Systém, Komponenta aplikace, Modul, Část aplikace (ApplicationComponent) - Modulární, nasaditelná a nahraditelná část softwarového systému, zapouzdřující své chování a data, která poskytuje skrz sadu rozhraní. Může se jednat o celý logický informační systém, o nějakou ucelenou komponentu nebo modul, nebo o část aplikace, jež se nasazuje a rozvíjí jako část celku.
    - Aplikační funkce (ApplicationFunction) - Aplikační funkce je definována jako interní chování jedné aplikační komponenty.
    - Interakce aplikace (ApplicationInteraction) - Prvek chování, který popisuje chování aplikací při jejich kooperaci.
    - Rozhraní aplikace, Aplikační rozhraní (ApplicationInterface) - Přístupový bod, ve kterém je služba aplikace dostupná pro využití uživatelem nebo jinou komponentou aplikace.
    - Aplikační služba (ApplicationService) - Služba, která poskytuje automatizované chování.
    - Datový objekt (DataObject) - Pasivní element, který je zpracováván za použití výpočetní techniky. Jedná se o data, soubor dat nebo údajů, které jsou zpracovávány většinou v rámci aplikační komponenty.
4. Technologická vrstva
    - Artefakt (Artifact) - Artefaktem se rozumí fyzická reprezentace dat, která je používána či vytvářena systémem.
    - Zařízení (Device) - Hardwarový zdroj, na kterém mohou být skladovány nebo dislokovány artefakty pro použití.
    - Síť (Network) - Komunikační medium mezi dvěma nebo více zařízeními.
    - Uzel (Node) - Výpočetní zdroj, na kterém mohou být skladovány, dislokovány nebo zpracovávány artefakty pro použití. Poskytuje především služby výpočetního výkonu a datových kapacit.
    - Cesta (CommunicationPath) - Spojení mezi dvěma nebo více uzly, skrze které si mohou tyto uzly vyměňovat data.
    - Systémový software (SystemSoftware) - Softwarové prostředí pro speciální typ komponentů a objektů, které jsou na něm rozmístěny ve formě artefaktů.
    - Rozhraní infrastruktury (TechnologyInterface) - Přístupový bod, kde služby infrastruktury nabízené uzlem mohou být využity jiným uzlem nebo komponentou aplikace.
    - Služby infrastruktury (TechnologyService) - Externě viditelná jednotka funkcionality poskytovaná jedním nebo více uzly, která je přístupná přes dobře definované rozhraní a má význam pro okolí.
5. Motivační vrstva
    - Zhodnocení (Assesment) - Výsledek analýzy motivátoru. Zhodnucuje dopad motivátoru na organizaci a zhodnocuje výsledek analýzy nasazení změn pro splnění daného motivátoru.
    - Omezení (Constraint) - Omezení na cestě k realizaci systému.
    - Motivátor (Driver) - Motivátor je definován jako okolnost, která vytváří, motivuje a podporuje změnu v organizaci.
    - Cíl (Goal) - Koncový stav, kterého chce zainteresovaný subjekt (stakeholder) dosáhnout.
    - Význam (Meaning) - Znalost nebo odbornost přítomná v byznys objektu nebo v jeho reprezentaci
    - Výstup (Outcome) - Reprezentuje jednoznačný výstup, zejména jako výsledek schopností organizace či výsledek obchodního snažení nebo realizace strategie. Výstup je buď hmatatelný na úrovni dovednosti vytvářet produkt, nebo se jedná o výstup jež se pozitivně odráží na podnikání či činnosti organizace. Jednou z motivací pro zlepšení organizace je tedy dovednost učinit výstup.
    - Princip (Principle) - Normovaná vlastnost všech systémů v daném kontextu, nebo způsob jejich realizace. Principy vycházejí ze strategických cílů a svými důsledky formují a formulují architektonické požadavky.
    - Požadavek (Requirement) - Stanovisko, formálně vyjádřená potřeba, která musí být v systému (resp. architekturou) realizována. Jedná se o architektonické nikoli byznysové požadavky.
    - Zainteresovaný subjekt (Stakeholder) - Zainteresovaný jedinec, tým nebo organizace, která má zájem na přínosu architektury.
    - Hodnota (Value) - Hodnota představuje přínos, užitek nebo důležitost produktu či služby
6. Implementační vrstva
    - Dodaný výstup (Deliverable) - Přesně definovaný výsledek pracovního bloku.
    - Rozdíl (Gap) - Rozdíl je napojený na dva stavy architektury (např. výchozí a cílovou nebo dvě přechodové), a tudíž představuje znázornění rozdílů mezi těmito dvěma stavy architektury.
    - Stav architektury (Plateau) - Relativně stabilní stav architektury, která existuje (existovala) během omezeného časového období.
    - Pracovní blok (WorkPackage) - Série akcí navržená tak, aby dosáhla vytyčeného cíle ve specifikovaném čase.
7. Ostatní elementy mimo vrstvy
    - Spojení (Junction) - Spojení slouží k vyjádření toho, že se na nějakém vztahu podílí více prvků. Může se jednat o více prvků na vstupu a jediný na výstupu, o jeden na vstupu a více na výstupu a nebo o více prvků na obou stranách. Slouží k vyjádření, že pro realizaci daného vztahu je nutno počítat se zapojením více elementů.
    - Lokalita, místo (Location) - Místo v prostoru, kde se nacházejí aktéři nebo kde je vykonáváno chování.

## Popis a znázornění klíčových elementů jazyka Archimate


Elementy jsou zobrazováni v pohledech, tedy obrázkových diagramech. Aby i neodborník dokázal snadno tyto diagramy číst, níže je grafické znázornění elementů pro jednotlivé vrstvy následováné vždy tabulkou pro danou vrstvu s vysvětlením významu elementu.

### Klíčové elementy Archimate na strategické vrstvě

Od strategie se vše odvíjí. Strategie je základ pro jakékoliv konání, včetně popisu a změn v architektuře. Pro strategii jsou důležité schopnosti a zdroje, nicméně samotná strategie je základem pro další vrstvy. Proto je také vždy na prvním místě.

![Diagram Zobrazení Archimate elementů (strategická vrstva)](zobrazeni_archimate_elementu_strategicka_vrstva.png)

| Element | Popis |
|---|---|
| Prováděcí postup (CourseOfAction) | Prováděcí postup je přístup nebo plán pro konfiguraci některých schopností a zdrojů podniku, prováděných za účelem dosažení cíle. Prováděcí postup představuje to, co se podnik rozhodl udělat. Lze je kategorizovat jako strategie (dlouhodobé) a taktiky (krátkodobé).|
| Schopnost (Capability) | Poskytuje pohled na vysoké úrovni o současných a požadovaných schopnostech organizace ve vztahu k její strategii a prostředí. Schopnost je ucelenou sadou dovedností, znalostí, potřeb, kontraktů, procesů, služeb a dalších objektů na všech úrovních, které dohromady dávají definovatelný celek.|
| Tok (ValueStream) | Tok hodnot představuje sled činností, které vytvářejí celkový výsledek pro zákazníka, zúčastněné strany nebo koncového uživatele. Hodnotový tok popisuje, jak podnik organizuje své činnosti tak, aby vytvářel hodnotu. Proudy hodnot jsou obvykle realizovány podnikovými procesy, a případně dalšími klíčovými prvky chování. Proudy hodnot mohou být definovány na různých úrovních organizace, např. na úrovni podniku, obchodní jednotky nebo oddělení. Proudy hodnot mohou být složením nebo agregací činností s přidanou hodnotou. Tyto jsou také modelovány s prvkem hodnotového toku a jsou známé jako hodnotové (proudové) fáze, z nichž každá vytváří a přidává inkrementální hodnotu z jedné fáze do další. Tyto fáze jsou obvykle spojeny pomocí tokových vztahů k modelování toku hodnoty mezi nimi.|
| Zdroj (Resource) | Představuje definovatelný zdroj, který je za potřebí mít k dodažení strategie a který se využije pro realizaci strategií, byznysu a procesů.|


### Klíčové elementy Archimate na byznysové vrstvě

V této vrstvě se popisuje vše, co děláme, protože vše, co činíme, je součástí našeho byznysu. Ať už se opravdu jedná o byznys jako obchod, nebo o naplnění našeho poslání, na této vrstvě musíme vyjádřit, co vlastně děláme, kdo to dělá, jak to dělá a s kým či pro koho to dělá. Byznys je uváděn hned pod strategií, protože je to prostě náš byznys.

![Diagram Zobrazení Archimate elementů (byznysová vrstva)](zobrazeni_archimate_elementu_byznysova_vrstva.png)

| Element | Popis |
|---|---|
| Aktér, Účastník (BusinessActor) | Aktér/Účastník je definován jako organizační jednotka schopna vykonávat aktivitu přiřazenou k jedné nebo více byznys rolím. Aktér je subjekt, může to být jedna organizace, organizační jednotka, OVM, nebo samozřejmě i osoba.|
| Byznysová služba (BusinessService) | Byznys služba je definována jako služba, která naplňuje potřeby zákazníka (interního nebo externího vůči poskytující organizaci).|
| Funkce (byznysově) (BusinessFunction) | Prvek chování, který seskupuje chování podle vybraná sady kritérií (typicky požadovaných dovedností, znalostí, zdrojů).|
| Interakce (BusinessInteraction) | Prvek chování, který popisuje chování spolupráce.|
| Kontrakt, předpis (Contract) | Formální nebo neformální specifikace dohody, která specifikuje práva a povinnosti spojené s produktem.|
| Objekt (BusinessObject) | Pasivní element, který má relevanci z předmětného pohledu. Jedná se o fyzický či logický objekt, o němž se vykonává proces či služba. Dokument, doklad, žádost, dávka, rozhodnutí, prakticky cokoliv, co se dá fyzicky či logicky reprezentovat.|
| Proces (BusinessProcess) | Prvek chování, který sdružuje skupiny chování na základě pořadí činností. Je určen k produkování sady produktů nebo byznys služeb.|
| Produkt (Product) | Produkt je soubor služeb definovaných kontraktem (zákonem), které jsou společně poskytovány klientovi (pro jeho životní situaci).|
| Reprezentace (Representation) | Smyslově vnímatelná forma informací spojených s byznys objektem. Tedy kupříkladu fyzický dokument, plastová kartička občanského průkazu apod.|
| Role (BusinessRole) | Role je fakticky zodpovědnost za vykonávání specifického chování, ke které může být přiřazen účastník procesu.|
| Rozhraní (BusinessInterface) | Přístupový bod, kde je procesní služba dostupná okolnímu prostředí. Tedy kupříkladu terminál, uživatelské rozhraní, rozhraní služby, ale může to de facto být i formulář.|
| Spolupráce (BusinessCollaboration) | Spojení dvou a více rolí pracující společně k vykonání určitého kolektivního chování. Nebo jiná spolupráce rolí.|
| Událost, procesní událost (BusinessEvent) | Něco, co se stává (interně nebo externě) a ovlivňuje chování.|



### Klíčové elementy Archimate na aplikační vrstvě

Na této vrstvě popisujeme aplikace, programy, data, výměnu dat, a vše co zajistí, že byznys budeme schopni s pomocí ICT opravdu dělat. A to včetně technických dat a databází a systémů, které pro nás zajišťují fungování onoho byznysu v praxi.

![Diagram Zobrazení Archimate elementů (aplikační vrstva)](zobrazeni_archimate_elementu_aplikacni_vrstva.png)

| Element | Popis |
|---|---|
| Aplikace, Systém, Komponenta aplikace, Modul, Část aplikace (ApplicationComponent) | Modulární, nasaditelná a nahraditelná část softwarového systému, zapouzdřující své chování a data, která poskytuje skrz sadu rozhraní. Může se jednat o celý logický informační systém, o nějakou ucelenou komponentu nebo modul, nebo o část aplikace, jež se nasazuje a rozvíjí jako část celku.|
| Aplikační funkce (ApplicationFunction) | Aplikační funkce je definována jako interní chování jedné aplikační komponenty.|
| Aplikační služba (ApplicationService) | Služba, která poskytuje automatizované chování.|
| Aplikační spolupráce (ApplicationCollaboration) | Souhrn dvou nebo více komponent aplikací, které pracují společně za účelem vykonání kolektivního chování|
| Datový objekt (DataObject) | Pasivní element, který je zpracováván za použití výpočetní techniky. Jedná se o data, soubor dat nebo údajů, které jsou zpracovávány většinou v rámci aplikační komponenty.|
| Interakce aplikace (ApplicationInteraction) | Prvek chování, který popisuje chování aplikací při jejich kooperaci.|
| Rozhraní aplikace, Aplikační rozhraní (ApplicationInterface) | Přístupový bod, ve kterém je služba aplikace dostupná pro využití uživatelem nebo jinou komponentou aplikace.|



### Klíčové elementy Archimate na technologické vrstvě

Někdy označovaná i jako infrastrukturní. Jedná se o vrstvu všech technologických prostředků a zařízení, které potřebujeme k tomu, aby nám fungovaly aplikace a systémy a data, a tedy abychom s technickou pomocí mohli dělat byznys a plnit naši strategii. Místy je dost problematické odlišovat aplikační a technologickou vrstvu a jednotlivé elementy (zejména softwarové) se často zaměňují.

![Diagram Zobrazení Archimate elementů (technologická vrstva)](zobrazeni_archimate_elementu_technologicka_vrstva.png)

| Element | Popis |
|---|---|
| Artefakt (Artifact) | Artefaktem se rozumí fyzická reprezentace dat, která je používána či vytvářena systémem.|
| Cesta (CommunicationPath) | Spojení mezi dvěma nebo více uzly, skrze které si mohou tyto uzly vyměňovat data.|
| Rozhraní infrastruktury (TechnologyInterface) | Přístupový bod, kde služby infrastruktury nabízené uzlem mohou být využity jiným uzlem nebo komponentou aplikace.|
| Služby infrastruktury (TechnologyService) | Externě viditelná jednotka funkcionality poskytovaná jedním nebo více uzly, která je přístupná přes dobře definované rozhraní a má význam pro okolí.|
| Systémový software (SystemSoftware) | Softwarové prostředí pro speciální typ komponentů a objektů, které jsou na něm rozmístěny ve formě artefaktů.|
| Síť (Network) | Komunikační medium mezi dvěma nebo více zařízeními.|
| Uzel (Node) | Výpočetní zdroj, na kterém mohou být skladovány, dislokovány nebo zpracovávány artefakty pro použití. Poskytuje především služby výpočetního výkonu a datových kapacit.|
| Zařízení (Device) | Hardwarový zdroj, na kterém mohou být skladovány nebo dislokovány artefakty pro použití.|



### Klíčové elementy Archimate na motivační vrstvě

Motivační vrstva ukazuje to, co motivuje či donucuje ke změnám v byznysu a v architektuře. Tedy motivací může být nějaký požadavek, externí vliv, zvýšení poptávky či cíl zvýšení kvality, nebo nějaké nové omezení způsobené změnou legislativy apod. V motivační vrstvě najdeme také trochu nelogicky reprezentaci požadavků, včetně požadavků na byznys a aplikace a technologie.

![Diagram Zobrazení Archimate elementů (motivační vrstva)](zobrazeni_archimate_elementu_motivacni_vrstva.png)

| Element | Popis |
|---|---|
| Cíl (Goal) | Koncový stav, kterého chce zainteresovaný subjekt (stakeholder) dosáhnout.|
| Hodnota (Value) | Hodnota představuje přínos, užitek nebo důležitost produktu či služby|
| Motivátor (Driver) | Motivátor je definován jako okolnost, která vytváří, motivuje a podporuje změnu v organizaci.|
| Omezení (Constraint) | Omezení na cestě k realizaci systému.|
| Požadavek (Requirement) | Stanovisko, formálně vyjádřená potřeba, která musí být v systému (resp. architekturou) realizována. Jedná se o architektonické nikoli byznysové požadavky.|
| Princip (Principle) | Normovaná vlastnost všech systémů v daném kontextu, nebo způsob jejich realizace. Principy vycházejí ze strategických cílů a svými důsledky formují a formulují architektonické požadavky.|
| Výstup (Outcome) | Reprezentuje jednoznačný výstup, zejména jako výsledek schopností organizace či výsledek obchodního snažení nebo realizace strategie. Výstup je buď hmatatelný na úrovni dovednosti vytvářet produkt, nebo se jedná o výstup jež se pozitivně odráží na podnikání či činnosti organizace. Jednou z motivací pro zlepšení organizace je tedy dovednost učinit výstup.|
| Význam (Meaning) | Znalost nebo odbornost přítomná v byznys objektu nebo v jeho reprezentaci|
| Zainteresovaný subjekt (Stakeholder) | Zainteresovaný jedinec, tým nebo organizace, která má zájem na přínosu architektury.|
| Zhodnocení (Assesment) | Výsledek analýzy motivátoru. Zhodnucuje dopad motivátoru na organizaci a zhodnocuje výsledek analýzy nasazení změn pro splnění daného motivátoru.|





### Klíčové elementy Archimate na implementační vrstvě

Na této vrstvě se řeší změna určitého stavu ze současného (as-is) do budoucího chtěného (to-be) a to, co se musí pro tuto změnu udělat. Tedy implementace nového byznysu, implementace nových aplikací či jejich změn apod. 

![Diagram Zobrazení Archimate elementů (implementační vrstva)](zobrazeni_archimate_elementu_implementacni_vrstva.png)

| Element | Popis |
|---|---|
| Dodaný výstup (Deliverable) | Přesně definovaný výsledek pracovního bloku.|
| Pracovní blok (WorkPackage) | Série akcí navržená tak, aby dosáhla vytyčeného cíle ve specifikovaném čase.|
| Rozdíl (Gap) | Rozdíl je napojený na dva stavy architektury (např. výchozí a cílovou nebo dvě přechodové), a tudíž představuje znázornění rozdílů mezi těmito dvěma stavy architektury.|
| Stav architektury (Plateau) | Relativně stabilní stav architektury, která existuje (existovala) během omezeného časového období.|



### Ostatní líčové elementy Archimate mimo základní vrstvy

![Diagram Zobrazení Archimate elementů (ostatní)](zobrazeni_archimate_elementu_ostatni.png)

| Element | Popis |
|---|---|
| Lokalita, místo (Location) | Místo v prostoru, kde se nacházejí aktéři nebo kde je vykonáváno chování.|
| Spojení (Junction) | Spojení slouží k vyjádření toho, že se na nějakém vztahu podílí více prvků. Může se jednat o více prvků na vstupu a jediný na výstupu, o jeden na vstupu a více na výstupu a nebo o více prvků na obou stranách. Slouží k vyjádření, že pro realizaci daného vztahu je nutno počítat se zapojením více elementů.|

