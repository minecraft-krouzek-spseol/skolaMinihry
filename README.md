# VOŠ a SPŠEOL v Minecraftu!

Tento repozitář obsahuje Python skripty pro výukovou mapu školy VOŠ a SPŠEOL v Minecraft: Education Edition. Projekt je zaměřen na výuku základů algoritmizace (cykly, podmínky, práce s Agentem) prostřednictvím interaktivních miniher.

## Obsah projektu

Repozitář obsahuje kódy pro dvě hlavní úlohy:

### 1. Oprava školní chodby (`chodba.py`)
* **Cíl:** Vyplnit propadlou podlahu (5x7 bloků) pomocí Agenta.
* **Koncepty:** Vnořené cykly (`for` loop), absolutní souřadnice, pokládání bloků.
* **Kontrola:** Skript automaticky ověřuje zaplnění celé plochy a kontroluje, zda Agent nepolepil bloky mimo určenou oblast.

### 2. Úklid tělocvičny (`telocvicna.py`)
* **Cíl:** Odstranit "míče" (červenou vlnu) rozházené na ploše, na které hráč nesmí sahat rukou.
* **Koncepty:** Detekce bloků, ničení objektů (`agent.destroy`), validace stavu prostředí.
* **Kontrola:** Skript po spuštění příkazu `/hotovo` provede inspekci konkrétních souřadnic a ověří, zda byl veškerý nepořádek odstraněn.

## Jak projekt použít

1. Spusťte **Minecraft: Education Edition**.
2. Otevřete Code Builder (klávesa **C**).
3. Vyberte jazyk **Python** nebo jednoduše využijete možnost **Blocks**
4. Stáhněte si ukoly a mapu z releases a přidejte si je podle video tutoriálu do Minecraftu.
5. Ve hře si můžete projít školu a splnit úkoly od NPCs.

https://www.spseol.cz
