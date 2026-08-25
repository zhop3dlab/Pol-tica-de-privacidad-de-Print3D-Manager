# Política de privacitat de Print3D Manager

**Última actualització: 25 d'agost de 2026**

_Aquesta és una traducció de la versió canònica en castellà, [PRIVACY_POLICY.md](../../PRIVACY_POLICY.md). En cas de discrepància, preval la versió en castellà._

Aquesta política explica quines dades tracta Print3D Manager ("l'app"), amb quina finalitat, amb quina base legal, quant de temps es conserven, i quines opcions tens. Està escrita per descriure exactament el que fa l'app avui, no funcions futures.

## 1. Qui tracta les dades

Print3D Manager és una app desenvolupada de manera independent per a la gestió de tallers d'impressió 3D (costos, impressores, materials, projectes, clients, pressupostos i factures).

Contacte: **zhop3dlab@gmail.com**.

## 2. Principi general: l'app és local per defecte

Tota la informació que introdueixes (impressores, materials, projectes, clients, pressupostos, factures, inventari) es guarda **al teu propi dispositiu** de manera predeterminada. No necessites crear un compte ni tenir connexió a internet per fer servir l'app amb totes les seves funcions principals.

Cap dada del teu negoci s'envia als nostres servidors ni a tercers llevat que tinguis el pla Business i activis voluntàriament la sincronització amb el núvol (vegeu secció 3), o mentre es mostra un anunci (vegeu secció 6).

## 3. Compte i sincronització amb el núvol (pla Business, opcional)

Si tens el pla Business i decideixes crear un compte (amb correu i contrasenya, o amb el teu compte de Google) per guardar les teves dades també al núvol i fer-les servir en més d'un dispositiu:

- **Dades del compte**: adreça de correu i, si fas servir Google, el nom i la imatge de perfil associats a aquest compte de Google.
- **Dades del teu negoci**: si actives la sincronització, es guarda una còpia dels teus projectes, clients, impressores, materials, pressupostos i factures en una base de dades al núvol (Google Firebase/Firestore), associada únicament al teu compte i al teu espai de treball. Ningú fora del teu compte pot accedir a aquestes dades.
- Pots deixar de fer servir el núvol en qualsevol moment i tornar a fer que l'app funcioni només en local.
- Pots **eliminar el teu compte i totes les dades associades al núvol** en qualsevol moment des de la mateixa app, a **Més → Compte → Eliminar compte i dades**. Aquesta acció és permanent i immediata.

Fem servir Google Firebase (Authentication i Firestore) com a proveïdor d'infraestructura per al compte i el núvol. Google actua com a encarregat del tractament d'aquestes dades segons les seves pròpies condicions: <https://firebase.google.com/support/privacy>.

**Base legal**: tractem aquestes dades perquè és necessari per prestar-te el servei que has contractat (execució d'un contracte/relació d'ús del pla Business) i, en el cas del correu de contacte, amb el teu consentiment en crear el compte.

**Conservació**: mentre mantinguis el teu compte actiu. Si l'elimines (Més → Compte → Eliminar compte i dades), les dades al núvol s'esborren immediatament. Si mai crees un compte, no es genera cap dada al núvol.

**Transferències internacionals**: la infraestructura de Google Firebase pot processar i emmagatzemar dades en centres de dades fora del teu país, incloent-hi fora de l'Espai Econòmic Europeu. Google ofereix garanties d'acord amb el RGPD (clàusules contractuals tipus) per a aquestes transferències — més detall a l'enllaç anterior.

## 4. Si fas servir l'app per gestionar dades dels teus propis clients

Si guardes a l'app dades dels teus clients (nom, adreça, identificació fiscal, correu...) per a pressupostos i factures, **tu ets el responsable del tractament d'aquestes dades** davant dels teus propis clients — igual que si les portessis en un full de càlcul o un programa de facturació. Print3D Manager és únicament l'eina que fas servir per guardar-les (i, si tens el pla Business amb la sincronització activada, l'encarregat del tractament al núvol).

Això vol dir que ets tu qui ha d'assegurar-se de tenir una base legal adequada per tractar les dades dels teus clients (normalment, la relació comercial/contractual amb ells) i d'atendre les seves pròpies sol·licituds d'accés, rectificació o eliminació si te les fan directament a tu.

## 5. Dades que mai surten del teu dispositiu

- **Fitxers G-code**: si fas servir l'analitzador de G-code, el fitxer es llegeix i s'analitza íntegrament al teu dispositiu. El contingut del fitxer mai es puja a internet ni es comparteix amb ningú; només tu veus les dades extretes (temps estimat, grams, temperatures).
- **Còpies de seguretat locals**: exportar/importar les teves dades en un fitxer JSON (plans Pro i Business) és una operació completament local — el fitxer es guarda on tu decideixis (per exemple, compartint-lo tu mateix per correu o guardant-lo al teu emmagatzematge).
- **PDFs de pressupostos i factures**: es generen al teu dispositiu. Compartir-los o descarregar-los és una acció teva explícita; l'app no els envia a cap servidor propi.

## 6. Publicitat

L'app mostra anuncis mitjançant **Google AdMob** als usuaris del pla gratuït. AdMob pot recollir identificadors de publicitat del teu dispositiu per mostrar anuncis (personalitzats o no, segons la configuració de privacitat del teu sistema operatiu) i mesurar-ne el rendiment. Aquest tractament el realitza Google d'acord amb la seva pròpia política de privacitat: <https://policies.google.com/privacy> i la seva política específica per a AdMob: <https://support.google.com/admob/answer/6128543>.

**Base legal**: consentiment (gestionat a través de la configuració de privacitat del teu dispositiu/Google) i interès legítim a finançar l'app gratuïta mitjançant publicitat.

Els usuaris dels plans de pagament (Pro i Business) no veuen anuncis.

## 7. Què NO fem

- No venem les teves dades a ningú.
- No accedim al contingut dels teus projectes, clients o factures llevat que tinguis el pla Business i activis expressament la sincronització al núvol, i ni tan sols aleshores les revisem manualment.
- No fem servir les teves dades de negoci per entrenar models d'intel·ligència artificial.
- No demanem permisos de càmera, contactes, ubicació ni micròfon — l'app no els necessita i no els sol·licita.

## 8. Els teus drets

Tens dret a accedir, rectificar, eliminar, limitar el tractament, oposar-te i sol·licitar la portabilitat de les teves dades. A la pràctica, des de la mateixa app pots:

- **Veure** quantes dades tens guardades localment i al núvol (Més → Compte).
- **Descarregar** una còpia de les teves dades en un fitxer JSON (plans Pro i Business, Més → Dades).
- **Eliminar** el teu compte i totes les dades associades al núvol des de la mateixa app (Més → Compte → Eliminar compte i dades).
- **Desinstal·lar l'app** en qualsevol moment, cosa que elimina totes les dades guardades localment al teu dispositiu.

Si necessites ajuda amb qualsevol d'aquests drets, o tens algun dubte sobre aquesta política, contacta amb **zhop3dlab@gmail.com**.

Si consideres que no hem atès correctament la teva sol·licitud, tens dret a presentar una reclamació davant l'autoritat de control de protecció de dades del teu país (a Espanya, l'**Agència Espanyola de Protecció de Dades**, <https://www.aepd.es>).

## 9. Menors d'edat

L'app no està dirigida a menors d'edat i no recollim conscientment dades de menors.

## 10. Canvis en aquesta política

Si aquesta política canvia de manera rellevant, s'actualitzarà la data al principi del document. L'ús continuat de l'app després d'un canvi implica l'acceptació de la política actualitzada.
