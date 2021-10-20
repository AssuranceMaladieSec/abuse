---
title: "Politique de signalement de vulnerabilites - Reporting Policy"
---

## [FR] Politique de signalement de vulnérabilités

**> Comment signaler une vulnérabilité :** 

Si vous trouvez (ou suspectez d'avoir découvert) une vulnérabilité sécurité ou de vie privée sur un site ou un service de l'Assurance Maladie, merci de suivre les instructions ci-dessous :

- envoyer les détails suivants à [abuse@assurance-maladie.fr](mailto:abuse@assurance-maladie.fr) :
  - site web ou service impacté
  - étapes pour reproduire l'incident
  - impact estimé 

- optionnel : si vous souhaitez et savez envoyer un email chiffré, voici notre [clé GnuPG](https://github.com/AssuranceMaladieSec/abuse/blob/master/abuse-gpg-public-key.txt).

**> Divulgation responsable :** 
- Nous reviendrons rapidement vers vous. 
- Merci de ne rendre publique **aucune information** concernant votre signalement ni de les partager avec un tiers tant que nous n'avons pas corrigé ou atténuer le problème remonté s'il y a lieu. 

**> Périmètre des services couverts par cette politique de signalement :** 
- `*.ameli.fr`,
- `*.dmp.fr`,
- `*.assurance-maladie.fr`,
-  `*.cnamts.fr`
- et tout autre service en lien avec l'Assurance Maladie.

**> Seront considérés comme étant hors périmètre :** 
- Clickjacking sur des pages sans fonctionnalités sensibles ou sans scénario,
- Cross-Site Request Forgery (CSRF) sur des formulaires non authentifiés ou non sensibles,
- Injection CSV sans scénario réel,
- Spoofing de contenu et injection de texte ne démontrant pas de vecteur d'attaque/ne permettant pas la modification de HTML/CSS,
- Manquements aux bonnes pratiques de sécurité concernant les mails (entrées SPF/DKIM/DMARC invalides, incomplétes ou manquantes),
- Vulnérabilités affectant des utilisateurs utilisant des navigateurs non à jour. (inférieurs à 2 versions stables aprés la derniére version stable),
- Vulnérabilités nécessitant un comportement une interaction peu probable avec l'utilisateur.

**> Crédits :** [Merci à toutes les personnes](/abuse/thanks/) ayant fait des signalements responsables.

## [EN] Vulnerability reporting policy 

**> How-to report:**

If you have found (or suspect the existence of) a privacy or security vulnerability on one of our services, follow the steps below: 

- send the following details to [abuse@assurance-maladie.fr](mailto:abuse@assurance-maladie.fr):
  - impacted website/service
  - steps to reproduce
  - impacts you estimate 

- optional: if you want and are able to send encrypted email, find there our [GnuPG key](https://github.com/AssuranceMaladieSec/abuse/blob/master/abuse-gpg-public-key.txt).

**> Responsible disclosure:** 
- We will come back to you very soon. 
- Do not disclose **any information** about the incident nor share anything about it with anyone before we were able to patch or mitigate the vulnerabity. Thanks.

**> Scope of the services covered by this reporting policy:** 
- `*.ameli.fr`, 
- `*.dmp.fr`, 
- `*.assurance-maladie.fr`,
-  `*.cnamts.fr`
- and any other service related to French Assurance Maladie organization.

**> The following will be considered out of scope :** 
- Clickjacking on pages with no sensitive actions or without scenario,
- Cross-Site Request Forgery (CSRF) on unauthenticated forms or forms with no sensitive actions,
- Comma Separated Values (CSV) injection without demonstrating a vulnerability,
- Content spoofing and text injection issues without showing an attack vector/without being able to modify HTML/CSS,
- Missing email best practices (Invalid, incomplete or missing SPF/DKIM/DMARC records, etc.),
- Vulnerabilities only affecting users of outdated or unpatched browsers (Less than 2 stable versions behind the latest released stable version),
- Issues that require unlikely user interaction.

**> Acknowledgments:** [thank to all reporters](/abuse/thanks/) for their responsible disclosures.
