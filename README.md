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
- Einsteiger mit Bedarf an einer einfachen Lösung  

## Core Features  
1. Produkt zur Liste hinzufügen  
2. Optionale Mengenangabe (z. B. 2x Milch)  
3. Anzeige aller Produkte in einer gemeinsamen Liste  
4. Artikel als erledigt markieren/abhaken  
5. Speicherung der Liste im lokalen Speicher  

## Non-Goals  
- kein Login-System  
- kein Backend  
- keine Benutzerverwaltung  
- keine Echtzeit-Synchronisation über Geräte hinweg  
- keine Benachrichtigungen  

## Success Criteria  
- ein Produkt kann in weniger als 10 Sekunden hinzugefügt werden  
- die Liste bleibt nach einem Refresh erhalten  
- erledigte Artikel sind klar visuell erkennbar  

## Suggested Tech Stack  
- React  
- Vite  
- localStorage  
- einfaches CSS  
