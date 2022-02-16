# Mitschriften

## Rollen

1. Gast: alles bis 1
2. Supporter/User: alles bis 2
3. Researcher (#3): alles bis 3
4. Cancer Specialist (#4): alles bis 4
5. Core-Team (Vollzugriff ohne admin-rechte): alles bis 5
6. admin: alles

## Rollenübergänge

- Gast2Supporter_User
	- Zwangseingabe: Vorstellung des Users (Name,...) --> Supporter/User
	- Berechtigungen:
		- #1, #2

- Supporter_User2ResearcherORCancerSpecialist
	- Entscheidung des Supporter/Users: Welche Rolle möchte ich sein? 
		- Support/User ODER Researcher ODER Cancer-Specialist
		- einmalige, selbstständige Vergabe einer der drei Rollen
		- Nachricht an admin / Core-Team
		- admin: Kann Rollen vergeben
		

# Modellierung

## Rollen

| Rolle 			| #1 		| #2 		| #3 		| #4 		| #5 		| #6 		| Wie bekommt man die Rolle																			| Anleitung
|---: 				|--- 		|--- 		|--- 		|--- 		|--- 		|--- 		|--- 																								|:---:
| Gast 				| x 		| 			| 			| 			| 			| 			| <li>Server beitreten</li> 															
| Supporter/User 	| x 		| x 		| 			| 			| 			| 			| <li>Vorstellung in #willkommen </li><li>Reaktion Daumen hoch in #serverbeitritt</li>				| [Hier](./Gast2Supporter_User.png)
| Researcher 		| x 		| x 		| x 		| 			| 			|			| <li>informelle Anfrage in #2admin-talk</li>																| [Hier](./Supporter_User2ResearcherORCancerSpecialist.png)
| Cancer Specialist | x 		| x 		| x 		| x 		| 			| 			| <li>informelle Anfrage in #2admin-talk</li> 																| [Hier](./Supporter_User2ResearcherORCancerSpecialist.png)
| Core-Team 		| x 		| x 		| x 		| x 		| x 		| x 		| <li>ausgeschlossen</li>																					| 
| admin 			| x 		| x 		| x 		| x 		| x 		| x 		| <li>ausgeschlossen</li>																					| 

	
		
