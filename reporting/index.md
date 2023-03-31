---
title: "Politique de signalement d'incident de cybersécurité - Reporting Policy for Security Incident"
---

## [FR] Préambule

Ce site est géré par l'équipe Sécurité de l'Assurance Maladie et son CERT.

L'Assurance Maladie et les autres branches de la Sécurité Sociale incluant Caisse d'Allocations Familiales (CNAF), Assurance Retraite (CNAV), le Recouvrement (URSSAF) et la Mutuelle Sociale Agricole (MSA) ont mis en place un CERT pour la mutualisation de ses moyens de réponse aux incidents de sécurité. Cet organisme peut-être contacté pour tout problème de sécurité en relation avec la Sécurité Sociale.

Voici la fiche d'information du CERT Social :
- Nom : CERT Social
- Adresse : cert@cert-social.fr
- Lettre de mission : [RFC2350](https://assurancemaladiesec.github.io/abuse/CERTSocial-RFC2350.pdf)
- Empreinte de clé PGP : 7EC6 D0BE 7288 277C DF2A 42E2 B495 94E2 C5EB E134 (Short ID : [0xB49594E2C5EBE134](https://assurancemaladiesec.github.io/abuse/certsocial-gpg-public-key.txt))
- Serveur de clé principal : https://pgp.circl.lu
- Numéro de téléphone : +33 (0)2 52 09 20 06 (de 9h à 18h)

L'adresse abuse@assurance-maladie.fr continuera d'être consultée à des fins de continuité de service pour le signalement de problèmes de sécurité lié uniquement à l'Assurance Maladie et pour les relations avec les hébergeurs.

## [FR] Politique de signalement de vulnérabilités sur le périmètre de l'Assurance Maladie

**> Comment signaler une vulnérabilité :** 

Si vous trouvez (ou suspectez d'avoir découvert) une vulnérabilité sécurité ou de vie privée sur un site ou un service de l'Assurance Maladie, merci de suivre les instructions ci-dessous :

- envoyer les détails suivants à [abuse@assurance-maladie.fr](mailto:abuse@assurance-maladie.fr) :
  - site web ou service impacté
  - étapes pour reproduire l'incident
  - impact estimé

**> Divulgation responsable :** 
- Si des données personnelles d'assurés ou des informations mettant en danger immédiat la continuité d'un de nos services doivent être mentionnées dans votre rapport, merci de bien chiffrer vos informations avec notre [clé GnuPG](https://assurancemaladiesec.github.io/abuse//abuse-gpg-public-key.txt). Si vous ne possédez pas de moyen de chiffrer votre message en PGP, vous pouvez prendre contact avec nous sur notre adresse de contact ou par téléphone pour convenir d'un moyen de communication sûr.  
- Nous reviendrons rapidement vers vous. 
- Merci de ne rendre publique **aucune information** concernant votre signalement ni de les partager avec un tiers tant que nous n'avons pas corrigé ou atténuer le problème remonté s'il y a lieu. 

**> Périmètre des services couverts par cette politique de signalement :** 
- `*.ameli.fr`,
- `*.dmp.fr`,
- `*.assurance-maladie.fr`,
-  `*.cnamts.fr`
- et tout autre service en lien avec un organisme de l'Assurance Maladie (CPAM, CRAMIF, DRSM....).

**> Seront considérés comme étant hors périmètre :** 
- Clickjacking sur des pages sans fonctionnalités sensibles ou sans scénario,
- Cross-Site Request Forgery (CSRF) sur des formulaires non authentifiés ou non sensibles,
- Injection CSV sans scénario réel,
- Spoofing de contenu et injection de texte ne démontrant pas de vecteur d'attaque/ne permettant pas la modification de HTML/CSS,
- Manquements aux bonnes pratiques de sécurité concernant les mails (entrées SPF/DKIM/DMARC invalides, incomplétes ou manquantes),
- Vulnérabilités affectant des utilisateurs utilisant des navigateurs non à jour (inférieurs à 2 versions stables après la dernière version stable),
- Vulnérabilités nécessitant un comportement une interaction peu probable avec l'utilisateur.

**> Crédits :** [Merci à toutes les personnes](/abuse/thanks/) ayant fait des signalements responsables.

## [FR] Préambule

This site is managed by the security team of Assurance Maladie and its CERT.
"Assurance Maladie" is the French Public national healthcare insurance for the entire french population. It is related to the French State by the authority of the Ministry of Health and is a part of the [Social Security](https://www.securite-sociale.fr/accueil) organisation.

The "Assurance Maladie" and the other branches of the Social Security have mutualized their security response team under the name "CERT Social". The "Caisse d'Allocations Familiales" also known as CAF (family welfare), "Assurance Retraite" also less known as CAV (public retirement), le "Recouvrement" also known as URSSAF (handling of the financement of all social contributions) and the "Mutuelle Sociale Agricole" also known as MSA (social security for farmers) also belong to the "CERT Social". The following address can be used for every security problem related to the whole Social Security.

Here is a quick résumé of the CERT Social
- Name : CERT Social
- E-mail address : cert@cert-social.fr
- Policy agreement : [RFC2350](https://assurancemaladiesec.github.io/abuse/CERTSocial-RFC2350.pdf)
- PGP fingerprint : 7EC6 D0BE 7288 277C DF2A 42E2 B495 94E2 C5EB E134 (Short ID : [0xB49594E2C5EBE134](https://assurancemaladiesec.github.io/abuse/certsocial-gpg-public-key.txt))
- Main key server : https://pgp.circl.lu
- Phone number : +33 (0)2 52 09 20 06 (de 9h à 18h)

The e-mail address abuse@assurance-maladie.fr will continue to be monitored for security incident and vulnerability disclosure and for communications with the hosters and registrars.

## [EN] Vulnerability reporting policy 

**> How-to report:**

If you have found (or suspect the existence of) a privacy or security vulnerability on one of our services, follow the steps below: 

- send the following details to [abuse@assurance-maladie.fr](mailto:abuse@assurance-maladie.fr):
  - impacted website/service
  - steps to reproduce
  - impacts you estimate 

**> Responsible disclosure:** 
- If personal data of insured people or informations putting in immediat danger the well-being of one of our services must be mentionned in your report, please, be sure of encrypting these informations with our [GPG key](https://assurancemaladiesec.github.io/abuse/abuse-gpg-public-key.txt). If you do not have a way of doing that, you can get in touch with us with our contact address or by our phone land line to set a secure way of transmission.  
- We will come back to you very soon.
- Do not disclose **any information** about the incident nor share anything about it with anyone before we were able to patch or mitigate the vulnerabity. Thanks.

**> Scope of the services covered by this reporting policy:** 
- `*.ameli.fr`, 
- `*.dmp.fr`, 
- `*.assurance-maladie.fr`,
-  `*.cnamts.fr`
- and any other service related to "Assurance Maladie" organization (regional or departemental organism like CPAM, CRAMIF, DRSM...).

**> The following will be considered out of scope :** 
- Clickjacking on pages with no sensitive actions or without scenario,
- Cross-Site Request Forgery (CSRF) on unauthenticated forms or forms with no sensitive actions,
- Comma Separated Values (CSV) injection without demonstrating a vulnerability,
- Content spoofing and text injection issues without showing an attack vector/without being able to modify HTML/CSS,
- Missing email best practices (Invalid, incomplete or missing SPF/DKIM/DMARC records, etc.),
- Vulnerabilities only affecting users of outdated or unpatched browsers (Less than 2 stable versions behind the latest released stable version),
- Issues that require unlikely user interaction.

**> Acknowledgments:** [thank to all reporters](/abuse/thanks/) for their responsible disclosures.
