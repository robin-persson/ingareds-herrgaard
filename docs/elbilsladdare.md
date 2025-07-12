# Innehåll

På denna sida sammanfattas hur våra elbilsladdare nyttjas och fungerar.

[TOC]

# Hur får jag tillgång att ladda?

Om du önskar ladda på samfällighetens stolpar behöver du göra följande:

1. **Skaffa parkeringstillstånd**. Se sidan [Parkeringstillstånd](./parkering.md#parkeringstillstand)
2. **Få tillgång till laddning**. Laddstolparna tillhandahålls av [Mer](https://se.mer.eco/). Skaffa ett konto, antingen via webben eller appen, och be [kundtjänst](https://se.mer.eco/mer/kontakta-oss/) att registrera dig på samfällighetens stolpar.

# Våra laddare

Samfälligheten har i skrivande stund 3 laddstolpar med två uttag i varje. Två vita Alfen-laddare samt en blå, LS4.

## Vita stolparna (Alfen Eve Double Pro-Line)

![Alfen Eve Double Pro-Line](./img/alfen-eve-double-pro-line.png){ align=left width=100 }

De två vita laddarna (ID: 22052 och 22053), av märket Alfen Eve Double Pro-line, delar på en 32 A-säkring (22 kW, 3-fas, 400 V). Dvs fyra uttag delar på tre faser om 32A. Lastbalanserare fördelar strömmen automatiskt mellan laddarna.

Varje enskilt uttag kan leverera en effekt upp till 11 kW.

> ℹ️ Om alla uttag används kommer hastigheten behöva begränsas. Se [exempel](#exempel-effektfordelning-nar-flera-laddar-samtidigt) nedan.

> ℹ️ 1-fasbilar (som t.ex. laddhybrider) laddar på endast en fas och kan därför bara använda ca ⅓ av den totala effekten.

## Blå stolpen (Garo LS4)

![Garo LS4](./img/garo-ls4.jpg){ align=left width=100}

Den blå LS4-laddaren är en 1-fasladdare avsäkrad med 32 A.

> ℹ️ Eftersom endast en fas nyttjas gäller samma kapacitet oavsett bil: Max 3,7 kW (230 V × 16 A) oavsett om bilen har 1- eller 3-fasladdare.

# Allmänt om elbilar

- De flesta elbilar har en ombordladdare som klarar max 16 A per fas (max 11 kW).
- Bilen själv begränsar laddningen beroende på batteriets status, temperatur, laddnivå m.m.
- Vissa bilar har ombordladdare som laddar på tre faser, vissa endast på en fas. Se [exempel](#exempel-effektfordelning-nar-flera-laddar-samtidigt) nedan för att förstå vad det innebär för effekten vid laddning.

# Exempel: Effektfördelning när flera laddar samtidigt

**Exempel 1 – Två 3-fasbilar**
- Strömmen delas lika: 32 A / 2 = 16 A per laddare
- Effekt per bil: √3 × 400 V × 16 A ≈ 11 kW
- Båda bilarna laddar med ca 11 kW var

**Exempel 2 – En 3-fasbil + en 1-fasbil**
- Strömmen delas lika: 32 A / 2 = 16 A per laddare
- 1-fasbilen: 230 V × 16 A = 3,7 kW
- 3-fasbilen: √3 × 400 V × 16 A ≈ 11 kW

**Exempel 3 - flera bilar på de två vita laddarna**

Laddare 22052:
| Uttag | Starttid | Erbjuden effekt | Verklig effekt | Typ av bil | Kommentar |
|-------|----------|-----------------|---------------|------------|-----------|
| 1     | 13:00    | 11 kW           | 3,6 kW        | 1-fas bil  | Färdigladdad när uttag 2 kopplades in |
| 2     | 19:00    | 11 kW           | 3,6 kW        | 1-fas bil  | Båda uttag fick 16 A vid samtidig laddning |

Laddare 22053:
| Uttag | Starttid | Erbjuden effekt | Verklig effekt | Typ av bil | Kommentar |
|-------|----------|-----------------|---------------|------------|-----------|
| 1     | 16:35    | 5,5 kW          | 5,4 kW        | 3-fas bil  | Delad last med 22052 – totalt 16 A till 22053, dvs 8A per uttag |
| 2     | 16:57    | 5,5 kW          | 1,8 kW        | 1-fas bil  | Lägre effekt på 1-fasbil | 

# Felsökning

För att underlätta framtida felsökning och åtgärd följer nedan några fel som tidigare uppstått och avhjälpts.

## En av de vita laddarna ger alltid lägre än den andra 

Det har hänt att en vit laddare inte kunnat erbjuda full kapacitet. Till exempel har en 1-fasbil inte kommit upp i mer än 1,3 kW (6A) på en av de vita Alfen-laddarna, trots att det varit den enda inkopplade bilen (vilket borde gett en effekt på 7kW, eller 32A).

Enligt Mer kan detta hända om laddaren tappar uppkopplingen till lastbalanseraren. När så sker går laddaren in i ett säkerhetsläge och erbjuder max 6A. 6A på en fas blir ca 1,3 kW. På tre faser blir detta ca 4,2 kW.

> ✅ Supporten på Mer kan avhjälpa detta på distans. Hör av er till support, se [kontaktuppgifter](https://se.mer.eco/mer/kontakta-oss/), uppge namnet på samfälligheten och be dem ta en titt så fixar de det lätt.