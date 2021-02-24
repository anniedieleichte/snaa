## Meine Codebuch

##Node-Attribute

**id**
eindeutige Codierung des Knoten

**name**
Vollständiger Name des Knotens

**type**
Unterscheidung zwischen Person und Organisation
0= Person
1= Organisation

**age**
Alter der Personen

**funktion**
V=Vorstand
AR=Aufsichtsrat

**representation**
Funktion innerhalb der VfB Gremien
0=Sport, Unternehmensstrategie und Kommunikation
1= Finanzen und Verwaltung
2=Kommunikation

**position**
0=Vorsitzender
1=Stellvertretender Vorsitzender
2=Mitglied

**kind**
Art der Organisation
0=Verein
1=Unternehmen
2=Verband
3=Stiftung


##Edge-Attribute

**from**
definiert den Sender 

**to**
definiert den Empfänger 

**relationship**
Um welche Art von Mitgliedschaft es sich handelt
0=Leitung (Vorstand, Aufsichtsrat, Präsidium)
1=Stellvertretende Leitung (Vorstand, Aufsichtsrat, Präsidium)
2=Mitglied
3=Gründer
4=Botschafter

**year**
Definiert das Jahr, in die Mitgliedschaft entstanden ist
