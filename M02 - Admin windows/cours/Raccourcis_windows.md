# Raccourcis Windows et Windows Server pour l’administration système et réseau

> Aide-mémoire destiné aux administrateurs système, aux équipes support, aux techniciens d’exploitation et aux apprenants en administration systèmes et réseaux.

Ce document réunit les principaux raccourcis clavier de Windows et Windows Server utiles pour accéder rapidement aux outils d’administration, gérer des sessions distantes, travailler avec l’Explorateur, organiser les fenêtres et administrer les rôles AD DS, DNS, DHCP et RDS.

> Les comportements peuvent varier selon la version de Windows, l’application utilisée, la configuration du poste et le contexte de connexion, notamment en session RDP.

## Sommaire

- [Raccourcis essentiels](#raccourcis-essentiels)
- [Lancer les consoles et outils](#lancer-les-consoles-et-outils)
- [Gestion des fenêtres et de l’écran](#gestion-des-fenêtres-et-de-lécran)
- [Bureaux virtuels et multitâche](#bureaux-virtuels-et-multitâche)
- [Explorateur et partages réseau](#explorateur-et-partages-réseau)
- [Capture, assistance et support](#capture-assistance-et-support)
- [Invite de commandes et console](#invite-de-commandes-et-console)
- [Sessions RDP](#sessions-rdp)
- [Server Manager](#server-manager)
- [Consoles AD DS, DNS, DHCP et RDS](#consoles-ad-ds-dns-dhcp-et-rds)
- [Accessibilité utile](#accessibilité-utile)
- [Aide-mémoire opérationnel](#aide-mémoire-opérationnel)

---

## Raccourcis essentiels

| Raccourci | Action | Usage d’administration |
|---|---|---|
| <kbd>Windows</kbd> | Ouvre ou ferme le menu Démarrer | Lancer rapidement un outil système |
| <kbd>Windows</kbd> + <kbd>X</kbd> | Ouvre le menu d’accès rapide | Accès à Terminal, Gestionnaire de périphériques, Gestion du disque, Connexions réseau selon la version |
| <kbd>Windows</kbd> + <kbd>R</kbd> | Ouvre la boîte **Exécuter** | Lancer une console MMC, une applet CPL ou une commande |
| <kbd>Windows</kbd> + <kbd>E</kbd> | Ouvre l’Explorateur de fichiers | Naviguer dans les partages, journaux, scripts et profils |
| <kbd>Windows</kbd> + <kbd>I</kbd> | Ouvre les Paramètres | Accéder aux options réseau, système et mises à jour |
| <kbd>Windows</kbd> + <kbd>L</kbd> | Verrouille le poste | Sécuriser immédiatement une session d’administration |
| <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Esc</kbd> | Ouvre le Gestionnaire des tâches | Analyser les processus, services, performances et blocages |
| <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Suppr</kbd> | Ouvre l’écran de sécurité Windows | Verrouiller, changer d’utilisateur ou ouvrir le Gestionnaire des tâches |
| <kbd>Alt</kbd> + <kbd>Tab</kbd> | Bascule entre les fenêtres ouvertes | Passer entre consoles MMC, RDP, navigateur et scripts |
| <kbd>Alt</kbd> + <kbd>F4</kbd> | Ferme la fenêtre active | Fermer rapidement une console ou une boîte de dialogue |

---

## Lancer les consoles et outils

La combinaison <kbd>Windows</kbd> + <kbd>R</kbd> est l’un des moyens les plus rapides d’ouvrir des consoles d’administration et des applets système.

| Commande à saisir dans **Exécuter** | Outil lancé | Utilisation principale |
|---|---|---|
| `cmd` | Invite de commandes | Diagnostic et commandes classiques Windows |
| `powershell` ou `pwsh` | PowerShell | Automatisation et administration par scripts |
| `compmgmt.msc` | Gestion de l’ordinateur | Événements, disques, utilisateurs locaux, services |
| `eventvwr.msc` | Observateur d’événements | Consultation des journaux système et applicatifs |
| `services.msc` | Services | Démarrer, arrêter ou configurer les services |
| `devmgmt.msc` | Gestionnaire de périphériques | Pilotes et matériels |
| `diskmgmt.msc` | Gestion des disques | Partitions, volumes et disques |
| `ncpa.cpl` | Connexions réseau | Cartes réseau, IPv4/IPv6 et adaptateurs |
| `wf.msc` | Pare-feu Windows Defender avancé | Règles entrantes, sortantes et profils |
| `gpedit.msc` | Stratégie de groupe locale | Paramètres locaux de stratégie |
| `secpol.msc` | Stratégie de sécurité locale | Droits utilisateur et stratégies de sécurité |
| `sysdm.cpl` | Propriétés système | Nom de machine, domaine, performances et variables |
| `mstsc` | Connexion Bureau à distance | Ouverture d’une session RDP |
| `taskschd.msc` | Planificateur de tâches | Création et suivi des tâches planifiées |

---

## Gestion des fenêtres et de l’écran

Ces raccourcis facilitent le travail simultané sur plusieurs consoles, une documentation technique et une session distante.

| Raccourci | Action | Exemple d’usage |
|---|---|---|
| <kbd>Windows</kbd> + <kbd>←</kbd> | Ancre la fenêtre à gauche | PowerShell à gauche et documentation à droite |
| <kbd>Windows</kbd> + <kbd>→</kbd> | Ancre la fenêtre à droite | Comparer deux fichiers de logs ou deux consoles |
| <kbd>Windows</kbd> + <kbd>↑</kbd> | Maximise la fenêtre active | Agrandir une console de supervision |
| <kbd>Windows</kbd> + <kbd>↓</kbd> | Réduit ou restaure la fenêtre active | Dégager rapidement l’écran |
| <kbd>Windows</kbd> + <kbd>Z</kbd> | Ouvre les dispositions d’ancrage | Organiser plusieurs outils sur un grand écran |
| <kbd>Windows</kbd> + <kbd>Home</kbd> | Réduit ou restaure les autres fenêtres | Conserver une seule console visible pendant une intervention |
| <kbd>Windows</kbd> + <kbd>D</kbd> | Affiche ou masque le Bureau | Accéder aux fichiers de dépannage ou raccourcis du Bureau |
| <kbd>Windows</kbd> + <kbd>,</kbd> | Affiche temporairement le Bureau | Vérifier rapidement un élément placé derrière les fenêtres |
| <kbd>Windows</kbd> + <kbd>Shift</kbd> + <kbd>←</kbd> / <kbd>→</kbd> | Déplace la fenêtre active vers un autre moniteur | Envoyer une session RDP sur le second écran |

---

## Bureaux virtuels et multitâche

Les bureaux virtuels permettent de séparer les tâches : exploitation, tickets, documentation, connexions distantes ou supervision.

| Raccourci | Action |
|---|---|
| <kbd>Windows</kbd> + <kbd>Tab</kbd> | Ouvre l’affichage des tâches |
| <kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>D</kbd> | Crée un nouveau bureau virtuel |
| <kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>←</kbd> | Bascule vers le bureau virtuel de gauche |
| <kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>→</kbd> | Bascule vers le bureau virtuel de droite |
| <kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>F4</kbd> | Ferme le bureau virtuel actuel |

---

## Explorateur et partages réseau

L’Explorateur de fichiers reste indispensable pour consulter les journaux, les scripts, les partages UNC et les répertoires de déploiement.

| Raccourci | Action | Intérêt d’administration |
|---|---|---|
| <kbd>Alt</kbd> + <kbd>D</kbd> | Sélectionne la barre d’adresse | Saisir un chemin UNC, par exemple `\\serveur\partage` |
| <kbd>Ctrl</kbd> + <kbd>L</kbd> | Place le focus dans la barre d’adresse | Variante pour changer rapidement de chemin |
| <kbd>Ctrl</kbd> + <kbd>E</kbd> ou <kbd>Ctrl</kbd> + <kbd>F</kbd> | Sélectionne la zone de recherche | Rechercher un journal, un script ou un fichier de configuration |
| <kbd>Ctrl</kbd> + <kbd>N</kbd> | Ouvre une nouvelle fenêtre | Comparer deux dossiers ou deux serveurs |
| <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>N</kbd> | Crée un dossier | Préparer une collecte ou une arborescence de dépôt |
| <kbd>F2</kbd> | Renomme l’élément sélectionné | Renommer un script, un export ou une sauvegarde |
| <kbd>F5</kbd> | Actualise la fenêtre | Vérifier l’arrivée d’un fichier sur un partage |
| <kbd>Shift</kbd> + <kbd>Suppr</kbd> | Supprime définitivement | Nettoyer des fichiers temporaires avec prudence |
| <kbd>Alt</kbd> + <kbd>Entrée</kbd> | Affiche les propriétés | Contrôler attributs, taille et permissions |
| <kbd>F11</kbd> | Bascule en plein écran | Gagner de l’espace sur un petit écran |

---

## Capture, assistance et support

| Raccourci | Action |
|---|---|
| <kbd>Windows</kbd> + <kbd>Shift</kbd> + <kbd>S</kbd> | Capture une zone de l’écran dans le presse-papiers |
| <kbd>Alt</kbd> + <kbd>Impr. écran</kbd> | Capture la fenêtre active dans le presse-papiers |
| <kbd>Windows</kbd> + <kbd>Impr. écran</kbd> | Enregistre une capture plein écran dans le dossier `Captures d’écran` |
| <kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>Q</kbd> | Ouvre Assistance rapide (Quick Assist) |
| <kbd>Windows</kbd> + <kbd>V</kbd> | Ouvre l’historique du presse-papiers |
| <kbd>Windows</kbd> + <kbd>H</kbd> | Ouvre la saisie vocale |

---

## Invite de commandes et console

Les raccourcis suivants sont utiles pour copier des commandes, sélectionner du texte ou parcourir la sortie d’une console.

| Raccourci | Action |
|---|---|
| <kbd>Ctrl</kbd> + <kbd>C</kbd> ou <kbd>Ctrl</kbd> + <kbd>Inser</kbd> | Copie le texte sélectionné |
| <kbd>Ctrl</kbd> + <kbd>V</kbd> ou <kbd>Shift</kbd> + <kbd>Inser</kbd> | Colle le texte |
| <kbd>Ctrl</kbd> + <kbd>M</kbd> | Active le mode Marquage |
| <kbd>Alt</kbd> + sélection | Démarre une sélection en bloc |
| <kbd>Ctrl</kbd> + <kbd>↑</kbd> | Remonte d’une ligne dans l’historique de sortie |
| <kbd>Ctrl</kbd> + <kbd>↓</kbd> | Descend d’une ligne dans l’historique de sortie |
| <kbd>Ctrl</kbd> + <kbd>Home</kbd> | Va au début du tampon ou supprime à gauche selon le contexte |
| <kbd>Ctrl</kbd> + <kbd>End</kbd> | Va à la fin du tampon ou supprime à droite selon le contexte |

---

## Sessions RDP

Dans une session Bureau à distance, l’application des raccourcis peut dépendre de la configuration du client RDP : certains raccourcis sont envoyés au poste local, d’autres au serveur distant.

| Raccourci | Action dans la session distante |
|---|---|
| <kbd>Alt</kbd> + <kbd>Home</kbd> | Affiche le menu Démarrer du poste distant |
| <kbd>Alt</kbd> + <kbd>Page ↑</kbd> | Bascule entre les programmes de gauche à droite |
| <kbd>Alt</kbd> + <kbd>Page ↓</kbd> | Bascule entre les programmes de droite à gauche |
| <kbd>Alt</kbd> + <kbd>Inser</kbd> | Parcourt les programmes dans leur ordre d’ouverture |
| <kbd>Alt</kbd> + <kbd>Suppr</kbd> | Ouvre le menu système de la fenêtre distante active |
| <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Fin</kbd> | Ouvre l’écran de sécurité Windows du poste distant |
| <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Pause</kbd> | Bascule entre le mode fenêtré et le plein écran RDP |
| <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>-</kbd> | Capture la fenêtre distante active dans le presse-papiers |
| <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>+</kbd> | Capture toute la fenêtre cliente RDP dans le presse-papiers |

---

## Server Manager

Server Manager possède ses propres touches d’accès pour accélérer la navigation dans les vues serveur, les tuiles et les propriétés locales.

### Navigation générale

| Raccourci | Action |
|---|---|
| <kbd>Alt</kbd> + <kbd>M</kbd> | Ouvre le menu **Manage** |
| <kbd>Alt</kbd> + <kbd>V</kbd> | Ouvre le menu **View** |
| <kbd>Alt</kbd> + <kbd>H</kbd> | Ouvre le menu **Help** |
| <kbd>F1</kbd> | Ouvre l’aide |
| <kbd>F5</kbd> | Actualise la vue |
| <kbd>Alt</kbd> + <kbd>N</kbd> | Ouvre les notifications ou les détails des tâches |
| <kbd>Ctrl</kbd> + <kbd>+</kbd> | Effectue un zoom avant |
| <kbd>Ctrl</kbd> + <kbd>-</kbd> | Effectue un zoom arrière |
| <kbd>Ctrl</kbd> + <kbd>0</kbd> | Rétablit l’affichage à 100 % |
| <kbd>Alt</kbd> + <kbd>←</kbd> ou <kbd>Retour arrière</kbd> | Revient à la vue précédente |
| <kbd>Alt</kbd> + <kbd>→</kbd> | Va à la vue suivante |

### Tuiles Server Manager

| Raccourci | Tuile ciblée |
|---|---|
| <kbd>Alt</kbd> + <kbd>P</kbd> | Propriétés du serveur local |
| <kbd>Alt</kbd> + <kbd>E</kbd> | Événements |
| <kbd>Alt</kbd> + <kbd>R</kbd> | Services |
| <kbd>Alt</kbd> + <kbd>B</kbd> | Best Practices Analyzer (BPA) |
| <kbd>Alt</kbd> + <kbd>O</kbd> | Performances |
| <kbd>Alt</kbd> + <kbd>A</kbd> | Rôles et fonctionnalités ou liste des serveurs selon la page |

### Propriétés du serveur local

| Raccourci | Champ ciblé |
|---|---|
| <kbd>Alt</kbd> + <kbd>C</kbd> | Nom de l’ordinateur |
| <kbd>Alt</kbd> + <kbd>L</kbd> | Dernières mises à jour installées |
| <kbd>Alt</kbd> + <kbd>D</kbd> | Domaine ou groupe de travail |
| <kbd>Alt</kbd> + <kbd>W</kbd> | Windows Update |
| <kbd>Alt</kbd> + <kbd>S</kbd> | Dernière recherche de mises à jour |
| <kbd>Alt</kbd> + <kbd>R</kbd> | Gestion à distance |
| <kbd>Alt</kbd> + <kbd>F</kbd> | Pare-feu Windows |
| <kbd>Alt</kbd> + <kbd>K</kbd> | Bureau à distance |
| <kbd>Alt</kbd> + <kbd>G</kbd> | Windows Error Reporting |
| <kbd>Alt</kbd> + <kbd>T</kbd> | NIC Teaming |
| <kbd>Alt</kbd> + <kbd>X</kbd> | Customer Experience Improvement Program |
| <kbd>Alt</kbd> + <kbd>O</kbd> | Connexion Ethernet filaire |
| <kbd>Alt</kbd> + <kbd>Y</kbd> | IE Enhanced Security Configuration |
| <kbd>Alt</kbd> + <kbd>Z</kbd> | Fuseau horaire |

---

## Consoles AD DS, DNS, DHCP et RDS

L’approche la plus efficace consiste à lancer directement la console souhaitée avec <kbd>Windows</kbd> + <kbd>R</kbd>, puis à utiliser les raccourcis standards de navigation des consoles MMC : <kbd>F5</kbd>, <kbd>F2</kbd>, <kbd>Suppr</kbd>, <kbd>Shift</kbd> + <kbd>F10</kbd>, <kbd>Tab</kbd>, les flèches et <kbd>Entrée</kbd>.

| Rôle ou console | Ouverture rapide | Usage principal |
|---|---|---|
| AD DS — Active Directory Users and Computers | `dsa.msc` | Utilisateurs, groupes, ordinateurs, OU, mots de passe et délégation |
| AD DS — Active Directory Sites and Services | `dssite.msc` | Sites, sous-réseaux et réplication inter-sites |
| AD DS — Active Directory Domains and Trusts | `domain.msc` | Relations d’approbation et niveaux fonctionnels |
| AD DS — ADSI Edit | `adsiedit.msc` | Attributs LDAP avancés et dépannage, avec prudence |
| DNS Manager | `dnsmgmt.msc` | Zones, enregistrements, délégations et transferts |
| DHCP Manager | `dhcpmgmt.msc` | Étendues IPv4/IPv6, options, réservations et baux |
| RDS — Connexion Bureau à distance | `mstsc` | Administration de serveurs et hôtes distants |

### Navigation MMC : raccourcis transverses

| Raccourci | Action | Exemple |
|---|---|---|
| <kbd>F5</kbd> | Actualise la vue | Mettre à jour une OU, une zone DNS ou une liste de baux DHCP |
| <kbd>F2</kbd> | Renomme l’objet sélectionné | Renommer une OU ou un groupe |
| <kbd>Suppr</kbd> | Supprime l’objet sélectionné | Supprimer un enregistrement DNS erroné ou une réservation |
| <kbd>Shift</kbd> + <kbd>F10</kbd> | Ouvre le menu contextuel | Créer un objet, ouvrir les propriétés ou lancer une action |
| <kbd>Tab</kbd> / <kbd>Shift</kbd> + <kbd>Tab</kbd> | Déplace le focus | Passer de l’arborescence à la liste ou aux propriétés |
| <kbd>←</kbd> / <kbd>→</kbd> | Replie ou développe un nœud | Naviguer dans les zones DNS ou les étendues DHCP |
| <kbd>↑</kbd> / <kbd>↓</kbd> | Parcourt les objets | Sélectionner une zone, une réservation ou une OU |
| <kbd>Entrée</kbd> | Ouvre ou valide l’élément sélectionné | Afficher les propriétés d’un objet |
| <kbd>Ctrl</kbd> + <kbd>C</kbd> / <kbd>Ctrl</kbd> + <kbd>V</kbd> | Copie ou colle | Réutiliser un DN, un chemin ou une valeur |

### Repères par rôle

- **AD DS** : retenir `dsa.msc`, `dssite.msc`, `domain.msc` et `adsiedit.msc`, puis utiliser <kbd>F5</kbd>, <kbd>Shift</kbd> + <kbd>F10</kbd>, <kbd>Tab</kbd> et les flèches.
- **DNS** : retenir `dnsmgmt.msc`, puis utiliser <kbd>F5</kbd>, <kbd>Shift</kbd> + <kbd>F10</kbd>, les flèches et <kbd>Suppr</kbd> pour les zones et enregistrements.
- **DHCP** : retenir `dhcpmgmt.msc`, puis utiliser <kbd>F5</kbd>, <kbd>Shift</kbd> + <kbd>F10</kbd>, <kbd>Entrée</kbd> et les flèches pour les étendues, options et réservations.
- **RDS** : retenir `mstsc`, <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Fin</kbd>, <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Pause</kbd>, <kbd>Alt</kbd> + <kbd>Home</kbd> et <kbd>Alt</kbd> + <kbd>Page ↑</kbd>/<kbd>Page ↓</kbd>.

---

## Accessibilité utile

Ces raccourcis peuvent également être utiles lors d’une intervention de support ou d’un dépannage visuel.

| Raccourci | Action |
|---|---|
| <kbd>Windows</kbd> + <kbd>U</kbd> | Ouvre les paramètres d’accessibilité |
| <kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>Entrée</kbd> | Ouvre le Narrateur |
| <kbd>Windows</kbd> + <kbd>+</kbd> | Zoom avant avec la Loupe |
| <kbd>Windows</kbd> + <kbd>-</kbd> | Zoom arrière avec la Loupe |
| <kbd>Windows</kbd> + <kbd>Esc</kbd> | Ferme la Loupe |
| <kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>C</kbd> | Active ou désactive les filtres de couleur, si configurés |
| <kbd>Shift</kbd> cinq fois | Active ou désactive les touches rémanentes |

---

## Aide-mémoire opérationnel

- Pour ouvrir vite un outil système : <kbd>Windows</kbd> + <kbd>R</kbd>, puis une console MMC ou une applet CPL.
- Pour travailler sur plusieurs outils : <kbd>Alt</kbd> + <kbd>Tab</kbd>, <kbd>Windows</kbd> + <kbd>Tab</kbd> et les bureaux virtuels.
- Pour le support à distance : <kbd>Windows</kbd> + <kbd>Ctrl</kbd> + <kbd>Q</kbd> pour Assistance rapide et <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>Fin</kbd> pour l’écran de sécurité dans RDP.
- Pour Server Manager : retenir en priorité <kbd>Alt</kbd> + <kbd>M</kbd>, <kbd>Alt</kbd> + <kbd>V</kbd>, <kbd>Alt</kbd> + <kbd>P</kbd>, <kbd>Alt</kbd> + <kbd>R</kbd>, <kbd>Alt</kbd> + <kbd>T</kbd> et <kbd>F5</kbd>.

## Sources

- [Microsoft Learn — Raccourcis clavier dans Windows](https://support.microsoft.com/windows/keyboard-shortcuts-in-windows-dcc61a57-8ff0-cffe-9796-cb9706c75eec)
- [Microsoft Learn — Raccourcis clavier de Server Manager](https://learn.microsoft.com/windows-server/administration/server-manager/server-manager-keyboard-shortcuts)
- [Microsoft Learn — Raccourcis Bureau à distance](https://learn.microsoft.com/windows-server/remote/remote-desktop-services/clients/remote-desktop-connection-keyboard-shortcuts)

---

> Document conçu comme une fiche de référence. Avant toute action sensible ou destructive (suppression, modification de stratégie, modification DNS/DHCP), vérifier la cible, le contexte et l’existence d’une sauvegarde ou d’un plan de retour arrière.

