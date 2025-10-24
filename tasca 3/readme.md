# Tasca 03: Gestió flexible de discos (LVM i Espais d’emmagatzematge)

## Descripció de la tasca

En aquesta tasca **posarem en pràctica** els coneixements adquirits sobre la gestió flexible i segura de l’emmagatzematge de dades.  
Treballarem amb el cas real del bufet **Garriga i Associats**, una empresa amb un alt volum d’informació legal sensible que requereix **alta disponibilitat, redundància i facilitat d’administració** dels seus sistemes.

El nostre objectiu serà **dissenyar i documentar dues solucions d’emmagatzematge** —una per a entorns **Linux** i una altra per a **Windows**— que permetin garantir la protecció de la informació davant fallades de disc i facilitar l’ampliació de l’espai sense interrupcions del servei.  

Per aconseguir-ho, utilitzarem **màquines virtuals** per simular els entorns i demostrar el funcionament de les diferents configuracions, elaborant una documentació tècnica clara i completa.

## Fases del projecte

### Fase 1: Part Linux – LVM (Logical Volume Manager)

Treballarem amb **Zorin OS** (o una altra distribució Linux compatible) per implementar la gestió de volums mitjançant **LVM**.

Durant aquesta fase:
- Crearem un **grup de volums (VG)** i un **volum lògic (LV)** amb dos discos de 10 GB, formatant-lo i muntant-lo automàticament al sistema.  
- Implementarem un **mirall (lvm_mirror)** per protegir les dades davant la fallada d’un disc.  
- Generarem **instantànies (snapshots)** per comprovar com es poden restaurar dades danyades.  
- Demostrarem el procés d’**ampliació del volum lògic** utilitzant l’espai lliure del grup de volums.

### Fase 2: Part Windows – Espais d’emmagatzematge (Storage Spaces)

A l’entorn **Windows 11**, experimentarem amb la tecnologia **Storage Spaces** per aconseguir una gestió flexible i tolerant a fallades.

Durant aquesta fase:
- Crearem un **Storage Pool** inicial amb tres discos de 10 GB.  
- Provarem diferents configuracions: **mirall doble**, **mirall triple** i **paritat**, comparant la seva eficiència i resiliència.  
- Documentarem la **visualització i gestió** dels discos des de la consola d’administració de Windows, mostrant la facilitat de manteniment.

## Metodologia de treball

Treballarem en **grup**, dividint-nos en dos equips: un encarregat de la part **Linux (LVM)** i l’altre de **Windows (Storage Spaces)**.  
Cada membre prepararà el seu guió de treball, cercant comandes, procediments i fonts de documentació.  

Posteriorment, unificarem els resultats i revisarem conjuntament la documentació abans de publicar-la al nostre repositori.

## Estructura de carpetes

Dins la carpeta `tasca03` es troben els següents arxius:

- `informe_linux.md`: Documentació tècnica de la part Linux amb LVM.  
- `informe_windows.md`: Documentació tècnica de la part Windows amb Espais d’Emmagatzematge.  
- Carpeta `img/`: Conté les imatges utilitzades en ambdós informes.

## Documents

Podeu consultar tots els documents fent clic al document corresponent:
- A l’arxiu [informe_linux](informe_linux.md) podeu trobar la part Linux.  
- A l’arxiu [informe_windows](informe_windows.md) podeu trobar la part Windows.  

[Tornar pàgina del projecte](../README.md)


[Tornar pàgina del projecte](../README.md)

