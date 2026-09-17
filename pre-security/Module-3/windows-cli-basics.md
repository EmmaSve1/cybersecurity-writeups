

### Room: [Windows CLI Basics]

**Datum:** [16/9-26] **Spår:** [Datum: [09/16-26] Spår:[Tryhackme/Pre Security]


**Vad rummet handlade om (1-2 meningar i egna ord):**
- Hur man använder Windows Command Prompt/CMD
- Navigera i Windows system utan att klicka sig runt
- Få fram dolda filer
- Lokalisera filer som jag inte visste vart i systemet de fanns

**Nya begrepp – i egna ord:**

- Begrepp:CMD/Command promt Förklaring: Windows textbaserade gränssnitt det vill säga motsvarigheten till terminalen i Linux
- Begrepp: Förklaring:

**Kommandon jag använde:**

| Kommando       | Vad det gör                                                                                                                                                                            |
| -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| whoami         | Visar vem jag är inloggad som                                                                                                                                                          |
| hostname       | Får fram vad namnet på datorn är                                                                                                                                                       |
| systeminfo     | Visar detaljerna om operativ systemet, vilken version av Windows man kör etc                                                                                                           |
| ipconfig       | Visar nätverks konfigurationen, visar hur systemet är uppkopplat till internet                                                                                                         |
| cd             | Visar vart i systemet jag är                                                                                                                                                           |
| dir            | Vad som är runt mig, alltså vilka filer eller mappar                                                                                                                                   |
| dir /a         | Visar även de gömda filerna                                                                                                                                                            |
| cd Documents   | Förflyttar mig till Documents, cd har alltså flera bruk                                                                                                                                |
| cd ..          | För att gå tillbaka en gång bland filerna                                                                                                                                              |
|                |                                                                                                                                                                                        |
| dir /s filnamn | För att hitta vart en fil ligger i disken, /s berättar för windows att söka alla undermappar med start ifrån den katalog jag är nu och samtidigt visa hela sökvägen om filen existerar |
| type filnamn   | För att läsa filen, Windows skriver vad som står i filen i CMD                                                                                                                         |

**Min process (för CTF/labbövningar):** Hitta task_brief.txt någonstans i min user folder

1. Recon – vad jag undersökte först: Vart filen låg, jag körde dir /s task_brief.txt för att få fram katalogen samt sökvägen
2. Vad jag hittade: Vart i systemt filen låg samt sökväg
3. Hur jag löste uppgiften: Körde kommandot, cd sökvägen och efter det dir för att se så filen låg där. Slutligen körde jag type task_brief.txt och hittade där flaggan.

## **Aha-grejer (saker som klarnade):**
Windows och Linux har liknande kommandon fast med olika namn tex dir = ls, type = cat



