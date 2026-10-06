# Fitxa tècnica: Muntatge d'un ordinador de sobretaula

## Objectiu

Documentar i detallar el procediment pas a pas per al muntatge complet i sistemàtic d'un ordinador de sobretaula d'alt rendiment. L'objectiu principal és garantir la correcta instal·lació física de cada component hardware, optimitzar el flux d'aire de la caixa, organitzar el cablatge intern i assegurar que el sistema reconegui tots els dispositius des de la BIOS/UEFI sense conflictes tècnics.

## Materials

- **Chassis/Caixa:** Caixa ATX amb panell lateral de vidre i filtre antipols.
- **Placa base:** Placa base format ATX compatible amb processadors Intel/AMD de darrera generació.
- **Processador:** CPU Intel Core / AMD Ryzen.
- **Sistema de refrigeració:** Refrigeració per aire de doble torre amb ventilador PWM de 120mm.
- **Memòria RAM:** Kit de 32 GB (2x16 GB) DDR4/DDR5 a alta velocitat.
- **Emmagatzematge:** SSD NVMe M.2 de 1 TB d'alta velocitat.
- **Font d'alimentació:** Font d'alimentació 750W 80 Plus Gold modular.
- **Targeta gràfica (opcional):** GPU dedicada PCIe 4.0/5.0.
- **Eines:** Tornavís d'estrella (PH2) magnètic, brides de plàstic per a la gestió de cables i polsera antiestàtica.

## Procediment

1. **Preparació de l'entorn de treball:**
   Netejar la taula de treball, col·locar una catifa antiestàtica i posar-se la polsera de presa a terra. Desempaquetar tots els components hardware i revisar que totes les peces i fons de caragols estiguin complets.

2. **Muntatge inicial a la placa base (fora de la caixa):**
   - Obrir el sòcol de la CPU (socket), orientar el processador segons el triacle indicador d'alineació i col·locar-lo amb molta cura sense fer pressió.
   - Tancar la palanca de seguretat del sòcol.
   - Instal·lar el disc SSD NVMe M.2 a la ranura principal i fixar-lo amb el caragol o tancament ràpid.
   - Insertar els mòduls de memòria RAM a les ranures recomanades per a Dual Channel (normalment A2 i B2) fins a sentir el "clic" dels pestells.

3. **Instal·lació del sistema de refrigeració:**
   - Aplicar una petita quantitat de pasta tèrmica (mida d'un gra de llessa) sobre el centre de l'IHS de la CPU.
   - Col·locar el dissipador i caragolar-lo en patró de creu per repartir la pressió de manera uniforme.
   - Connectar el cable del ventilador a la presa `CPU_FAN` de la placa base.

4. **Instal·lació de la font d'alimentació i muntatge al chassis:**
   - Montar els caragols de separació (standoffs) a la caixa ATX segons el format de la placa.
   - Instal·lar el shield I/O posterior si la placa no el porta integrat.
   - Col·locar la placa base a la caixa i fixar-la amb els caragols corresponents sense forçar el roscat.
   - Instal·lar la font d'alimentació a la part inferior de la caixa i passar els cables principals (`ATX 24 pins` i `CPU 8 pins`) per la part posterior del chassis.

5. **Connexions internes i gestió de cablatge:**
   - Connectar l'alimentació de 24 pins a la placa i els 8 pins per a la CPU.
   - Connectar els cables del panell frontal de la caixa (`Power SW`, `Reset SW`, `Power LED`, `HDD LED`, `USB 3.0` i `HD Audio`) als pins corresponents de la placa base.
   - Fixar tots els cables posteriors amb brides per millorar l'estètica i afavorir el flux d'aire intern.

### Imatge del procés

![Muntatge de la CPU](https://hardzone.es/app/uploads-hardzone.es/2021/01/geforce.png)

### Comanda de comprovació

Per comprovar la CPU des del terminal una vegada engegat el sistema Linux:git log --oneline
## Incidències i solucions

| Incidència | Solució |
|---|---|
| L'ordinador no s'encén | Comprovar que la font d'alimentació està connectada i que els cables ATX de 24 pins i CPU estan ben connectats. |
| La pantalla no mostra imatge | Comprovar la connexió del monitor i revisar la instal·lació de la targeta gràfica. |
| La memòria RAM no és detectada | Apagar l'ordinador i comprovar que els mòduls estan ben inserits a les ranures recomanades. |
| El SSD NVMe no apareix | Revisar que el SSD estigui correctament instal·lat a la ranura M.2. |
| La CPU presenta temperatures elevades | Comprovar la instal·lació del dissipador, el ventilador i la pasta tèrmica. |
| Els ventiladors no funcionen | Revisar les connexions dels ventiladors i comprovar que estan connectats als connectors corresponents de la placa base. |

## Imatge del procés

![Muntatge d'un ordinador de sobretaula](muntatge-pc.jpg)

*Imatge del procés de muntatge d'un ordinador de sobretaula.*

## Flux de treball amb Git

Git permet controlar les diferents versions de la documentació i consultar els canvis realitzats.

El flux de treball utilitzat és el següent:

1. Utilitzar `git status` per comprovar l'estat del repositori.
2. Utilitzar `git diff` per revisar els canvis realitzats.
3. Utilitzar `git add` per preparar els fitxers que volem guardar.
4. Utilitzar `git commit` per crear una versió amb un missatge descriptiu.
5. Utilitzar `git log --oneline` per consultar l'historial de commits.
6. Utilitzar `git push` per sincronitzar els canvis amb el repositori remot de GitHub.

Aquest sistema permet mantenir un historial ordenat de la documentació i recuperar informació de versions anteriors si és necessari.

## Recursos

- [Documentació oficial de GitHub](https://docs.github.com/)
- [Documentació oficial de Git](https://git-scm.com/doc/)
- Documentació del fabricant de la placa base.
- Documentació del fabricant dels components utilitzats.