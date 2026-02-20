# Far Cry 1 CZ – Instalace na 64bit Windows

> **Oficiální návod a průvodce instalací originální CZ verze Far Cry 1 na Windows 10/11 64bit**
> 
> Autoři: **Více admirál Jiřík & Admirál Claude.AI** 🖖

---

## 🎯 O tomto projektu

Originální 32bitový instalátor Far Cry 1 odmítá spustit instalaci na 64bitovém Windows a žádá soubor `setup64.exe` který na CD neexistuje. Po důkladném testování bylo nalezeno řešení pomocí přepínače `/a` který přeskočí systémové kontroly a spustí instalaci v administrativním módu.

Tento repozitář zachraňuje CZ dabing od **Studio Wind 2004** (Tomáš Jirman jako Jack Carver) pro další generaci hráčů!

---

## 🌐 Oficiální zdroje

| Zdroj | Odkaz |
|-------|-------|
| 📖 Návod k instalaci Far Cry 1 na 64bit | [far-cry.cz – Instalace FC1](https://far-cry.cz/instalace-fc1-na-64bit-windows/) |
| 🇨🇿 Kompletní čeština Far Cry 1 na 64bit | [far-cry.cz – Kompletní čeština](https://far-cry.cz/kompletni-cestina-far-cry-1-na-64bit-windows/) |
| 💬 Steam fórum – Oficiální čeština Far Cry 1 | [Steam Community – CZ dabing](https://steamcommunity.com/sharedfiles/filedetails/?l=czech&id=239626578) |

---

## 🚀 Živý návod a soubory

| Zdroj | Odkaz |
|-------|-------|
| 🌍 Interaktivní průvodce instalací (live demo) | [jirka22med.github.io – Far Cry 1 CZ](https://jirka22med.github.io/farcry1-cz-64bit-windows-fix/) |
| 📦 Oficiální soubory ke stažení (Google Drive) | [Stáhnout ZIP balíček](https://drive.google.com/file/d/1YmET4omY9A7q77l5HNF6UEBtR9QDIDMg/view?usp=drive_link) |

---

## 📦 Obsah ZIP balíčku (Google Drive)

Balíček obsahuje vše potřebné pro rozchodení Far Cry 1 CZ na 64bit Windows:

```
📁 OPRAVA HRY FAR CRY 1/
├── 📁 far_cry_v1.4_cumulative/     → Patch 1.4 – Build 1405
├── 📁 farcry_noDVD/                → NoCD spouštěč hry
├── 📁 Localized/                   → CZ dabing (Miroo – Microsoft OneDrive)
├── 📁 msvcp71_and_msvcr71/         → DLL knihovny Visual C++ 2003
├── 📄 farcry-navod.html            → HTML návod z far-cry.cz
└── ⚙️  FC1_CZ_INSTALATOR_64BIT_WIN.bat  → Univerzální spouštěč
```

> ⚠️ **Samotná hra Far Cry 1 není součástí balíčku** – musíš vlastnit originální kopii hry!

---

## ⚡ Rychlý postup instalace

### Klíčový přepínač `/a`
Celé řešení stojí na jediném přepínači:
```cmd
setup32.exe /a
```
Přepínač `/a` spustí instalátor v administrativním módu a přeskočí 32/64bit detekci!

### Cílová složka instalace
```
C:\Program Files (x86)\Ubisoft\Crytek\Far Cry
```
> ⚠️ **Instaluj VŽDY na disk C:** – jinak pravděpodobně nepůjde multiplayer!

### DLL knihovny
```
C:\Windows\SysWOW64\
```
> ⚠️ **SysWOW64 – NE System32!** SysWOW64 je správná složka pro 32bitové knihovny!

### Kritické varování
> ❌ **NIKDY nenastavuj:** Video Options → Lighting Quality → **Very High**
> 
> Hra se nenačte a budeš muset vše přeinstalovat!
> ✅ Maximální bezpečné nastavení je: **High**

---

## 📋 Podrobný návod krok za krokem

Kompletní interaktivní průvodce instalací na 8 stránkách:

👉 **[jirka22med.github.io/farcry1-cz-64bit-windows-fix](https://jirka22med.github.io/farcry1-cz-64bit-windows-fix/)**

---

## 🎙 CZ Dabing – Studio Wind 2004

| Postava | Dabér |
|---------|-------|
| Jack Carver | Tomáš Jirman |
| Richard Crowe | Petr Novák |
| Valerie Constantine | Nikola Birklenová |
| Dr. Krieger | Miroslav Kudela |
| Další | František Strnad, David Vikora |

Zdroj dabingu: **Miroo** – [Steam fórum Far Cry 1](https://steamcommunity.com/sharedfiles/filedetails/?l=czech&id=239626578) · Microsoft OneDrive

---

## 🔧 Testováno na

- ✅ Windows 10 64bit
- ✅ Windows 11 64bit
- ✅ Far Cry 1 v1.40 · Build 1405 · Patch 1.4 Cumulative
- ✅ Originální CZ krabicová verze od Playman

---

## 📚 Zdroje a poděkování

- **[far-cry.cz](https://far-cry.cz)** · autor BackPa – za klíčový návod s přepínačem `/a`
- **Miroo** – za zachování CZ dabingu a sdílení přes Microsoft OneDrive
- **Studio Wind 2004** – za legendární CZ dabing Far Cry 1

---

## 👥 Autoři

**🖖 Více admirál Jiřík & Admirál Claude.AI**

Datum vytvoření: 20.02.2026

---

## 📄 Licence

Tento projekt je licencován pod **CC0-1.0** – volné dílo, používej jak potřebuješ!

> Far Cry je ochranná známka společnosti **Crytek / Ubisoft**. Tento repozitář neobsahuje žádné herní soubory chráněné autorským právem.
