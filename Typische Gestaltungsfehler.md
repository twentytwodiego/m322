# User Inyerface – Analyse typischer UI/UX-Fehler


## 1. Übersicht
Ziel der Übung:  
Typische Usability-Fehler erkennen, beschreiben und optimieren.

---

# 2. Gefundene UI/UX-Fehler + Optimierungsvorschläge

## Fehler 1: Der grosse grüne „NO“-Button ist eigentlich der Start
-  Problem:   
  Der auffälligste Button („NO“) führt  nicht  zum Start. Stattdessen muss man den unauffälligen Link *“click HERE”* nutzen.
-  Warum schlecht:   
  Verstösst gegen Benutzererwartungen, verwirrend, führt zu Fehlklicks.
-  Optimierung:   
  Primärer Button sollte klar als *“Start”* beschriftet sein und deutlich sichtbar sein. Sekundäre Optionen (Ablehnen etc.) weniger prominent gestalten.

---

## Fehler 2: „click HERE“ ist der echte Startlink
-  Problem:   
  Der Start-Link ist klein, schwach formatiert und wirkt wie normaler Text.
-  Warum schlecht:   
  Niedrige Visibility, führt zu Irritation und unnötigem Suchen.
-  Optimierung:   
  Startaktion klar als Button gestalten, eindeutige CTA („Continue“, „Start“).

---

## Fehler 3: Cookie-Banner ist manipulativ
-  Problem:   
  Der Cookie-Hinweis oben in ROT wirkt wie eine Fehlermeldung. Der Button *“Yes”* ist rechts stark hervorgehoben, *“Not really, no”* ist klein und unscheinbar.
-  Warum schlecht:   
  Dark Pattern (Nudging), lenkt Benutzer in eine Richtung.
-  Optimierung:   
  Neutrale Farbgestaltung, gleiche Button-Grösse, klare Entscheidungsmöglichkeit.

---

## Fehler 4: Passwortanforderungen sind unten versteckt
-  Problem:   
  Die zahlreichen Passwortregeln stehen ganz unten und nicht nahe beim Eingabefeld.
-  Warum schlecht:   
  Benutzer sehen sie erst zu spät → Error-first statt Help-first.
-  Optimierung:   
  Anforderungen direkt unter oder im Input anzeigen. Nur die relevanten Regeln anzeigen.

---

## Fehler 5: Ungewöhnliche und absurde Passwortregeln
-  Beispiele:   
  - Muss mindestens einen Buchstaben der eigenen E-Mail enthalten  
  - Muss mindestens 1 kyrillischen Buchstaben enthalten  
-  Warum schlecht:   
  Realitätsfern, nicht nachvollziehbar, frustrierend.
-  Optimierung:   
  Standardisierte und nachvollziehbare Regeln nutzen (Länge, Zahlen, Sonderzeichen).

---

## Fehler 6: Checkbox „I do not accept the Terms & Conditions“
-  Problem:   
  Formular verlangt, dass man *“Terms & Conditions NICHT akzeptiert”*.
-  Warum schlecht:   
  Logische Umkehrung, führt zu Fehlern und rechtlichen Problemen.
-  Optimierung:   
  Checkbox wie üblich formulieren: „I accept the Terms & Conditions“.  
  Ohne Doppelverneinung.

---

## Fehler 7: „Next“ ist deaktiviert, „Cancel“ ist der primäre Button
-  Problem:   
  Der primäre, farblich dominante Button ist „Cancel“.  
  „Next“ wirkt deaktiviert, obwohl der Benutzer eigentlich weiter will.
-  Warum schlecht:   
  Verstösst gegen Konventionen, sorgt für Fehlbedienung.
-  Optimierung:   
  Primärer Button = Weiter/Next.  
  Sekundär = Cancel.  
  Visuell klar unterscheiden.

---

## Fehler 8: Dropdown mit „other“ für Domain ist verwirrend
-  Problem:   
  Nutzer müssen selbst die Domain manuell eingeben, obwohl es gängige Domains gibt.
-  Warum schlecht:   
  Erzeugt Extra-Aufwand ohne Mehrwert.
-  Optimierung:   
  Automatisch Domain aus E-Mail extrahieren, Vorschläge geben oder Eingabefeld vereinfachen.

---

## Fehler 9: Fortschrittsanzeige (1/4) vermittelt keinen klaren Fortschritt
-  Problem:   
  UI zeigt 1/4, aber Steps (1–4) wirken wie Tabs, die man anklicken kann – funktionieren aber nicht.
-  Warum schlecht:   
  Falsche Interaktionssignale.
-  Optimierung:   
  Entweder echte Tabs oder deaktivierte Steps visuell klar abgrenzen.

---

## Fehler 10: „Reset“ ist kaum sichtbar
-  Problem:   
  Reset steht blass und wirkt nutzlos, obwohl es eine destruktive Aktion wäre.
-  Warum schlecht:   
  Inkonsequente Gewichtung von Aktionen.
-  Optimierung:   
  Reset entweder deutlich sichtbar oder in ein Optionsmenü verschieben.

---

# 3. Zusammenfassung / Fazit

User Inyerface zeigt systematisch, wie schlechte UI/UX entsteht:

- Falsche visuelle Hierarchie  
- Irreführende Buttons  
- Manipulative Dark Patterns  
- Versteckte Informationen  
- Unklare Struktur  
- Unlogische Eingaben  

Diese Beispiele helfen, typische Fehler zu erkennen und im eigenen Design zu vermeiden.

