# Naplň flašku – PLC hra

Výuková hra o programování PLC v žebříčkovém diagramu (LAD) ve stylu Siemens S7-1200 / TIA Portal.

Hráč skládá program pro výrobní linku a simulace hned ukáže, jestli linka funguje. Před každým úkolem je teorie s interaktivními ukázkami.

## Úrovně

1. **Plnění lahví** – spínací a rozpínací kontakt, cívka, časovač TON, Set/Reset, blokování
2. **Ovládací panel** – START/STOP se samodržením, STOP jako rozpínací kontakt, TONR a RT, nouzové zastavení
3. **Váha a počítání** – analogový vstup, porovnávací kontakt CMP, čítač CTU, kvitování
4. **Víčkovačka** – pneumatický válec, koncové spínače, dvě stanice na jednom pásu, pomocné bity
5. **Poruchy a alarmy** – hlídací časovač, taktovací paměť (blikání), kvitování poruchy
6. **Kontrola kvality** – kamera, vyhazovač s impulzním časovačem TP, druhý čítač zmetků
7. **Ruční a automat** – přepínač režimů, ruční posuv, kontakty hrany -|P|- a -|N|-
8. **Balení do krabic** – nová hala shora, balička a handshake se strojem, kamerová kontrola krabic
9. **Robot a paletizace** – robot s dorazem a startem na hranu, paleta, kamera nad paletou, konec zakázky čítačem
10. **Třídění výhybkou** – výhybka a sklad zmetků, sledování kusu paměťovým bitem, hlídání plného skladu
11. **Zarážka a odstup** – pneumatická zarážka, fronta kusů, pouštění v taktu (taktovací bit + TP)

## Moje hala

Volná hra, která se otevře po úrovni 1. Hráč si na mřížce postaví vlastní výrobní halu:
vybere výrobek (džus, sušenky, med, voda, ozubená kola, jogurt, plechovky, čokoládové tyčinky) a zakázku,
poskládá linku z komponent (dopravník stačí táhnout myší nebo prstem) a napíše pro ni program. Každá komponenta dostane adresy %I/%Q sama.
Hala má mřížku 16 × 9 políček. Nové komponenty (pec, víčkovačka, kamera, výhybka, zarážka, chladicí tunel, balička, robot, paleta…) se odemykají splněním úrovní.

## Spuštění

Celá hra je jeden soubor `index.html`. Stačí ho otevřít v prohlížeči, nic se neinstaluje.

## Licence

Copyright © 2026 Eliška Sosnová. Všechna práva vyhrazena.

Hru můžeš hrát a používat ke studiu i ve výuce na adrese https://ellsyout.github.io/plc-hra/.
Bez předchozího písemného souhlasu autorky ji nelze dále šířit, kopírovat, upravovat ani komerčně využívat.

Hra je pouze učební pomůcka. Simulace i texty jsou zjednodušené a některé informace nemusí být úplně přesné nebo pravdivé.
Celé znění je v souboru [LICENSE](LICENSE).
