# AlbamarUno

Beschrijving
In AlbamarUno worden activiteiten geregistreerd door sensoren in een Z-Wave mesh-netwerk en vastgelegd in /var/log/Z-Wave*.log. 
Onafhankelijk van het Z-Wave netwerk loopt een proces in de vorm van een Python programma dat periodiek het Z-Wave log leest en alle mutaties die hierop plaatsvinden opslaat in een apart logbestand, genaamd sensor.log. Als tweede stap in dit proces wordt het sensor.log bestand, mits gewijzigd, middels ftp geupload naar een website.
Wanneer aangeroepen met een browser toont de website een kalender, waarin gearceerd de dagen waarop activiteit is vastgesteld.
Het zijn daarmee drie onafhankelijke processen waarvoor specifieke technologie is gebruikt, namelijk resp. Z-Way, Python en PHP/ Javascript.

Bug-list
001

Back-log
001
