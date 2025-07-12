# Innehåll

På denna sida sammanfattas hur våra elbilsladdare fungerar.

[TOC]

# Registrering

Om du  önskar ladda på samfällighetens stolpar behöver du göra följande:

1. **Skaffa parkeringstillstånd**. Se [sidan Parkeringstillstånd](./parkering.md#parkeringstillstånd)
2. **Få tillgång till laddning** på samfällighetens stolpar. Stolparna tillhandahålls av [Mer](https://se.mer.eco/). Skaffa ett konto, antingen via webben eller appen, och be kundtjänst att registrera dig på samfällighetens stolpar. Se deras [kontaktuppgifter](https://se.mer.eco/mer/kontakta-oss/).

# Våra laddare

Samfälligheten har i skrivande stund 3 laddstolpar med två uttag i varje. Två vita Alfen-laddare samt en blå, LS4.

## Vita stolparna (Alfen Eve Double Pro-Line)

![Alfen Eve Double Pro-Line](./img/alfen-eve-double-pro-line.png)

De två vita laddarna (ID: 22052 och 22053), av märket Alfen Eve Double Pro-line, delar på en 32 A-säkring (22 kW, 3-fas, 400 V). Dvs fyra uttag delar på tre faser om 32A. Lastbalanserare fördelar strömmen automatiskt mellan laddarna.

Varje enskilt uttag kan leverera en effekt upp till 11 kW.

> ℹ️ Om alla uttag används kommer hastigheten behöva begränsas. Se [exempel](#exempel) nedan.

> ℹ️ 1-fasbilar (som t.ex. laddhybrider) laddar på endast en fas och kan därför bara använda ca ⅓ av den totala effekten.

## Blå stolpen (Garo LS4)

![Garo LS4](./img/garo-ls4.jpg)

Den blå LS4-laddaren är en 1-fasladdare avsäkrad med 32 A.

> ℹ️ Eftersom endast en fas nyttjas gäller samma kapacitet oavsett bil: Max 3,7 kW (230 V × 16 A) oavsett om bilen har 1- eller 3-fasladdare.

# Allmänt om elbilar

- De flesta elbilar har en ombordladdare som klarar max 16 A per fas (max 11 kW).
- Bilen själv begränsar laddningen beroende på batteriets status, temperatur, laddnivå m.m.

## Exempel

> **Exempel 1 – Två elbilar (3-fas)**
> - Strömmen delas lika: 32 A / 2 = 16 A per laddare
> - Effekt per bil: √3 × 400 V × 16 A ≈ 11 kW
> - Båda bilarna laddar med ca 11 kW var

> **Exempel 2 – En elbil (3-fas) + en hybrid (1-fas)**
> - Båda laddare får 16 A
> - Hybriden (1-fas): 230 V × 16 A = 3,7 kW
> - Elbilen (3-fas): √3 × 400 V × 16 A ≈ 11 kW
> - Hybriden kan bara nyttja en fas och får därför lägre effekt.

> **Exempel på lastfördelning**
> 
> Laddare 22052:
> | Uttag | Starttid | Erbjuden effekt | Verklig effekt | Typ av bil | Kommentar |
> |-------|----------|-----------------|---------------|------------|-----------|
> | 1     | 13:00    | 11 kW           | 3,6 kW        | 1-fas bil  | Färdigladdad när uttag 2 kopplades in |
> | 2     | 19:00    | 11 kW           | 3,6 kW        | 1-fas bil  | Båda uttag fick 16 A vid samtidig laddning |
> 
> Laddare 22053:
> | Uttag | Starttid | Erbjuden effekt | Verklig effekt | Typ av bil | Kommentar |
> |-------|----------|-----------------|---------------|------------|-----------|
> | 1     | 16:35    | 5,5 kW          | 5,4 kW        | 3-fas bil  | Delad last med 22052 – totalt 16 A fördelat på 22053 |
> | 2     | 16:57    | 5,5 kW          | 1,8 kW        | 1-fas bil  | Lägre effekt på 1-fasbil | 

# Felsökning

Vi har stött på vissa typer av fel som avhjälpts. Mer information nedan.

## Begränsad kapacitet

Det har hänt att en laddare inte kunnat erbjuda avsäkrad kapacitet. Till exempel har en 1-fasbil inte kommit upp i mer än 1,3 kW (6A) på en av de vita Alfen-laddarna, trots att det varit den enda inkopplade bilen (vilket borde gett kapacitet på 7kW, eller 32A).

Detta kan hända om laddaren tappar uppkopplingen till lastbalanseraren. När så sker går laddaren in i ett säkerhetsläge och erbjuder max 6A. 6A på en fas blir ca 1,3 kW. På tre faser blir detta ca 4,2 kW.

> ✅ Supporten på Mer kan avhjälpa detta på distans. Hör av er till support, se [kontaktuppgifter](https://se.mer.eco/mer/kontakta-oss/), uppge namnet på samfälligheten och be dem ta en titt så fixar de det lätt.