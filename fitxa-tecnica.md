Fitxa tècnica: Muntatge d'un ordinador de sobretaula
Objectiu

Documentar el procés de muntatge d'un ordinador de sobretaula, explicant de manera ordenada els materials necessaris, els passos de muntatge i les comprovacions finals. L'objectiu és aconseguir que tots els components quedin correctament instal·lats, connectats i reconeguts per la BIOS/UEFI i pel sistema operatiu.

Materials

Caixa ATX amb ventilació i filtres antipols.

Placa base ATX compatible amb el processador.

Processador Intel Core o AMD Ryzen.

Dissipador i ventilador per a la CPU.

Pasta tèrmica.

Memòria RAM DDR4 o DDR5.

SSD NVMe M.2 de 1 TB.

Font d'alimentació modular de 750 W.

Targeta gràfica dedicada PCIe, si és necessària.

Tornavís d'estrella PH2.

Brides de plàstic per organitzar els cables.

Polsera antiestàtica.

Procediment

Preparar la zona de treball, netejar la superfície i comprovar que disposem de tots els components i eines necessàries.

Col·locar la placa base sobre una superfície adequada per començar el muntatge fora de la caixa.

Obrir el sòcol de la CPU i col·locar el processador respectant la marca d'alineació.

Tancar el mecanisme de seguretat del sòcol sense aplicar una força excessiva.

Instal·lar el SSD NVMe M.2 a la ranura corresponent de la placa base i fixar-lo.

Instal·lar els mòduls de memòria RAM a les ranures recomanades pel fabricant per aprofitar el Dual Channel.

Aplicar una petita quantitat de pasta tèrmica sobre el processador.

Instal·lar el dissipador i el ventilador de la CPU i connectar el ventilador a la connexió CPU_FAN.

Preparar la caixa instal·lant els separadors necessaris per a una placa base ATX.

Col·locar la placa base dins de la caixa i fixar-la amb els cargols corresponents.

Instal·lar la font d'alimentació a la part inferior de la caixa.

Connectar el cable principal ATX de 24 pins i el cable d'alimentació de la CPU.

Connectar els cables del panell frontal, com ara Power SW, Reset SW, Power LED, USB i HD Audio.

Instal·lar la targeta gràfica a la ranura PCIe, si l'equip disposa d'una GPU dedicada.

Connectar els cables d'alimentació necessaris per a la targeta gràfica.

Organitzar els cables a la part posterior de la caixa utilitzant brides per evitar que interfereixin amb el flux d'aire.

Revisar totes les connexions abans d'engegar l'ordinador.

Engegar l'equip i entrar a la BIOS/UEFI per comprovar que els components són detectats correctament.

Comprovacions

 L'ordinador s'encén correctament.

 La placa base rep alimentació.

 El processador és detectat per la BIOS/UEFI.

 La memòria RAM és detectada correctament.

 El SSD NVMe apareix a la BIOS/UEFI.

 La targeta gràfica és detectada, si està instal·lada.

 El ventilador del processador funciona correctament.

 Les temperatures del processador són normals.

 El sistema operatiu detecta els components instal·lats.

 El cablatge està ordenat i no interfereix amb els ventiladors.

Per comprovar la informació del processador des de Linux es pot utilitzar la comanda:

lscpu


Aquesta comanda mostra informació sobre l'arquitectura, el fabricant, el model del processador, el nombre de nuclis i els fils d'execució.

Incidències i solucions
Incidència	Solució
L'ordinador no s'encén	Comprovar que la font d'alimentació està connectada i que els cables ATX de 24 pins i CPU estan ben connectats.
La pantalla no mostra imatge	Comprovar la connexió del monitor i revisar la instal·lació de la targeta gràfica.
La memòria RAM no és detectada	Apagar l'ordinador i comprovar que els mòduls estan ben inserits a les ranures recomanades.
El SSD NVMe no apareix	Revisar que el SSD estigui correctament instal·lat a la ranura M.2.
La CPU presenta temperatures elevades	Comprovar la instal·lació del dissipador, el ventilador i la pasta tèrmica.
Els ventiladors no funcionen	Revisar les connexions dels ventiladors i comprovar que estan connectats als connectors corresponents de la placa base.
Imatge del procés

Flux de treball amb Git

Git permet controlar les diferents versions de la documentació i consultar els canvis realitzats.

El flux de treball utilitzat és el següent:

Utilitzar git status per comprovar l'estat del repositori.

Utilitzar git diff per revisar els canvis realitzats.

Utilitzar git add per preparar els fitxers que volem guardar.

Utilitzar git commit per crear una versió amb un missatge descriptiu.

Utilitzar git log --oneline per consultar l'historial de commits.

Utilitzar git push per sincronitzar els canvis amb el repositori remot de GitHub.

Aquest sistema permet mantenir un historial ordenat de la documentació i recuperar informació de versions anteriors si és necessari.

Recursos

Documentació oficial de GitHub

Documentació oficial de Git

Documentació del fabricant de la placa base.

Documentació del fabricant dels components utilitzats.