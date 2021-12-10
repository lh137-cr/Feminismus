# UNSER DATENSATZ # 
Codebuch Stand 2021-12, aktualisiert 2021-12
erstellt von Lavinia Hutt, Isabela Dias da Motta, Jonah Constantin Schua, Letizia Scalisi und Emelie Wenz

## INHALT ##
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

## URSPRUNG UND DATENERHEBUNG ##
Wir haben in Büchern und Zeitschriften, sowie im Internet relevante Personen und Events recherchiert
Das Netzwerk ist ein *gerichtetes two-mode Akteurs- und Events-Netzwerk*. 


# EDGE-ATTRIBUTE #
**id**  </p>
(eindeutige Codierung des Knoten)   
codiert von 1 bis 10, jede ID entspricht einem Studenten

**weight**  </p>
Beziehungsstärke zwischen Personen und Events </p>
3 = Organisator*in / wichtig für die Entstehung des Events,</p>
1 = Teilnahme an Event/Mitglied der Gruppe

**year** </p>
Jahr, in dem das Event stattgefunden hat

# NODE-ATTRIBUTE #

**id**  </p>
Identische ID wie aus der edgelist zur Identifikation der Knoten

**name** </p>
Name der Person oder des Events


**type**    </p>
Art des Knoten </p>
1 = Akteur*in oder Gruppe</p>
2 = Event </p>

**sex** </p>
Geschlecht bei Personen </p>
1 = weiblich</p>
2 = männlich</p>
3 = divers</p>

**year** </p>
Geburtsjahr der Person oder Gründung der Gruppe


