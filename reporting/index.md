---
title: "Politique de signalement d'incident de cybersécurité - Reporting Policy for Security Incident"
---

## [FR] Préambule

Ce site est géré par le CSIRT de l'Assurance Maladie.

L'Assurance Maladie et les autres branches de la Sécurité Sociale incluant Caisse d'Allocations Familiales (CNAF), Assurance Retraite (CNAV), le Recouvrement (URSSAF) et la Mutuelle Sociale Agricole (MSA) ont mis en place un CERT sectoriel pour mutualiser les moyens et partager les informations entre elles. Ce CERT peut-être contacté pour transmettre des signalements aux autres branches.

Voici la fiche d'information du CERT Social :
- Nom : CERT Social
- Adresse : [cert@cert-social.fr](mailto:cert@cert-social.fr)
- Lettre de mission : [RFC2350](https://www.assurance-maladie.ameli.fr/pages-d-informations-legales/cert-social)
- Empreinte de clé PGP : B577 1DC3 67A7 D447 B27A 21B0 43F6 EC35 41EF 887E (ID : [0x43F6EC3541EF887E](https://pgp.circl.lu/pks/lookup?op=get&search=0x43f6ec3541ef887e))
- Serveur de clé principal : https://pgp.circl.lu

Le CSIRT de l'Assurance Maladie prend en charge tous les problèmes de sécurité liée à son infrastructure et ses services. Il utilise la même identité GPG. L'adresse historique csirt.cnam@assurance-maladie.fr doit être privilégiée pour les échanges inter-CERT.

Voici la fiche d'information du CSIRT Assurance Maladie :
- Nom : CSIRT Assurance Maladie 
- Adresse : [csirt@assurance-maladie.fr](mailto:csirt@assurance-maladie.fr)
- Lettre de mission : [RFC2350](https://www.assurance-maladie.ameli.fr/pages-d-informations-legales/csirt-assurance-maladie-rfc2350)
- Empreinte de clé PGP : B577 1DC3 67A7 D447 B27A 21B0 43F6 EC35 41EF 887E (ID : [0x43F6EC3541EF887E](https://pgp.circl.lu/pks/lookup?op=get&search=0x43f6ec3541ef887e))
- Serveur de clé principal : [https://pgp.circl.lu](https://pgp.circl.lu)

L'adresse histortique abuse@assurance-maladie.fr ne sera plus consultée pour le signalement de problèmes de sécurité et est maintenant dédiée aux relations avec les hébergeurs et registrars.

## [FR] Politique de signalement de vulnérabilités sur le périmètre de l'Assurance Maladie

**> Comment signaler une vulnérabilité :** 

Si vous trouvez (ou suspectez d'avoir découvert) une vulnérabilité sur une application, un site ou un service de l'Assurance Maladie ou l'exposition d'un service indésirable sur le réseau de l'Assurance Maladie, merci de suivre les instructions ci-dessous 
vers l'adresse csirt@assurance-maladie.fr :
- envoyer les détails suivants :
  - site web ou service impacté
  - étapes pour reproduire la vulnérabilité ou indications sur le service indésirable exposé avec l'adresse et le port
  - impact estimé
 
L'Assurance Maladie gère un programme de bug bounty depuis la plateforme YesWeHack sur le périmètre :
- "Compte Ameli" web sur assure.ameli.fr et aussi ameliconnect.ameli.fr
- "Compte Ameli" sur l'application services.ameli.moncompte.mobi, sur le Google Play Store (fr.cnamts.it.activity) et sur l'Apple Store (compte-ameli)
- "AmeliPRO" sur espacepro.ameli.fr, authps-espacepro.ameli.fr, authcps-espacepro.ameli.fr, paiements2.ameli.fr, convention2.ameli.fr, conventionpharmaciens.ameli.fr, conventionauxiliaires.ameli.fr, installation-medecin.ameli.fr, installation-kine.ameli.fr, installation-idel.ameli.fr

Si vous êtes participant à ce bug bounty, veuillez remonter vos signalements à travers celle-ci.

**> Divulgation responsable :** 
- Si des données personnelles d'assurés ou des informations mettant en danger immédiat la continuité d'un de nos services doivent être mentionnées dans votre rapport, merci de bien chiffrer vos informations avec notre [clé GnuPG](https://pgp.circl.lu/pks/lookup?op=get&search=0x43f6ec3541ef887e). Si vous ne possédez pas de moyen de chiffrer votre message en PGP, vous pouvez prendre contact avec nous sur notre adresse de contact ou par téléphone pour convenir d'un moyen de communication sûr. Nous reviendrons rapidement vers vous. 
- Merci de ne rendre publique **aucune information** concernant votre signalement ni de les partager avec un tiers (responsible disclosure) tant que nous n'avons pas corrigé ou atténué le problème remonté s'il y a lieu. 

**> Périmètre des services couverts par cette politique de signalement :** 
- `*.ameli.fr`
- `*.dmp.fr` (domaine historique du Dossier Médical Partagé maintenant intégré dans MonEspaceSanté)
- `*.assurance-maladie.fr`
-  `*.cnamts.fr` (domaine historique remplacé par assurance-maladie.fr)
- et tout autre service en lien avec un organisme de l'Assurance Maladie (CPAM, CRAMIF, DRSM....)

- Toute ressource gérée par AS48703 Caisse Nationale d'Assurance Maladie

**> Seront considérés comme étant hors périmètre :** 
- Clickjacking sur des pages sans fonctionnalités sensibles ou sans scénario,
- Cross-Site Request Forgery (CSRF) sur des formulaires non authentifiés ou non sensibles,
- Injection CSV sans scénario réel,
- Spoofing de contenu et injection de texte ne démontrant pas de vecteur d'attaque/ne permettant pas la modification de HTML/CSS,
- Vulnérabilités affectant des utilisateurs utilisant des navigateurs non à jour (inférieurs à 2 versions stables après la dernière version stable),
- Vulnérabilités nécessitant un comportement une interaction peu probable avec l'utilisateur.

**> Crédits :** [Merci à toutes les personnes](/abuse/thanks/) ayant fait des signalements responsables.

## [EN] Read first

This site is managed by the computer security incident response team of Assurance Maladie.
"Assurance Maladie" is the French Public national healthcare insurance for nearly all french people. The Assurance Maladie is under the authority of the Ministry of Health and Solidarity and is a part of the [Social Security](https://www.securite-sociale.fr/accueil) organization.

The "Assurance Maladie" and the other branches of the Social Security have created a sectoral CERT to mutualize their means and share informations between themselves. The "Caisse d'Allocations Familiales" also known as CAF (family welfare), "Assurance Retraite" also less known as CAV (public retirement), le "Recouvrement" also known as URSSAF (handling of the financement of all social contributions) and the "Mutuelle Sociale Agricole" also known as MSA (social security for farmers) belong to the "CERT Social". This CERT can be contacted to transmit security problems to the others branches.

Contact card of the CERT Social :
- Name : CERT Social
- E-mail address : [cert@cert-social.fr](mailto:cert@cert-social.fr)
- Policy agreement : [RFC2350](https://assurance-maladie.ameli.fr/sites/default/files/cert-social-frc2350-v2_assurance-maladie.pdf)
- PGP fingerprint : B577 1DC3 67A7 D447 B27A 21B0 43F6 EC35 41EF 887E (ID : [0xB49594E2C5EBE134](https://pgp.circl.lu/pks/lookup?op=get&search=0x43f6ec3541ef887e))
- Main key server : https://pgp.circl.lu

The Assurance Maladie CSIRT handles every security problems related to the Assurance Maladie infrastructure and services. It uses the same GPG identity. The historic address csirt.cnam@assurance-maladie.fr shall be used only for inter-CERT exchanges.

Contact card of the Assurance Maladie CSIRT :
- Name : Assurance Maladie CSIRT
- E-mail address : [csirt@assurance-maladie.fr](mailto:csirt@assurance-maladie.fr)
- Policy agreement : [RFC2350](https://www.assurance-maladie.ameli.fr/pages-d-informations-legales/csirt-assurance-maladie-rfc2350)
- PGP fingerprint : B577 1DC3 67A7 D447 B27A 21B0 43F6 EC35 41EF 887E (ID : [0x43F6EC3541EF887E](https://pgp.circl.lu/pks/lookup?op=get&search=0x43f6ec3541ef887e))
- Main key server : https://pgp.circl.lu

The e-mail address abuse@assurance-maladie.fr will cease to be monitored for security purposes and is now reserved for communications with the hosters and registrars.

## [EN] Vulnerability reporting policy 

**> How-to report:**

If you have found (or suspect the existence of) a security vulnerability on one of our site, application or services or an insecure exposition on our network follow the steps below to the address csirt@assurance-maladie.fr : 

- send the following details :
  - impacted website/service
  - steps to reproduce or informations on the exposed service
  - impacts estimated

The "Assurance Maladie" manages a bug bounty program through the Yes We Hack platform on the following perimeter :
- "Compte Ameli" portal on assure.ameli.fr and also ameliconnect.ameli.fr
- "Compte Ameli" mobile app on services.ameli.moncompte.mobi, on the Google Play Store (fr.cnamts.it.activity) and on the Apple Store (compte-ameli)
- "AmeliPRO" on espacepro.ameli.fr, authps-espacepro.ameli.fr, authcps-espacepro.ameli.fr, paiements2.ameli.fr, convention2.ameli.fr, conventionpharmaciens.ameli.fr, conventionauxiliaires.ameli.fr, installation-medecin.ameli.fr, installation-kine.ameli.fr, installation-idel.ameli.fr

If you're a part of this bug bounty, please send your vulnerability disclosure through it.

**> Responsible disclosure:** 
- If personal data of insured people or informations putting in immediate danger the well-being of one of our services must be mentionned in your report, please, be sure of encrypting these informations with our [GPG key](https://pgp.circl.lu/pks/lookup?op=get&search=0x43f6ec3541ef887e). If you do not have a way of doing that, you can get in touch with us with our contact address or by our phone land line to set a secure way of transmission. We will come back to you very soon.
- Do not disclose **any information** about the incident nor share anything about it with anyone before we were able to patch or mitigate the vulnerabity. Thanks.

**> Scope of the services covered by this reporting policy:** 
- `*.ameli.fr`
- `*.dmp.fr` (former domain of the Dossier Médical Partagé now handled by MonEspaceSante.fr)
- `*.assurance-maladie.fr`
-  `*.cnamts.fr` (former main domain replaced by assurance-maladie.fr)
- and any other service related to "Assurance Maladie" organization (regional or departemental organism like CPAM, CRAMIF, DRSM...).

Any resource behind AS48703 Caisse Nationale d'Assurance Maladie

**> The following will be considered out of scope :** 
- Clickjacking on pages with no sensitive actions or without scenario,
- Cross-Site Request Forgery (CSRF) on unauthenticated forms or forms with no sensitive actions,
- Comma Separated Values (CSV) injection without demonstrating a vulnerability,
- Content spoofing and text injection issues without showing an attack vector/without being able to modify HTML/CSS,
- Vulnerabilities only affecting users of outdated or unpatched browsers (Less than 2 stable versions behind the latest released stable version),
- Issues that require unlikely user interaction.

**> Acknowledgments:** [thank to all reporters](/abuse/thanks/) for their responsible disclosures.
