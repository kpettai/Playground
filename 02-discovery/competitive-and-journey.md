# Competitive Analysis & Journey Map (Module 2)

## Responses
- **Role, who are you solving for? (the specific user segment or profile):** Persona 1: Lena, 32, Cologne

Role: A salaried, mobile-first shopper on a middling income who uses BNPL on most non-trivial purchases and takes whichever provider appears at checkout.
- **Goal, what is this user ultimately trying to achieve?:** Persona 1: Lena, 32, Cologne

Goal: To keep money in her account until she has decided to keep the item, without having to think about which provider to use.
- **Friction, the main barrier (moment of misery) stopping them from succeeding:** Persona 1: Lena, 32, Cologne

Her whole habit depends on "decide first, pay later," but the card treats every purchase as pay-now (BUG-2060). The one behaviour she values disappears, and she has no reason to prefer it over the Klarna or PayPal she already carries. As Anja (UXR-06) puts it, if the card charges immediately, she doesn't see the point.
- **External tools, the outside platforms or tools the user is forced to use:** She sees which BNPL options the merchant offers and takes whichever appears, usually Klarna or PayPal. [Evidenced: case brief]
- **The process, the 3 to 5 manual steps the user takes to get the job done:** She shops on her phone and reaches checkout. [Evidenced]
She sees which BNPL options the merchant offers and takes whichever appears, usually Klarna or PayPal. [Evidenced: case brief]
She selects pay-later, so money stays in her account until she decides to keep the item. [Evidenced]
She keeps or returns the item within the return window. If she returns it, she never paid. [Evidenced: UXR-06]
She tracks due dates for whatever she kept across separate provider apps. [Inferred, based on UXR-04]
The Riverty card stays unused, because it charges immediately and gives her nothing she doesn't already have. [Evidenced: BUG-2060, UXR-06]
- **Core frustration, the exact moment the process feels most “broken”:** She doesn't choose a provider. The merchant's checkout does, so her spending is scattered by chance.
Her obligations sit in multiple apps with separate due dates, which is the pain that made Tobias (UXR-04) quit BNPL.
The card was meant to be a single place for her pay-later habit, but it can't do the one thing she values, so she keeps using several tools.
- **The evidence, a specific quote or behavior from the research that proves this:** Her obligations sit in multiple apps with separate due dates, which is the pain that made Tobias (UXR-04) quit BNPL.
- **Your journey map, a shareable link, or the map file you committed (e.g. journey-map.html):** https://github.com/kpettai/Playground/blob/main/02-discovery/Lena_Future_State_Journey.html
