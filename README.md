# 🎬 Informační systém pro sledování a evidenci filmů

---

## 📝 Popis
Jednoduchý osobní informační systém pro evidenci filmů, sledování toho, co uživatel viděl, plánuje shlédnout a jak filmy hodnotil.

---

## 🎯 Cíl systému a cílová skupina
Systém je určen pro:
- **Jednotlivé uživatele**, kteří chtějí mít přehled o svých filmech  
- Filmové nadšence, kteří chtějí evidovat hodnocení a doporučení  

**Hlavní cíl**: umožnit uživateli organizovat svůj filmový archiv, sledovat historii sledování, tvořit seznamy oblíbených filmů a plánovat, na co se chce podívat.

Systém řeší:
- Nepřehledné seznamy filmů v poznámkách či na papíře  
- Zapomínání, co už člověk viděl  
- Obtížné hledání osobních hodnocení  
- Chybějící prostor pro vlastní filmové poznámky a doporučení  

---

## 🔐 Základní funkce (Role a oprávnění)

### 👤 Uživatel (jediná role – osobní systém)
- Přidávat filmy do své databáze  
- Editovat informace o filmech (název, rok, žánr, popis…)  
- Označit film jako:
  - Viděný  
  - Chci vidět  
  - Oblíbený  
- Přiřadit vlastní hodnocení  
- Přidat osobní poznámky nebo krátkou recenzi  
- Vyhledávat filmy podle názvu, žánru nebo roku  
- Filtrovat filmy (viděné / neviděné / oblíbené)  
- Zobrazit statistiky:
  - Počet viděných filmů  
  - Nejoblíbenější žánry  
  - Průměrné hodnocení  

---

## 🗂️ Spravovaná data

### 🎞️ Filmy
- Název  
- Rok vydání  
- Žánr / více žánrů  
- Režisér  
- Délka filmu  
- Krátký popis  
- Stav (viděno / chci vidět / neviděno)  
- Osobní hodnocení  
- Poznámka / recenze  

### ⭐ Uživatelovy seznamy
- Oblíbené filmy  
- Filmy k shlédnutí  
- Viděné filmy  

### 📊 Statistiky (odvozená data)
- Počet filmů celkem  
- Počet filmů viděných  
- Průměrné hodnocení uživatele  
- Nejčastější žánr  
