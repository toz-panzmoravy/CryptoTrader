# Návod k Indikátoru: Crypto Futures Master (CryptoEXP)

## I. Základní Filozofie

Tento indikátor není kouzelná křišťálová koule. Je to **palubní deska profesionálního pilota**. Jejím úkolem není dát vám jeden slepý signál "BUY" nebo "SELL", ale poskytnout vám kompletní "checklist" všech kritických faktorů.

**Před každým obchodem projdete očima tabulku odshora dolů. Pokud si jednotlivé metriky protiřečí, nebo pokud něčemu nerozumíte, je to samo o sobě signál: "ZŮSTAŇ MIMO".**

## II. Hlavní Dashboard - Popis jednotlivých řádků

Každý řádek v tabulce je jeden dílek skládačky.

---

### **1. Hlavní Signál & Kvalita**
- **Stav (`IN LONG`, `IN SHORT`, `HUNTING`, `STAY OUT`):** Ukazuje, v jaké fázi je interní logika indikátoru. `HUNTING` znamená, že byl detekován kvalitní setup a systém čeká na potvrzovací svíčku pro vstup.
- **Quality (0-100):** Celkové skóre setupu.
    - **70+:** A-Grade setup. Vysoká pravděpodobnost.
    - **50-70:** B-Grade setup. Obchodovatelný, ale buďte opatrnější, zvažte menší pozici.
    - **<50:** Nízká kvalita. I kdyby přišel signál, je lepší ho ignorovat.

---

### **2. Market Drivers (Hybatelé Trhu)**
- **Momentum (`BULLISH` / `BEARISH` / `NEUTRAL`):** Ukazuje, zda se na trendu shodují vyšší časové rámce. `BULLISH` nebo `BEARISH` je silné potvrzení. `NEUTRAL` znamená, že trh je nerozhodný.
- **Volatility (`LOW` / `NORMAL` / `HIGH` / `EXTREME`):**
    - `LOW`: Trh "spí". Může se chystat prudký pohyb.
    - `NORMAL`: Ideální podmínky pro obchodování.
    - `HIGH`: Zvýšená opatrnost.
    - `EXTREME`: Velmi nebezpečné. Cena může létat oběma směry. Zvažte snížení pozice nebo neobchodujte.
- **Funding (`Longs Pay Shorts` / `Shorts Pay Longs`):** Klíčové pro futures! Ukazuje, kdo platí komu.
    - `Longs Pay Shorts` (kladné číslo): Většina je v longu. Trh je "těžký" a má tendenci klesat. Dobré pro shorty.
    - `Shorts Pay Longs` (záporné číslo): Většina je v shortu. Shortaři jsou "potrava" pro růst. Dobré pro longy.
- **Altcoin Status (`ALTCOIN SEASON` / `BTC DOMINANCE`):**
    - `ALTCOIN SEASON`: Energie je v altcoinech. Ideální čas hledat na nich long pozice.
    - `BTC DOMINANCE`: Energie je v Bitcoinu. Altcoiny pravděpodobně krvácí. Buďte extrémně opatrní s longy na altech, je to dobré prostředí pro shorty.
- **Pump & Dump (`DETECTED` / `CLEAR`):**
    - `DETECTED`: Okamžitě ruce pryč! Někdo manipuluje s cenou. Neobchodovat.
    - `CLEAR`: Normální tržní aktivita.
- **Liq. Clusters (`CLEAR` / `1 ZONE` / `2+ ZONES`):** Ukazuje, kolik shluků likvidací je blízko aktuální ceny.
    - `CLEAR`: Bezpečno.
    - `1 ZONE`: Pozor, cena může být přitahována k této zóně.
    - `2+ ZONES`: Velmi nebezpečné. Funguje jako silný magnet na cenu. Očekávejte volatilitu.
- **Signal Type:** Dává kontext k celému setupu. Např. `MOMENTUM BREAKOUT` je jiný typ příležitosti než `FUNDING ARBITRAGE`. Pomáhá vám pochopit, *proč* se signál objevil.

---

### **3. Analýza Trendu**
- **Micro-Trend (`UP` / `DOWN`):** Směr SuperTrendu. Váš nejbližší přítel pro určení krátkodobého směru. V silném trendu cena respektuje tuto linku.
- **SMC Zones (`▲ Support` / `▼ Resistance`):** Nejdůležitější zóny pro plánování obchodu.
    - **Využití:** Plánujte vstupy, když cena reaguje na těchto úrovních. Stop loss umístěte *za* tuto zónu. Take profit cílujte k *další* SMC zóně.
- **Okamžitý Tlak (`▲ Nad EMA` / `▼ Pod EMA`):** Ukazuje, kdo má převahu v posledních několika svíčkách. Skvělé pro potvrzení vstupu.
- **Síla Trendu (0-100):** Jak zdravý a spolehlivý je hlavní trend?
    - **75+:** Silný, zdravý trend. Můžete mu věřit.
    - **50-75:** Průměrný trend.
    - **<50:** Slabý, "choppy" trh. Trendu se nedá věřit. Neobchodujte trendy, spíše se zaměřte na zvraty.
- **Potenciál Trendu (0-100):** "Palivová nádrž" trendu.
    - **Jak číst:** Ukazuje, kolik prostoru má trend, než narazí na další překážku (SMC zónu).
    - **Využití:** Pokud vstupujete do obchodu a potenciál je jen 20/100, neočekávejte dlouhý pohyb. Pokud je 80/100, máte před sebou volnou cestu. Skvělé pro řízení výstupů!

---

## III. Pullback Hunter Systém (Spodní Panel)

Toto je vaše tajná zbraň pro chytré vstupy.

- **Main Trend (`UPTREND (12 bars)`):** Říká "Hlavní trend je UP a běží už 12 svíček."
- **Pullback Status (`NONE` / `HUNTING` / `READY`):**
    - `NONE`: Trend ještě není dostatečně potvrzený (trvá méně než 10 svíček).
    - `HUNTING`: Trend běží, systém aktivně čeká, až cena začne korigovat.
    - `READY`: **Klíčový stav!** Korekce je dostatečně hluboká. Nyní je čas přiblížit graf a hledat konkrétní vstupní signál (např. svíčkovou formaci `E` nebo `H`).
- **Pullback Depth (0-100):** Jak kvalitní je korekce. 70+ je ideální.

---

## IV. Příklady z Praxe (Jak myslet)

### **Scénář 1: "A-Grade" SHORT na XRP**
1.  **Dashboard ukazuje:** `Altcoin Status: BTC DOMINANCE`, `Síla Trendu: 88/100`, `Micro-Trend: DOWN`.
2.  **Vaše myšlenka:** "Perfektní! Prostředí přeje shortům na altech, trend je silný."
3.  **Akce:** Díváte se na `Pullback Status`. Je `HUNTING`. Čekáte.
4.  Po pár svíčkách se cena zvedá proti trendu. `Pullback Status` se mění na `READY` a `Pullback Depth` ukazuje 75/100.
5.  **Vaše myšlenka:** "Super, korekce je ideální."
6.  **Akce:** Přiblížíte graf. Cena se dotýká SMC zóny `▼ Resistance`. Objeví se červený symbol `E` (medvědí pohlcení). `Potenciál Trendu` ukazuje 90/100.
7.  **Závěr:** Vstupujete do SHORT pozice. Stop loss dáváte těsně nad SMC zónu.

### **Scénář 2: Zmatená situace - "No-Go" Zóna**
1.  **Dashboard ukazuje:** `Momentum: BULLISH`, ale `Okamžitý Tlak: ▼ Pod EMA`. `Síla Trendu` je jen 35/100. `Liq. Clusters` ukazuje `3 ZONES`.
2.  **Vaše myšlenka:** "Tohle je chaos. Vyšší rámce chtějí nahoru, ale krátkodobě to padá. Trend nemá sílu a hrozí likvidační 'lov'."
3.  **Závěr:** Ruce pryč. Čekáte, až se situace vyčistí.

### **Scénář 3: Řízení obchodu pomocí Potenciálu**
1.  **Situace:** Jste v ziskovém longu. Vstupovali jste, když `Potenciál Trendu` byl 85/100.
2.  **Akce:** Sledujete, jak s každou svíčkou `Potenciál Trendu` klesá... 70... 55... 40...
3.  **Vaše myšlenka:** "Blížíme se k nějaké rezistenci, trendu dochází dech."
4.  **Závěr:** Jakmile potenciál klesne pod 30, začnete uvažovat o uzavření obchodu nebo alespoň o posunutí stop lossu na vstupní cenu, abyste ochránili zisky.
