

### Room: [# Virtualisation Basics]

**Datum:** [09/10-26] **Spår:** [Pre Security

**Vad rummet handlade om:**

Hur ett enda fysiskt servrar kan delas upp i flera oberoende, isolerade "datorer" genom virtualisering –och varför det behövs (annars skulle varje app/hemsida kräva sin egen fysiska server, vilket vore orimligt dyrt och slösaktigt).

**Nya begrepp – i egna ord:**

- Begrepp: Hypervisor Förklaring: Mjukvaran som delar upp en fysisk maskin i flera virtuella maskiner och fördelar CPU/Ram samt lagring mellan dem samtidigt som den håller de isolerade ifrån varandra
- Begrepp: VM/Virtuell Maskin Förklaring: En simulerad dator som körs i den fysiska maskinen via hypervisorn med egna resurser.
- Begrepp: Container Förklaring: Ett lättare alternativ till VM, delar samma operativ system men isolerar applicationen, den är snabbare att starta än en VM
- Begrepp: Type 1 vs Type 2 hypervisor Förklaring: Type 1 körs direkt på hårdvaran tex i ett datacenter, Type 2 körs ovanpå en vanligt operativ system tex Virtual Box på din dator.



**Min process (för CTF/labbövningar):**

1. Recon – vad jag undersökte först: Utforskade en Virtualization Manager webbapp för att titta på befintliga VMs och serverkapacitet.
2. Vad jag hittade: En VM som låg nere samt hur mycket resurser hosten använde och hade tillgängligt.
3. Hur jag löste uppgiften: Jag startade om den VM som låg nere.

## **Aha-grejer (saker som klarnade):**

Fysisk server = byggnad, VM= lägenhet, Container= rum i lägenhet.
 Fattade att ett eget hemmalabb/VM som VirtualBox är en Type 2


