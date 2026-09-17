

### Room: [Linux CLi Basics]

**Datum:** [09/16-26] **Spår:** [Pre Security]

**Vad rummet handlade om:**
Hur man navigerar i Linux terminal och filsystem, läser dokument och andra filer

**Nya begrepp – i egna ord:**

- Begrepp: Termnial Förklaring: Är en CLI alltså en text baserad interface/gränssnitt.
- Begrepp: /dev/root Förklaring: Är huvuddisken på systemet.
- Begrepp: tmpfs Förklaring: Är temporära filsystem lagrade i RAM och inte i den fysiska disken
- Begrepp: /dev/shm Förklaring: Är delat minnesutrymme
- Begrepp: /run/user/114 Förklaring: Är liknande temporär lagring för en annan system användare

**Kommandon jag använde:**

| Kommando | Vad det gör                                                                                                               |
| -------- | ------------------------------------------------------------------------------------------------------------------------- |
| pwd      | Det visar vart i systemet jag är                                                                                          |
| ls       | Vilka filer och mappar som finns där jag är                                                                               |
| ls -l    | Ger mer detaljer om filerna och mapparna där jag nu är                                                                    |
| ls -al   | Visar alla gömda filer                                                                                                    |
| cd       | För att flytta runt i systemet                                                                                            |
| cd ..    | För att gå tillbaka ett steg                                                                                              |
| find ~   | för att hitta var en specifik fil eller dokument ligger                                                                   |
| cat      | För att läsa en fil                                                                                                       |
| whoami   | För att kolla vem jag är inloggad som                                                                                     |
| uname -a | För att se vilket system jag är på och dess detaljer                                                                      |
| uname    | För att enbart se OS namnet tex Linux                                                                                     |
| df -h    | För att kollar disk användning samt tillgängligt utrymme, -h betyder mänskligt läsbart och visar med enkelhet tex 5GB osv |
|          |                                                                                                                           |

**Min process (för CTF/labbövningar):**
Hitta filen day1_report.txt

1. Recon – vad jag undersökte först: Jag körde kommandot find ~ -name day1_report.txt för att hitta vart i systemet filen finns. 
2. Vad jag hittade: Jag hittade vart filen låg.
3. Hur jag löste uppgiften: Jag körde cd <hela sökvägen> sedan ls för att se så att filen låg där och efter det körde jag cat day1_report.txt och hittade flaggan.

## **Aha-grejer (saker som klarnade):**

När det är en punkt framför en fil så är det en gömd fil/mapp
Linux förvarar konfiguration och informativa filer i /etc katalogen.

## **Frågor jag svarade fel på i quiz + rätt svar:**
Inga fel denna gång, men hade lite problem till en början att förstå hur jag skulle skriva in sökvägar osv men det löste sig.

---

## Termer jag inte helt förstår än

