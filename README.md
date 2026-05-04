# AI-DRIVEN-DEVELOPMENT

## Produktidee
WG-Einkaufshelfer

## Problem
In Wohngemeinschaften oder Haushalten werden oft Dinge doppelt gekauft oder wichtige Vorräte (wie Milch oder Toilettenpapier) vergessen, weil die Absprache fehlt.

## Ziel
Entwicklung einer minimalistischen Web-App, mit der Bewohner gemeinsam eine digitale Einkaufsliste verwalten können.

## Kern-Anwendungsfälle
- Produkt hinzufügen
- Menge angeben (optional)
- Live-Liste einsehen
- Artikel als erledigt markieren/abhaken

## Warum diese Idee für den Workshop funktioniert
- ähnlich wie Todo-Listen
- hoher Alltagsbezug für die Teilnehmer
- klein genug, um in einem Workshop gebaut zu werden





# Product Requirements Document (PRD)

## Product Name  
WG-Einkaufshelfer

## Overview  
Der WG-Einkaufshelfer ist eine einfache Web-App, mit der mehrere Personen gemeinsam eine Einkaufsliste verwalten können. Ziel ist es, den Alltag in Wohngemeinschaften oder Haushalten zu erleichtern.

## Problem  
In WGs oder Haushalten fehlt oft die Abstimmung beim Einkaufen. Dadurch werden Produkte doppelt gekauft oder wichtige Dinge wie Milch oder Toilettenpapier vergessen.

## Solution  
Eine minimalistische Web-App, in der Nutzer gemeinsam eine Einkaufsliste führen können. Produkte können hinzugefügt, Mengen angegeben und erledigte Einkäufe abgehakt werden.

## Target Users  
- WG-Bewohner  
- kleine Haushalte  
- Personen, die gemeinsam einkaufen organisieren möchten   

## Core Features  
1. Produkt zur Liste hinzufügen  
2. Optionale Mengenangabe (z. B. 2x Milch)  
3. Anzeige aller Produkte in einer gemeinsamen Liste  
4. Artikel als erledigt markieren/abhaken  

## Non-Goals  
- kein Login-System  
- kein Backend
- keine Benachrichtigungen  

## Success Criteria  
- ein Produkt kann in weniger als 10 Sekunden hinzugefügt werden  
- die Liste bleibt nach einem Refresh erhalten  
- erledigte Artikel sind klar visuell erkennbar  

## Suggested Tech Stack  
- React  
- Vite  
- localStorage



## User Stories

### 1. Produkt zur Liste hinzufügen  
**User Story**  
Als WG-Bewohner möchte ich ein Produkt zur Einkaufsliste hinzufügen können, damit wichtige Dinge nicht vergessen werden.

**Acceptance Criteria**  
- Nutzer kann einen Produktnamen eingeben  
- Nutzer kann das Produkt zur Liste hinzufügen  
- Das Produkt erscheint sofort in der Liste  

---

### 2. Einkaufsliste einsehen  
**User Story**  
Als Nutzer möchte ich alle Produkte auf der Einkaufsliste sehen, damit ich Doppelkäufe vermeide.

**Acceptance Criteria**  
- Alle hinzugefügten Produkte werden in einer Liste angezeigt  
- Die Liste wird übersichtlich dargestellt  
- Bereits vorhandene Produkte sind klar erkennbar  

---

### 3. Artikel abhaken  
**User Story**  
Als Nutzer möchte ich gekaufte Produkte abhaken können, damit ich weiß, was noch fehlt.

**Acceptance Criteria**  
- Nutzer kann einen Artikel als erledigt markieren  
- Erledigte Artikel sind visuell unterscheidbar (z. B. durch Durchstreichen)  
- Der Status bleibt nach einem Refresh erhalten  
