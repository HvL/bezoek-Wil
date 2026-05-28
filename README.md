# bezoek-Wil
WebApp voor bezoeken plannen en maken van gastenboek
GitHub Pages                 Supabase
─────────────────            ──────────────────────
index.html          ←──────→ PostgreSQL database
gastenboek.html     (API)    - activities
handleiding.html             - bookings
                             - gastenboek
                             - visitors
                             - settings
                             - weekly_activities
                             - visit_windows
                    
                    ←──────→ Storage bucket
                             - gastenboek/
                               (video & audio bestanden)

                               
# Bezoek Wil van der Burg

Een familieplanningsapp waarmee familie en vrienden eenvoudig een bezoek kunnen inplannen bij Wil van der Burg, haar dagprogramma kunnen bekijken en een persoonlijk video- of spraakbericht kunnen achterlaten in het gastenboek.

🌐 **Live:** [WilvdBurg.vanleeuwen-family.nl](https://WilvdBurg.vanleeuwen-family.nl)

---

## Functies

- **Bezoek inplannen** — kies zelf een begin- en eindtijd binnen het bezoekvenster, pas je boeking aan of annuleer hem
- **Agenda** — weekoverzicht van activiteiten en bezoekers met visuele tijdsbalk
- **Vandaag** — dagweergave voor Wil op de iPad met alle bezoekers en activiteiten van de dag
- **Gastenboek** — laat een video- of spraakbericht achter voor Wil (PIN-beveiligd)
- **Secretaresse** — afspraken beheren namens anderen, gedeelde gastenboek-link genereren
- **Beheer** — activiteiten toevoegen, bezoekvensters instellen, vaste weekactiviteiten, PIN-beheer

## Techniek

| Onderdeel | Technologie |
|-----------|-------------|
| Frontend | Vanilla HTML/CSS/JavaScript |
| Hosting | GitHub Pages |
| Database | Supabase (PostgreSQL) |
| Bestandsopslag | Supabase Storage (video/audio) |
| Realtime updates | Supabase Realtime websockets |
| Iconen | Tabler Icons |

## Bestanden

| Bestand | Beschrijving |
|---------|--------------|
| `index.html` | Hoofdapp |
| `gastenboek.html` | Gedeelde gastenboek-pagina (aparte URL) |
| `handleiding-bezoek-wil.html` | Handleiding voor bezoekers |

## Toegang

| Rol | Toegang |
|-----|---------|
| Bezoeker | Naam invullen, bezoek inplannen, agenda bekijken |
| Wil | Gastenboek bekijken via eigen PIN |
| Secretaresse | Afspraken beheren via eigen PIN |
| Beheerder | Volledige toegang via naam + PIN |

---

*Gebouwd met ❤️ voor de familie Van Leeuwen*
