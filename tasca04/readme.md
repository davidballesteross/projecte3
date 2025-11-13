# T04: Serveis de Directori. LDAP

## Descripció de la tasca

Innovatech, una empresa tecnològica en expansió, està experimentant problemes en la gestió dels seus usuaris i dels diferents sistemes interns.  
Actualment, cada servei (servidor de fitxers, plataforma documental, etc.) manté la seva pròpia base de dades d’usuaris, i a més cada equip client utilitza autenticació local.

Aquesta situació genera diversos problemes importants:

- Ineficiència operativa: en incorporar o donar de baixa un empleat, cal intervenir en diversos sistemes manualment.
- Risc de seguretat: molts usuaris tendeixen a reutilitzar contrasenyes per no haver de recordar-ne tantes.
- Escalabilitat limitada: la incorporació de nous serveis fa que aquest model esdevingui difícil de mantenir.

Davant d’aquest escenari, el CEO ha decidit implementar un sistema d’autenticació centralitzat basat en OpenLDAP, aprofitant que tota la infraestructura utilitza GNU/Linux.

## Objectius del projecte

La tasca consisteix a desplegar i configurar un servidor OpenLDAP en un sistema Linux.  
Els objectius principals són:

1. Instal·lar el servei OpenLDAP.
2. Configurar el domini base del directori.
3. Crear la jerarquia d’unitats organitzatives (OUs).
4. Afegir usuaris i grups al directori.
5. Configurar un equip client perquè utilitzi el directori per autenticar-se.

## Fases del projecte

### Fase 1: Instal·lació i configuració del servidor
- Instal·lació d’OpenLDAP i paquets relacionats.
- Definició del domini base i estructura inicial.
- Verificació del correcte funcionament del servei.

### Fase 2: Creació de la jerarquia i integració d’usuaris
- Creació de les unitats organitzatives (OUs) necessàries.
- Afegir usuaris i grups a l'estructura LDAP.
- Validació de la informació mitjançant consultes ldapsearch.

### Fase 3: Integració amb clients Linux
- Configuració del client Linux per utilitzar LDAP durant l’autenticació.
- Proves d’accés amb usuaris del directori.
- Documentació de resultats i incidències observades.

## Estructura de carpetes

Dins la carpeta `tasca04` es troben els següents fitxers:

- `solucio.md`: Document tècnic amb la guia completa de configuració d’OpenLDAP.
- Carpeta `img/`: Conté les captures de pantalla i esquemes utilitzats.

## Documents

Podeu consultar tots els documents fent clic al document corresponent:
- Al arxiu [solucio](solucio.md) podeu trobar la guia.

