# UNSER DATENSATZ # 
Codebuch Stand 2021-12, aktualisiert 2021-12
erstellt von Lavinia Hutt, Isabela Dias da Motta, Jonah Constantin Schua, Letizia Scalisi, Emelie Wenz und Julia Habenicht

## INHALT ##
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

## URSPRUNG UND DATENERHEBUNG ##
Wir haben in Büchern und Zeitschriften, sowie im Internet relevante Personen und Events recherchiert, unter anderem:</p>
Berlin wird feministisch - Cristina Perincioli, Querverlag GmbH 2015 (Autorin war selbst Akteurin und interviewt andere Akteur/innen der Zeit</p>
https://frauenmediaturm.de/neue-frauenbewegung/chronik-1975/ *zuletzt abgerufen 07. Dezember 2021* </p>
https://www.digitales-deutsches-frauenarchiv.de/akteurinnen/brot-und-rosen#actor-content-about
feminismus/feminismus *zuletzt abgerufen am 07.12.2021* </p>
https://www.fes.de/politische-akademie/onlineakademie/geschichte/story-slider-feminismus/feminismus *zuletzt abgerufen am 04.12.2021* </p>
https://frauenmediaturm.de/frauenbewegung-2/chronik-neue-frauenbewegung/ *zuletzt abgerufen am 10.12.2021* </p>
https://dffb-archiv.de/editorial/feminismen-dffb-1966-85 *zuletztabgerufen am 04.12.2021* </p>
https://frauenmediaturm.de/frauenbewegung-2/pionierinnen/ *zuletzt abgerufen am 05.12.2021* </p>
https://www.transcript-verlag.de/media/pdf/4a/78/95/oa9783839424087.pdf *am 07.12.2021* </p>

Das Netzwerk ist ein *gerichtetes two-mode Akteurs- und Events-Netzwerk*. 
Die Sample-Auswahl haben wir getroffen, da diese Akteur/innen unserer Meinung nach die Relevantesten von der Berliner Frauenbewegung im Zeitraum 1968-1975 waren und an den größten Meilensteinen mitgewirkt haben. 

# EDGE-ATTRIBUTE #
**id**  </p>
(eindeutige Codierung des Knoten)   
codiert von 1 bis 10, jede ID entspricht einem/r Akteur/in bzw einem Event

**relationship**  </p>
Beziehungsart zwischen Personen und Events </p>
1 = Organisator/in des Events,</p>
2 = Teilnahme an Event </p>
3 = Mitglied der Gruppe </p>
4 = Mitglied der Wohngemeinschaft </p>
5 = gemeinsame Zeit in einer Wohngemeinschaft </p>
6 = gemeinsame Mitgliedschaft einer Gruppe </p>
7 = gemeinsame Organisation eines Events </p>
8 = Gründer/in der Gruppe </p>
9 = Leiter/in der Gruppe

**year** </p>
Jahr, in dem die Beziehung anfing

# NODE-ATTRIBUTE #

**id**  </p>
Identische ID wie aus der edgelist zur Identifikation der Knoten

**name** </p>
Kürzel des Namens, um die Visualisierung vorerst zu vereinfachen

**name_first** </p>
tatsächlicher Name der Person oder des Events

**type**    </p>
Art des Knoten </p>
1 = Akteur/in oder Gruppe</p>
2 = Event </p>

**sex** </p>
Geschlecht bei Personen </p>
1 = weiblich</p>
2 = männlich</p>
3 = divers</p>

**year** </p>
Geburtsjahr der Person/Zeitpunkt des Events

**origin** </p>
1 = Land </p>
2 = Stadt

**education** </p>
1 = Student/in </p>
2 = kein/e Student/in
