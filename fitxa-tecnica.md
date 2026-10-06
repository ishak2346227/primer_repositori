# Fitxa tècnica: Muntatge d'un ordinador de sobretaula

## Objectiu

Documentar el procés de muntatge d'un ordinador de sobretaula, explicant de manera ordenada els materials necessaris, els passos de muntatge i les comprovacions finals.

L'objectiu és aconseguir que tots els components quedin correctament instal·lats, connectats i reconeguts per la BIOS/UEFI i pel sistema operatiu.

## Materials

- Caixa ATX amb ventilació i filtres antipols.
- Placa base ATX compatible amb el processador.
- Processador Intel Core o AMD Ryzen.
- Dissipador i ventilador per a la CPU.
- Pasta tèrmica.
- Memòria RAM DDR4 o DDR5.
- SSD NVMe M.2 de 1 TB.
- Font d'alimentació modular de 750 W.
- Targeta gràfica dedicada PCIe, si és necessària.
- Tornavís d'estrella PH2.
- Brides de plàstic per organitzar els cables.
- Polsera antiestàtica.

## Procediment

1. Preparar la zona de treball, netejar la superfície i comprovar que disposem de tots els components i eines necessàries.
2. Col·locar la placa base sobre una superfície adequada per començar el muntatge fora de la caixa.
3. Obrir el sòcol de la CPU i col·locar el processador respectant la marca d'alineació.
4. Tancar el mecanisme de seguretat del sòcol sense aplicar una força excessiva.
5. Instal·lar el SSD NVMe M.2 a la ranura corresponent de la placa base i fixar-lo.
6. Instal·lar els mòduls de memòria RAM a les ranures recomanades pel fabricant per aprofitar el Dual Channel.
7. Aplicar una petita quantitat de pasta tèrmica sobre el processador.
8. Instal·lar el dissipador i el ventilador de la CPU i connectar el ventilador a la connexió `CPU_FAN`.
9. Preparar la caixa instal·lant els separadors necessaris per a una placa base ATX.
10. Col·locar la placa base dins de la caixa i fixar-la amb els cargols corresponents.
11. Instal·lar la font d'alimentació a la part inferior de la caixa.
12. Connectar el cable principal ATX de 24 pins i el cable d'alimentació de la CPU.
13. Connectar els cables del panell frontal, com ara `Power SW`, `Reset SW`, `Power LED`, USB i `HD Audio`.
14. Instal·lar la targeta gràfica a la ranura PCIe, si l'equip disposa d'una GPU dedicada.
15. Connectar els cables d'alimentació necessaris per a la targeta gràfica.
16. Organitzar els cables a la part posterior de la caixa utilitzant brides per evitar que interfereixin amb el flux d'aire.
17. Revisar totes les connexions abans d'engegar l'ordinador.
18. Engegar l'equip i entrar a la BIOS/UEFI per comprovar que els components són detectats correctament.

## Comprovacions

- [ ] L'ordinador s'encén correctament.
- [ ] La placa base rep alimentació.
- [ ] El processador és detectat per la BIOS/UEFI.
- [ ] La memòria RAM és detectada correctament.
- [ ] El SSD NVMe apareix a la BIOS/UEFI.
- [ ] La targeta gràfica és detectada, si està instal·lada.
- [ ] El ventilador del processador funciona correctament.
- [ ] Les temperatures del processador són normals.
- [ ] El sistema operatiu detecta els components instal·lats.
- [ ] El cablatge està ordenat i no interfereix amb els ventiladors.

Per comprovar la informació del processador des de Linux es pot utilitzar la comanda:

```bash
lscpu