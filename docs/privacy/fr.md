# Politique de confidentialité de Print3D Manager

**Dernière mise à jour : 25 août 2026**

_Ceci est une traduction de la version canonique en espagnol, [PRIVACY_POLICY.md](../../PRIVACY_POLICY.md). En cas de divergence, la version espagnole prévaut._

Cette politique explique quelles données Print3D Manager (« l'application ») traite, dans quel but, sur quelle base légale, pendant combien de temps elles sont conservées, et quels choix s'offrent à vous. Elle est rédigée pour décrire exactement ce que fait l'application aujourd'hui, et non des fonctionnalités futures.

## 1. Qui traite les données

Print3D Manager est une application développée de manière indépendante pour la gestion d'un atelier d'impression 3D (coûts, imprimantes, matériaux, projets, clients, devis et factures).

Contact : **zhop3dlab@gmail.com**.

## 2. Principe général : l'application est locale par défaut

Toutes les informations que vous saisissez (imprimantes, matériaux, projets, clients, devis, factures, inventaire) sont enregistrées **sur votre propre appareil** par défaut. Vous n'avez besoin ni de créer un compte ni d'avoir une connexion internet pour utiliser l'application avec toutes ses fonctionnalités principales.

Aucune donnée de votre activité n'est envoyée à nos serveurs ni à des tiers, sauf si vous disposez du plan Business et activez volontairement la synchronisation avec le cloud (voir section 3), ou pendant l'affichage d'une publicité (voir section 6).

## 3. Compte et synchronisation avec le cloud (plan Business, facultatif)

Si vous disposez du plan Business et décidez de créer un compte (avec e-mail et mot de passe, ou avec votre compte Google) pour également enregistrer vos données dans le cloud et les utiliser sur plusieurs appareils :

- **Données du compte** : adresse e-mail et, si vous utilisez Google, le nom et la photo de profil associés à ce compte Google.
- **Données de votre activité** : si vous activez la synchronisation, une copie de vos projets, clients, imprimantes, matériaux, devis et factures est enregistrée dans une base de données cloud (Google Firebase/Firestore), liée uniquement à votre compte et à votre espace de travail. Personne en dehors de votre compte ne peut accéder à ces données.
- Vous pouvez cesser d'utiliser le cloud à tout moment et faire fonctionner à nouveau l'application uniquement en local.
- Vous pouvez **supprimer votre compte et toutes les données cloud associées** à tout moment depuis l'application, dans **Plus → Compte → Supprimer le compte et les données**. Cette action est permanente et immédiate.

Nous utilisons Google Firebase (Authentication et Firestore) comme fournisseur d'infrastructure pour le compte et le cloud. Google agit en tant que sous-traitant de ces données selon ses propres conditions : <https://firebase.google.com/support/privacy>.

**Base légale** : nous traitons ces données car cela est nécessaire pour vous fournir le service que vous avez souscrit (exécution d'un contrat/utilisation du plan Business) et, pour l'e-mail de contact, avec votre consentement lors de la création du compte.

**Conservation** : tant que vous maintenez votre compte actif. Si vous le supprimez (Plus → Compte → Supprimer le compte et les données), les données dans le cloud sont supprimées immédiatement. Si vous ne créez jamais de compte, aucune donnée n'est générée dans le cloud.

**Transferts internationaux** : l'infrastructure de Google Firebase peut traiter et stocker des données dans des centres de données situés en dehors de votre pays, y compris en dehors de l'Espace économique européen. Google offre des garanties conformes au RGPD (clauses contractuelles types) pour ces transferts — plus de détails au lien ci-dessus.

## 4. Si vous utilisez l'application pour gérer les données de vos propres clients

Si vous enregistrez dans l'application des données de vos clients (nom, adresse, identifiant fiscal, e-mail...) pour des devis et factures, **vous êtes le responsable du traitement de ces données** vis-à-vis de vos propres clients — de la même manière que si vous les gériez dans un tableur ou un logiciel de facturation. Print3D Manager est uniquement l'outil que vous utilisez pour les enregistrer (et, si vous disposez du plan Business avec la synchronisation activée, le sous-traitant pour le cloud).

Cela signifie que c'est à vous de vous assurer de disposer d'une base légale adéquate pour traiter les données de vos clients (généralement, votre relation commerciale/contractuelle avec eux) et de répondre à leurs propres demandes d'accès, de rectification ou de suppression si elles vous sont adressées directement.

## 5. Données qui ne quittent jamais votre appareil

- **Fichiers G-code** : si vous utilisez l'analyseur de G-code, le fichier est lu et analysé entièrement sur votre appareil. Le contenu du fichier n'est jamais téléchargé sur internet ni partagé avec qui que ce soit ; vous seul voyez les données extraites (temps estimé, grammes, températures).
- **Sauvegardes locales** : exporter/importer vos données dans un fichier JSON (plans Pro et Business) est une opération entièrement locale — le fichier est enregistré où vous le décidez (par exemple, en le partageant vous-même par e-mail ou en l'enregistrant dans votre propre stockage).
- **PDF de devis et factures** : générés sur votre appareil. Les partager ou les télécharger est une action explicite de votre part ; l'application ne les envoie à aucun serveur qui nous appartienne.

## 6. Publicité

L'application affiche des publicités via **Google AdMob** aux utilisateurs du plan gratuit. AdMob peut collecter des identifiants publicitaires de votre appareil pour afficher des publicités (personnalisées ou non, selon les paramètres de confidentialité de votre système d'exploitation) et mesurer leurs performances. Ce traitement est effectué par Google conformément à sa propre politique de confidentialité : <https://policies.google.com/privacy> et à sa politique spécifique à AdMob : <https://support.google.com/admob/answer/6128543>.

**Base légale** : consentement (géré via les paramètres de confidentialité de votre appareil/Google) et intérêt légitime à financer l'application gratuite par la publicité.

Les utilisateurs des plans payants (Pro et Business) ne voient pas de publicités.

## 7. Ce que nous NE faisons PAS

- Nous ne vendons vos données à personne.
- Nous n'accédons pas au contenu de vos projets, clients ou factures, sauf si vous disposez du plan Business et activez expressément la synchronisation cloud — et même dans ce cas, nous ne les consultons pas manuellement.
- Nous n'utilisons pas vos données professionnelles pour entraîner des modèles d'intelligence artificielle.
- Nous ne demandons pas les autorisations caméra, contacts, localisation ou microphone — l'application n'en a pas besoin et ne les demande pas.

## 8. Vos droits

Vous avez le droit d'accéder à vos données, de les rectifier, de les supprimer, de limiter leur traitement, de vous y opposer et d'en demander la portabilité. En pratique, depuis l'application vous pouvez :

- **Voir** combien de données vous avez enregistrées localement et dans le cloud (Plus → Compte).
- **Télécharger** une copie de vos données dans un fichier JSON (plans Pro et Business, Plus → Données).
- **Supprimer** votre compte et toutes les données cloud associées depuis l'application (Plus → Compte → Supprimer le compte et les données).
- **Désinstaller l'application** à tout moment, ce qui supprime toutes les données enregistrées localement sur votre appareil.

Si vous avez besoin d'aide concernant l'un de ces droits, ou si vous avez des questions sur cette politique, contactez **zhop3dlab@gmail.com**.

Si vous estimez que votre demande n'a pas été traitée correctement, vous avez le droit de déposer une réclamation auprès de l'autorité de contrôle de la protection des données de votre pays (en Espagne, l'**Agencia Española de Protección de Datos**, <https://www.aepd.es>).

## 9. Mineurs

L'application ne s'adresse pas aux mineurs et nous ne collectons pas sciemment de données les concernant.

## 10. Modifications de cette politique

Si cette politique change de manière significative, la date en haut du document sera mise à jour. L'utilisation continue de l'application après un changement implique l'acceptation de la politique mise à jour.
