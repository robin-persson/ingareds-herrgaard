# Elbilsladdare

Här sammanfattas hur våra elbilsladdare fungerar i olika scenarion och med olika typer av laddbara bilar.

## Våra laddare

- De två vita Alfen-laddarna (ID: 22052 och 22053) delar på en 32 A-säkring (22 kW, 3-fas, 400 V). Dvs fyra uttag delar på tre faser om 32A.
- Den blå Ls-4-laddaren är en enfasladdare avsäkrad med 32 A.
  - Laddaren begränsar effekten: Max 3,7 kW (230 V × 16 A) oavsett bilens kapacitet, vilket gäller både 1- och 3-fasbilar.
- Lastbalansering är aktiv: Om fler än en bil laddas samtidigt, fördelas strömmen automatiskt mellan laddarna.
- 1-fasbilar (som t.ex. laddhybrider) laddar på endast en fas och kan därför bara använda ca ⅓ av den totala effekten.

## Allmänt om elbilar

- De flesta elbilar har en ombordladdare som klarar max 16 A per fas (max 11 kW).
- Bilen själv begränsar laddningen beroende på batteriets status, temperatur, laddnivå m.m.

### Exempel 1 – Två elbilar (3-fas)
- Strömmen delas lika: 32 A / 2 = 16 A per laddare
- Effekt per bil: √3 × 400 V × 16 A ≈ 11 kW
- Båda bilarna laddar med ca 11 kW var

### Exempel 2 – En elbil (3-fas) + en hybrid (1-fas)
- Båda laddare får 16 A
- Hybriden (1-fas): 230 V × 16 A = 3,7 kW
- Elbilen (3-fas): √3 × 400 V × 16 A ≈ 11 kW
- Hybriden kan bara nyttja en fas och får därför lägre effekt.

## Exempel på lastfördelning

**Laddare 22052**

| Uttag | Starttid | Erbjuden effekt | Verklig effekt | Typ av bil | Kommentar |
|-------|----------|-----------------|---------------|------------|-----------|
| 1     | 13:00    | 11 kW           | 3,6 kW        | 1-fas bil  | Färdigladdad när uttag 2 kopplades in |
| 2     | 19:00    | 11 kW           | 3,6 kW        | 1-fas bil  | Båda uttag fick 16 A vid samtidig laddning |

**Laddare 22053**

| Uttag | Starttid | Erbjuden effekt | Verklig effekt | Typ av bil | Kommentar |
|-------|----------|-----------------|---------------|------------|-----------|
| 1     | 16:35    | 5,5 kW          | 5,4 kW        | 3-fas bil  | Delad last med 22052 – totalt 16 A fördelat på 22053 |
| 2     | 16:57    | 5,5 kW          | 1,8 kW        | 1-fas bil  | Lägre effekt på 1-fasbil | 