# Tasca 03: Gestió flexible de discos (LVM i Espais d’emmagatzematge)

## Descripció de la tasca

En aquesta tasca **posarem en pràctica** els coneixements adquirits sobre la gestió flexible i segura de l’emmagatzematge de dades.  
Treballarem amb el cas del bufet **Garriga i Associats**, una empresa amb un gran volum d’informació legal sensible que necessita **alta disponibilitat, redundància i escalabilitat** en els seus sistemes.

El nostre objectiu serà **dissenyar i documentar dues solucions d’emmagatzematge** —una per a **entorns Linux** i una altra per a **Windows**— que garanteixin la protecció i disponibilitat de les dades davant possibles fallades de disc, i que permetin ampliar la capacitat d’emmagatzematge de forma dinàmica i sense interrupcions.

Per demostrar-ho, utilitzarem **màquines virtuals** per simular les configuracions i documentarem tot el procés amb imatges i explicacions detallades.

## Fases del projecte

### Fase 1: Part Linux – LVM (Logical Volume Manager)

Treballarem amb **Zorin OS** (o una altra distribució Linux equivalent) per implementar la gestió de volums lògics mitjançant **LVM**.  
Durant aquesta fase:

- Crearem un **grup de volums (VG)** i un **volum lògic (LV)** amb dos discos de 10 GB, formatant-lo i muntant-lo automàticament al sistema.  
- Implementarem un **mirall (lvm_mirror)** per protegir les dades davant la fallada d’un disc.  
- Generarem **instantànies (snapshots)** per comprovar la recuperació de dades davant danys.  
- Demostrarem l’**ampliació del volum lògic** utilitzant l’espai lliure del grup de volums.

### Fase 2: Part Windows – Espais d’emmagatzematge (Storage Spaces)

A l’entorn **Windows 11**, treballarem amb la tecnologia **Storage Spaces** per configurar sistemes redundants i escalables.  
Durant aquesta fase:

- Crearem un **Storage Pool** amb tres discos de 10 GB.  
- Provarem diferents configuracions: **mirall doble**, **mirall triple** i **paritat**, analitzant la seva eficiència i avantatges.  
- Mostrarem com es pot **gestionar i monitorar l’estat dels discos** des de la consola d’administració de Windows, demostrant la seva facilitat d’ús i manteniment.

## Metodologia de treball

Treballarem en **grup**, dividint-nos en dos equips principals: un encarregat de la part **Linux (LVM)** i l’altre de **Windows (Storage Spaces)**.  
Cada membre elaborarà el seu **guió individual de treball**, investigant comandes, configuracions i fonts tècniques de suport.  

Posteriorment, unificarem la documentació en un **informe comú**, que inclourà les dues parts del projecte i totes les demostracions pràctiques.

## Estructura de carpetes

Dins la carpeta `tasca03` es troben els següents arxius:

- `informe.md`: Document tècnic amb la descripció, configuració i demostració de les dues solucions (Linux i Windows).  
- Carpeta `img/`: Conté les imatges utilitzades a l’informe.

## Documents

Podeu consultar tots els documents fent clic al document corresponent:
- A l’arxiu [informe](informe.md) podeu trobar l’informe complet del projecte de zorin.
- A l’arxiu [informe](informe.windows.md) podeu trobar l’informe complet del projecte de windows.


[Tornar pàgina del projecte](../README.md)
