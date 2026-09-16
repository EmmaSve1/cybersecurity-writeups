
### Room: [Offensive Security Intro]

**Datum:** [10/9-26] **Spår:** [Pre Security]

**Vad rummet handlade om (1-2 meningar i egna ord):**
Introduktion till offensive security genom att praktiskt hitta och utnyttja en dold sida på en fejk-bank.

**Nya begrepp – i egna ord:**

- Begrepp: Dirbuster/dirb
   Förklaring: Kommando man kör med en URL för att hitta glömda gömda sidor
- Begrepp: Offensive Security och Defensive Security Förklaring: Offensive och defensive security, skillanden mellan dem.
Offensive är att hitta sårbarheter innan de uttnytjas och defensive är att skydda och laga system.

**Kommandon jag använde:**

| Kommando | Vad det gör        |
| -------- | ------------------ |
| dirb     | hittar gömda sidor |
|          |                    |

**Min process (för CTF/labbövningar):**

1. Recon – vad jag undersökte först: Startade maskinen i hemsidan, en fejk bank i webbläsaren för att se vad som finns
2. Vad jag hittade: Körde Dirbuster för att leta efter dolda sidor, hittade en dold sida som heter /bank-transfer
3. Hur jag löste uppgiften: Gick till den dolda sidan och överförde pengar mellan konton.

## **Aha-grejer (saker som klarnade):**

Kod för att söka efter dolda sidor, att man kan hitta dolda sidor som körs på en URL med hjälp av 
dirb.

## **Frågor jag svarade fel på i quiz + rätt svar:**
Inga fel denna gång

---

## Termer jag inte helt förstår än

