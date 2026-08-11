# Didier Martial ALLOU

**Bioinformaticien | Technicien informatique N1/N2 | Réseaux & systèmes | Microsoft 365 | Automatisation | Data & Health IT**

Montréal, Québec, Canada

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](VOTRE_LIEN_LINKEDIN)
[![CV](https://img.shields.io/badge/CV-Download-success)](LIEN_VERS_VOTRE_CV)
[![Portfolio](https://img.shields.io/badge/Portfolio-Projets-orange)](#projets-sélectionnés)
[![Email](https://img.shields.io/badge/Email-Contact-lightgrey)](mailto:VOTRE_EMAIL)

---

## À propos

Je suis diplômé d'une **maîtrise en bio-informatique de l'Université de Montréal**, avec un parcours antérieur en informatique, réseaux et télécommunications.

Mon profil se situe à l'intersection de trois domaines :

* **soutien informatique, systèmes et réseaux** ;
* **bio-informatique et analyse de données scientifiques** ;
* **automatisation et administration des environnements Microsoft**.

J'ai acquis une expérience pratique en soutien informatique auprès d'utilisateurs dans un environnement universitaire, notamment en diagnostic de problèmes **Wi-Fi, Ethernet, authentification, certificats, adresses IP, pilotes, téléphonie et postes de travail**.

Je développe actuellement mes compétences vers des fonctions de niveau intermédiaire en :

* administration Microsoft 365 ;
* Microsoft Entra ID ;
* Microsoft Intune ;
* PowerShell ;
* Windows Server et Active Directory ;
* réseaux TCP/IP, VLAN et routage ;
* cybersécurité opérationnelle ;
* administration Azure.

Mon objectif professionnel est d'évoluer vers des fonctions telles que **technicien informatique N2, technicien principal, administrateur de postes de travail, administrateur Microsoft 365 junior, technicien réseau intermédiaire ou analyste informatique junior**, tout en conservant une forte capacité à travailler dans les environnements scientifiques, universitaires et de santé.

---

# Projets sélectionnés

## Bio-informatique

### Cartographie *in silico* des régions de liaison HuR-like sur le pri-miR-128-1 humain

[Voir le projet](LIEN_PROJET_HUR_PRI_MIR128)

Projet réalisé dans le cadre de ma maîtrise en bio-informatique.

**Objectif :** identifier et prioriser des régions potentielles de liaison de la protéine HuR sur le pri-miR-128-1 humain à partir de motifs de liaison connus.

Principales composantes :

* analyse de **67 motifs HuR** ;
* détection d'occurrences exactes sur la séquence ;
* identification de régions enrichies ;
* analyse par fenêtres glissantes ;
* modèle de fond de Markov d'ordre 1 ;
* score composite normalisé ;
* visualisation du profil positionnel des motifs ;
* développement d'une application Web locale avec **FastAPI**.

**Technologies :**

`Python` `NumPy` `Matplotlib` `pyahocorasick` `FastAPI` `Regex` `JSON` `CSV`

**Résultats principaux :**

* 64 occurrences exactes détectées ;
* 11 motifs uniques ;
* deux régions enrichies principales identifiées ;
* pipeline reproductible pour l'analyse et la visualisation.

[Documentation](LIEN_DOCUMENTATION_HUR) ·
[Code](LIEN_CODE_HUR) ·
[Figures](LIEN_FIGURES_HUR) ·
[Rapport](LIEN_RAPPORT_HUR)

---

# Infrastructure, systèmes et soutien informatique

## IT Support N2 Troubleshooting Lab

[Voir le projet](LIEN_SUPPORT_N2)

Laboratoire consacré au diagnostic structuré d'incidents informatiques inspirés de situations réelles en entreprise.

Scénarios étudiés :

* poste connecté au Wi-Fi sans accès Internet ;
* problèmes DNS ;
* erreurs DHCP ;
* authentification ;
* profils Windows ;
* pilotes ;
* certificats ;
* lenteurs système ;
* problèmes de services ;
* connectivité applicative ;
* imprimantes ;
* accès aux ressources réseau.

Méthodologie appliquée :

`Symptôme → Portée → Hypothèses → Tests → Cause → Correction → Validation → Documentation`

**Outils :**

`PowerShell` `Windows Terminal` `Event Viewer` `ipconfig` `nslookup` `tracert` `ping` `Test-NetConnection` `Wireshark`

[Incidents documentés](LIEN_INCIDENTS) ·
[Base de connaissances](LIEN_KNOWLEDGE_BASE)

---

## Windows Server & Active Directory Lab

[Voir le projet](LIEN_ACTIVE_DIRECTORY)

Infrastructure Windows simulant une PME avec plusieurs services organisationnels.

**Compétences travaillées :**

* Windows Server ;
* Active Directory Domain Services ;
* utilisateurs et groupes ;
* unités organisationnelles ;
* stratégies de groupe ;
* DNS ;
* DHCP ;
* permissions NTFS ;
* partages réseau ;
* délégation ;
* journalisation ;
* dépannage de domaine.

Architecture prévue :

```text
                    Internet
                       |
                    Firewall
                       |
                 ----------------
                 |              |
             DC-WIN-01      SRV-FILES-01
          AD / DNS / DHCP     Files
                 |
          -----------------
          |               |
    CLIENT-W11-01    CLIENT-W11-02
```

[Architecture](LIEN_ARCHITECTURE_AD) ·
[Documentation](LIEN_DOCUMENTATION_AD) ·
[Incidents](LIEN_INCIDENTS_AD)

---

## PowerShell IT Operations Toolkit

[Voir le projet](LIEN_POWERSHELL)

Collection de scripts destinés à automatiser les tâches courantes d'administration informatique.

Scripts prévus ou développés :

* inventaire matériel et logiciel ;
* surveillance de l'espace disque ;
* état des services Windows ;
* création d'utilisateurs à partir d'un fichier CSV ;
* gestion des groupes ;
* comptes inactifs ;
* collecte des événements Windows ;
* tests de connectivité ;
* vérification DNS ;
* génération de rapports ;
* automatisation de tâches répétitives.

Chaque script est documenté avec :

* objectif ;
* prérequis ;
* paramètres ;
* exemples ;
* gestion des erreurs ;
* risques ;
* résultats attendus.

`PowerShell 7` `Active Directory` `Microsoft Graph` `CSV` `JSON`

---

# Microsoft 365 & Endpoint Management

## Microsoft 365 Administration Lab

[Voir le projet](LIEN_M365)

Laboratoire d'administration Microsoft 365 destiné à développer des compétences directement transférables en entreprise.

Compétences :

* gestion des utilisateurs ;
* licences ;
* groupes Microsoft 365 ;
* Exchange Online ;
* Teams ;
* OneDrive ;
* SharePoint ;
* boîtes partagées ;
* permissions ;
* intégrité des services ;
* diagnostic des problèmes utilisateurs.

---

## Microsoft Entra ID Lab

[Voir le projet](LIEN_ENTRA)

Projet consacré à la gestion moderne des identités et des accès.

Domaines étudiés :

* utilisateurs et groupes ;
* groupes dynamiques ;
* rôles administratifs ;
* MFA ;
* accès conditionnel ;
* invités ;
* journaux de connexion ;
* authentification ;
* principe du moindre privilège ;
* Zero Trust ;
* procédures d'arrivée et de départ des employés.

---

## Microsoft Intune — Modern Endpoint Management

[Voir le projet](LIEN_INTUNE)

Laboratoire consacré à l'administration moderne des appareils Windows.

Objectifs :

* enrôlement des appareils ;
* profils de configuration ;
* stratégies de conformité ;
* déploiement d'applications ;
* BitLocker ;
* Windows LAPS ;
* politiques de sécurité ;
* mises à jour Windows ;
* rapports ;
* diagnostic des erreurs Intune ;
* principes de Windows Autopilot.

Projet final prévu :

> Déploiement et administration simulés de 25 postes Windows dans une PME utilisant Microsoft Intune et Microsoft Entra ID.

---

# Réseaux

## Enterprise Network Lab

[Voir le projet](LIEN_NETWORK_LAB)

Architecture réseau simulée avec Cisco Packet Tracer.

Compétences :

* TCP/IP ;
* IPv4 ;
* subnetting ;
* VLAN ;
* trunking ;
* routage inter-VLAN ;
* routage statique ;
* OSPF ;
* DHCP ;
* DNS ;
* NAT/PAT ;
* ACL ;
* Wi-Fi ;
* sécurité des ports ;
* diagnostic réseau.

**Outils :**

`Cisco Packet Tracer` `Wireshark` `Cisco IOS` `PowerShell`

[Topologie](LIEN_TOPOLOGIE) ·
[Configurations](LIEN_CONFIG_RESEAU) ·
[Scénarios de dépannage](LIEN_TROUBLESHOOTING_RESEAU)

---

# Azure & Cloud

## Azure Administration Lab

[Voir le projet](LIEN_AZURE)

Environnement d'apprentissage consacré aux fondamentaux de l'administration Azure :

* groupes de ressources ;
* RBAC ;
* réseaux virtuels ;
* sous-réseaux ;
* machines virtuelles ;
* groupes de sécurité réseau ;
* stockage ;
* sauvegarde ;
* Azure Monitor ;
* gestion des coûts ;
* Microsoft Entra ID.

---

# Compétences techniques

## Systèmes

`Windows 10/11`
`Windows Server`
`macOS`
`Linux`

## Microsoft

`Microsoft 365`
`Microsoft Entra ID`
`Microsoft Intune`
`Exchange Online`
`Teams`
`SharePoint`
`OneDrive`

## Réseaux

`TCP/IP`
`DNS`
`DHCP`
`Wi-Fi`
`Ethernet`
`IPv4`
`VLAN`
`VPN`
`Routage`
`Diagnostic réseau`

## Administration & automatisation

`PowerShell`
`Git`
`GitHub`
`Microsoft Graph`
`Windows Terminal`

## Programmation & données

`Python`
`SQL`
`JSON`
`CSV`
`Regex`

## Bio-informatique

`Analyse de séquences`
`Recherche de motifs`
`Analyse statistique`
`Visualisation scientifique`
`Pipelines reproductibles`

---

# Expérience technique

## Assistant technique informatique — Université de Montréal

Soutien informatique auprès d'une population d'environ **750 résidents**.

Principales interventions :

* diagnostic Wi-Fi et Ethernet ;
* problèmes d'authentification ;
* certificats ;
* configuration IP ;
* pilotes de cartes réseau ;
* lenteurs réseau ;
* téléphonie ;
* prises réseau ;
* ajout d'appareils ;
* utilisation d'une plateforme de billets ;
* escalade vers les analystes TI lorsque nécessaire.

Environ **20 billets traités par semaine**, avec approximativement **3 escalades hebdomadaires** selon la nature des incidents.

---

## Expérience antérieure en informatique

Expérience en soutien, réseaux, maintenance informatique et administration de comptes dans plusieurs environnements professionnels.

Domaines d'intervention :

* soutien utilisateurs ;
* dépannage matériel et logiciel ;
* réseaux ;
* installation de systèmes ;
* Microsoft 365 ;
* gestion de comptes ;
* MFA ;
* sauvegardes ;
* formation des utilisateurs ;
* maintenance informatique.

---

# Formation

## Maîtrise en bio-informatique

**Université de Montréal — Faculté de médecine**

Principaux domaines :

* bio-informatique ;
* programmation scientifique ;
* biostatistique ;
* analyse de données ;
* génomique ;
* recherche reproductible.

### Projet principal

**Cartographie *in silico* des régions de liaison HuR-like sur le pri-miR-128-1 humain**

---

## Formation antérieure

Formation universitaire et technique en :

* informatique ;
* réseaux ;
* télécommunications ;
* informatique industrielle ;
* maintenance informatique.

---

# Certifications et développement professionnel

## En préparation / parcours ciblé

* Microsoft **MD-102 — Endpoint Administrator**
* Cisco **CCNA**
* Microsoft **SC-300 — Identity and Access Administrator**
* **ITIL 4 Foundation**
* Microsoft **AZ-104 — Azure Administrator**

> Les certifications indiquées dans cette section sont des objectifs de développement professionnel et ne doivent être considérées comme acquises qu'après réussite officielle des examens correspondants.

---

# Portfolio

| Projet                 | Domaine          | Technologies                  | Statut           |
| ---------------------- | ---------------- | ----------------------------- | ---------------- |
| HuR / pri-miR-128-1    | Bio-informatique | Python, FastAPI, NumPy        | Réalisé          |
| Support N2 Lab         | Support TI       | Windows, PowerShell           | En développement |
| Active Directory Lab   | Systèmes         | Windows Server, AD, DNS, DHCP | En développement |
| PowerShell Toolkit     | Automatisation   | PowerShell 7                  | En développement |
| Microsoft 365 Lab      | Cloud / M365     | Microsoft 365                 | En développement |
| Entra ID Lab           | Identité         | Entra ID                      | En développement |
| Intune Lab             | Endpoint         | Intune, Windows 11            | En développement |
| Enterprise Network Lab | Réseaux          | Cisco, Packet Tracer          | En développement |
| Azure Lab              | Cloud            | Azure                         | Planifié         |

---

# CV et documents professionnels

* [CV — Technologie de l'information](LIEN_CV_TI)
* [CV — Bio-informatique](LIEN_CV_BIOINFO)
* [CV — Recherche scientifique](LIEN_CV_RECHERCHE)
* [Profil LinkedIn](VOTRE_LIEN_LINKEDIN)
* [Portfolio PDF](LIEN_PORTFOLIO_PDF)
* [Rapport de maîtrise](LIEN_RAPPORT_MAITRISE)

---

# Ce que je recherche

Je m'intéresse particulièrement aux opportunités dans les environnements :

* hospitaliers ;
* universitaires ;
* centres de recherche ;
* organismes publics ;
* entreprises utilisant l'écosystème Microsoft.

Fonctions ciblées :

* Technicien informatique N2
* Technicien principal
* Administrateur de postes de travail
* Administrateur Microsoft 365 junior
* Technicien réseau intermédiaire
* Analyste informatique junior
* Bioinformaticien junior
* Analyste de données scientifiques

---

# Principes de travail

Je privilégie une approche fondée sur :

* le diagnostic méthodique ;
* la compréhension de la cause racine ;
* la documentation ;
* l'automatisation ;
* la reproductibilité ;
* la sécurité ;
* la validation des résultats ;
* l'amélioration continue.

Dans mes projets, je cherche systématiquement à pouvoir répondre à quatre questions :

1. **Quel problème doit être résolu ?**
2. **Pourquoi cette solution est-elle appropriée ?**
3. **Comment vérifier qu'elle fonctionne ?**
4. **Comment la reproduire ou la maintenir ?**

---

# Contact

**Didier Martial ALLOU**

Montréal, Québec, Canada

[LinkedIn](VOTRE_LIEN_LINKEDIN)
[GitHub](VOTRE_LIEN_GITHUB)
[Courriel](mailto:VOTRE_EMAIL)

---

> Ce portfolio documente ma progression technique à travers des projets reproductibles, des laboratoires et des situations inspirées d'environnements professionnels réels. Les projets en cours sont mis à jour progressivement avec leur documentation, leurs configurations et leurs résultats.
