# Journal des modifications

Chaque version a sa section `## x.y.z — AAAA-MM-JJ`, avec des sous-parties
`### Nouveautés`, `### Améliorations`, `### Corrections` ou `### Sécurité`.
Argos lit ce fichier pour afficher « Quoi de neuf » sans quitter
l'application : garder une ligne par changement, écrite pour tout le monde.

## 0.1.0 — 2026-11-06

### Nouveautés

- Analyse de fichiers avec trois moteurs : ClamAV (s'il est installé), règles YARA-X et heuristique maison.
- Protection en temps réel des dossiers où arrivent les menaces (Téléchargements, Bureau, démarrage…) et surveillance des nouveaux programmes.
- Anti-ransomware : fichiers leurres, détection des rafales de chiffrement et arrêt du programme coupable.
- Quarantaine chiffrée, restaurable à tout moment.
- Bilan de santé avec un score de sécurité et des corrections en un clic.
- Carte du réseau local : appareils connectés, ports ouverts, état de la box, alerte en cas d'intrus ou d'usurpation.
- Blocage de l'accès Internet d'un programme et DNS protecteur en un clic.
- Persistance : tout ce qui se relance tout seul au démarrage, et ce qui a changé.
- Chronologie de la machine, confidentialité (webcam, micro, mots de passe fuités) et logiciels pas à jour.
- Mode jeu, mode Famille via Tailscale et assistant local.
- Tutoriel de première ouverture et palette de commandes (⌘K ou Ctrl K).
- Mises à jour d'Argos depuis l'application, avec le détail de ce qui change.
- Page « Comparatif » : ce qu'Argos fait bien, moins bien, et ne fait pas.
- Page « Transparence » : tout ce qui sort de ton PC, et avec quel accord.
