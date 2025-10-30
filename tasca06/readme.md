# Tasca 06: Fonaments del servei DNS

## Descripció de la tasca

En aquesta tasca **posarem en pràctica** els coneixements adquirits sobre el funcionament i diagnosi del **servei DNS**.  
Com a membres de l’equip tècnic de la consultora **EverPia**, heu rebut l’encàrrec de l’empresa de màrqueting digital **DigiCore**, que pateix problemes ocasionals de connectivitat i sospita que la causa és una **resolució de noms lenta o incorrecta**.

L’objectiu principal és **realitzar una auditoria teòrica i pràctica del servei DNS**, formant el personal tècnic del client i proporcionant-los **eines de diagnosi eficients** per detectar i resoldre problemes de resolució de noms.

---

## Fases del projecte

### Fase 1: Fase Teòrica – Sessió Formativa

En aquesta primera fase s’ha de crear **material formatiu** que expliqui els conceptes essencials del sistema DNS.  
Aquesta sessió servirà com a base per al personal tècnic de DigiCore, que rebrà una **píndola formativa en vídeo** (entre **10 i 15 minuts**) amb els continguts següents:

- **Jerarquia i estructura del DNS:** Root → TLD → Segon nivell.  
- **Procés de resolució:** consultes **iteratives** i **recursives**; diferència entre **servidor d’arrel** i **autoritatiu**.  
- **Tipus de zones:** directa, inversa, primària i secundària.  
- **Tipus de registres (records):** A, CNAME, MX, NS i SRV.  
- **Concepte de resposta autoritativa** i com identificar-la.  
- **Time To Live (TTL):** la seva funció i efecte en el rendiment.  
- **Start of Authority (SOA):** informació essencial i importància.  
- **Reenviadors (forwarders):** condicionals i incondicionals.  
- **Resolució local (mDNS):** mecanisme de resolució sense servidor dins la xarxa local.

**Activitat de la fase teòrica:**  
Un cop dominats aquests conceptes, cal preparar un **vídeo formatiu** (durada entre 10 i 15 minuts) que resumeixi de manera clara tots aquests punts.

---

### Fase 2: Fase Pràctica – Diagnosi de noms (Auditoria amb CLI)

En aquesta fase es demostrarà l’ús de les principals **eines de diagnosi DNS** tant en **Linux/macOS** com en **Windows**.  
Per a les proves s’utilitzarà una màquina **Zorin OS** amb dues interfícies de xarxa:

- **Primera interfície (NAT):** connexió a Internet.  
- **Segona interfície (Adaptador Pont):** IP estàtica configurada segons indicacions dels responsables.

#### A. Diagnosi avançada amb `dig` (Linux / macOS)

- **Comanda 1:** `dig xtec.cat A` → Identificar IP de resposta, TTL i servidor.  
- **Comanda 2:** `dig tecnocampus.cat NS` → Determinar servidors de noms autoritatius.  
- **Comanda 3:** `dig escolapia.cat SOA` → Localitzar correu de l’administrador i número de sèrie.  
- **Comanda 4:** `dig -x 147.83.2.135` → Analitzar informació obtinguda en la resolució inversa.

#### B. Comprovació amb `nslookup` (Multiplataforma)

L’eina `nslookup` permet realitzar les mateixes proves des de qualsevol sistema operatiu.

- **Comanda 1:** consulta bàsica **no autoritativa** del domini `tecnocampus.cat`.  
  - Anàlisi: per què indica que la resposta és no autoritativa?  
- **Comanda 2:** consulta **autoritativa** dirigint-se directament a un dels servidors NS del domini.  
  - Anàlisi: quines diferències s’observen respecte la resposta anterior?

#### C. Resolucions locals

Comprovació del funcionament de la **resolució local (mDNS)** entre equips d’una mateixa xarxa sense servidor de noms dedicat.

**Activitat de la fase pràctica:**  
Crear un document `guia.md` amb:
- Les captures de les **6 comandes** indicades.  
- Les explicacions i anàlisis de cada resultat.  
- Les proves de resolució local realitzades.

---

## Estructura de carpetes

Dins la carpeta `tasca06` es troben els següents arxius:

- `solució.md`: Document tècnic amb la descripció, configuració i anàlisi de totes les proves realitzades.  
- Carpeta `img/`: Conté les captures de pantalla utilitzades al document guia.

---

## Documents

Podeu consultar tots els documents fent clic al document corresponent:  
- A l’arxiu [solució](solució.md) podeu trobar la guia completa amb resultats i anàlisi de la pràctica.

[Tornar pàgina del projecte](../README.md)

