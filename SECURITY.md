# Sécurité

## Signaler une faille

Merci de **ne pas** ouvrir d'issue publique pour une faille de sécurité.

Utilise le **[signalement privé de GitHub](https://github.com/Yoyotaa/argos-releases/security/advisories/new)** en indiquant :

- la version d'Argos et le système (Windows / macOS, version) ;
- ce que tu as observé, et comment le reproduire ;
- l'impact que tu envisages.

Tu recevras une réponse dès que possible. Une fois corrigée, la faille sera mentionnée dans le [journal des modifications](CHANGELOG.md) (avec ton nom si tu le souhaites).

## Versions prises en charge

Seule la **dernière version** reçoit des correctifs. Argos se met à jour tout seul : garde la vérification automatique activée.

## Authenticité des téléchargements

- Ne télécharge Argos **que** depuis la [page des versions](https://github.com/Yoyotaa/argos-releases/releases).
- Chaque version publie `SHA256SUMS.txt` pour vérifier les installeurs.
- Les paquets de mise à jour sont signés (minisign, Ed25519) ; l'application refuse tout paquet dont la signature ne correspond pas à sa clé publique intégrée.
