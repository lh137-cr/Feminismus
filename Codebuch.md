UNSER DATENSATZ
Codebuch Stand 2021-12, aktualisiert 2021-12
erstellt von Lavinia Hutt, Isabela Dias da Motta, Jonah Constantin Schua, Letizia Scalisi und Emelie Wenz

INHALT
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

URSPRUNG UND DATENERHEBUNG
Wir haben in Büchern und Zeitschriften, sowie im Internet relevante Personen und Events recherchiert
Das Netzwerk ist ein *gerichtetes two-mode Akteurs- und Events-Netzwerk*. 


EDGE-ATTRIBUTE
**id**  
(eindeutige Codierung des Knoten)   
codiert von 1 bis 10, jede ID entspricht einem Studenten

**weight**  
Beziehungsstärke zwischen Personen und Events
3 = Organisator*in / wischtig für die Entstehung des Events,   
1 = Teilnahme an Event

**year**
Jahr, in dem das Event stattgefunden hat

NODE-ATTRIBUTE

**id**  
Identische ID wie aus der edgelist zur Identifikation der Knoten

**name**
Name der Person oder des 


**type**    
Art des Knoten 
1 = Akteur*in 
2 = Event 

**sex**
Geschlecht bei Personen
1 = weiblich
2 = männlich
3 = divers

**age**
Alter der Personen in ganzen Zahlen

