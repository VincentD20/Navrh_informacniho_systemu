# 🎬 Informační systém pro evidenci filmů **Filmdex**
## 📝 Krátký popis 
Webový informační systém pro evidenci filmů, správu uživatelských hodnocení a organizaci filmových seznamů.


 
## 🎯 Cíl systému a cílová skupina 

**Hlavní cíl:** vytvořit přehledný filmový katalog, který umožní uživatelům evidovat, co viděli, co se chystají vidět, a sdílet hodnocení v rámci platformy. 



#### Systém řeší:

- Nepřehledné seznamy filmů v osobních poznámkách   
- Ztrácení přehledu o zhlédnutých filmech   
- Nekonzistentní data o filmech   
- Neexistenci strukturovaného hodnocení a recenzí   

 

## 🔐 Základní funkce (Role a oprávnění) 
### 👤 1. Uživatel 
- Prohlížet seznam filmů
- Přidávat filmy do osobních seznamů (chci vidět / viděné / oblíbené)   
- Hodnotit filmy a psát krátké recenze   
- Upravit svůj profil 
- Vyhledávat filmy podle názvu, žánru nebo roku



### 🛠️ 2. Moderátor 

#### Moderátor má všechny funkce uživatele + navíc: 

- Kontrolovat a schvalovat návrhy na úpravu filmových informací   
- Opravovat nepřesné nebo chybné údaje u filmů   
- Spravovat nevhodné recenze (skrýt / smazat)   
- Spravovat žánry a filmové štítky   

 

### 🛡️ 3. Administrátor (Admin) 

#### Administrátor má plná oprávnění:

- Vytvářet, upravovat a mazat uživatele   
- Přiřazovat a odebírat role (Uživatel / Moderátor / Admin)   
- Přidávat, upravovat a mazat filmy   
- Spravovat systémová nastavení   
- Zobrazovat pokročilé statistiky o aktivitě uživatelů a obsahu   

 

## 🗂️ Spravovaná data 
### 🎞️ Filmy 

- Název   
- Rok vydání
- Žánry   
- Režisér   
- Délka filmu   
- Krátký popis   
- Stav pro uživatele (viděno / chci vidět / neviděno)   
- Průměrné hodnocení   
- Uživatelovy recenze   

 

### 👥 Uživatelé 

- Jméno   
- E-mail   
- Role (Uživatel / Moderátor / Admin)   
- Seznam oblíbených filmů   
- Historie hodnocení   

 

### ⭐ Uživatelské akce 

- Hodnocení filmu   
- Recenze   
- Osobní filmové seznamy   

 

### 📊 Statistiky (odvozená data) 

- Počet registrovaných uživatelů   
- Počet filmů v databázi   
- Nejlépe hodnocené filmy   
- Nejaktivnější uživatelé   
#
