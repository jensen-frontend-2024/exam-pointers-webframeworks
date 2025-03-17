# Exam-pointers - Web Frameworks in JavaScript

Följande är en lista på saker som kan komma att dyka upp på den skriftliga examinationen. Dock ska ni inte betrakta denna lista som tillräcklig för att klara tentan. Även fast man förstår de individuella delarna var för sig så måste man ändå kunna använda koncepten tillsammans i ordentliga exempel för klara av tentan i sin helhet.

Tentan kommer att vara uppdelad i tre delar.

1. Konceptuella Frågor
2. Kodanalys och tekniska frågor
3. Design och lösningsförslag

## Moment som kommer att examineras

### Konceptuella Frågor

- Statehantering med useState
- Props
- Konsten att köra kod under olika skeden i en komponents livscykel med useEffect
- React Router inklusive de mest andvändbara hooks
- Context API
- Kontrollerad komponent VS okontrollerad komponent
- useRef

### Kodanalys och tekniska frågor

I denna sektion så kommer ni få titta på enklare kodsnuttar och svara på tillhörande frågor. Ett exempel kan vara: "vad gör detta stycke kod, förklara med egna ord."

### Design och lösningsförslag

Denna sektion fokuserar på att ni ska skriva kod utifrån en kravbeskrivning. Följande är ett exemepl på hur en sådan fråga kan se ut:

```
Du ska skapa en statuslös React-komponent som visar en lista av meddelanden med följande krav:

- Varje meddelande ska visa en text och en tidsstämpel. 
- Om ett meddelande är markerat som "viktigt" ska detta visas. 
- Om listan av meddelanden är tom eller undefined, ska en fallback-text visas: "Inga meddelanden att visa."

1. Vilka props ska komponenten ta emot?
2. Skriv kod för komponentens grundläggande struktur.
```
