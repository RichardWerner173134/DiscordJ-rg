# Modellierung

## Rollen

| Rolle 			| #1 		| #2 		| #3 		| #4 		| #5 		| #6 		| Wie bekommt man die Rolle																					| Anleitung
|---: 				|--- 		|--- 		|--- 		|--- 		|--- 		|--- 		|--- 																										|:---:
| Gast 				| x 		| 			| 			| 			| 			| 			| <li>Server beitreten</li> 																				| 														
| Supporter/User 	| x 		| x 		| 			| 			| 			| 			| <li>Vorstellung in #willkommen </li><li>Reaktion Daumen hoch in #serverbeitritt</li>						| [Hier](./Modellierung/Gast2Supporter_User.png)
| Researcher 		| x 		| x 		| x 		| 			| 			|			| <li>informelle Anfrage in #2admin-talk</li>																| [Hier](./Modellierung/Supporter_User2ResearcherORCancerSpecialist.png)
| Cancer Specialist | x 		| x 		| x 		| x 		| 			| 			| <li>informelle Anfrage in #2admin-talk</li> 																| [Hier](./Modellierung/Supporter_User2ResearcherORCancerSpecialist.png)
| Core-Team 		| x 		| x 		| x 		| x 		| x 		| x 		| <li>ausgeschlossen</li>																					| 
| admin 			| x 		| x 		| x 		| x 		| x 		| x 		| <li>ausgeschlossen</li>			

# Begrüßungsnachricht

## Einordnung
Die Nachricht kommt, nachdem ein Nutzer dem Server beitritt. Sie kommt in Discord in privaten Nachrichten an.
Der Text ist frei konfigurierbar.

## Inhalt
Willkommen auf dem Server von Jörg.

Bitte stell dich im Channel willkommen kurz vor. Kopiere dafür folgenden Text und fülle die Lücken aus:

```
Name: <Name><Nachname>
Gewünschte Rolle: (Supporter/User ODER Researcher ODER Cancer Specialist)
```

Im Channel Rollenvergabe #serverbeitritt kannst du den Regeln zustimmen, um als Nutzer angenommen zu werden.

# Konfigurationen

## MEE6 Bot
- private Begrüßungsnachricht
- automatische Rollenvergabe von Supporter/Gast in #serverbeitritt

## innerhalb von Discord

### Channel Willkommen
- Für alle sichtbar
- slow-modus
- schreiben können nur für Gast

### Channel Serverbeitritt
- nur für Gast sichtbar, damit supporter/user als niedrigste Rolle nach Akzeptieren bleibt
- schreiben nicht möglich