# TP7 — Tunnel VPN avec OpenVPN

Déploiement d'un tunnel VPN chiffré avec une infrastructure à clés publiques dédiée.

## Objectifs

- Établir un tunnel **OpenVPN** entre un serveur (Kali) et un client (Ubuntu)
- Construire une **PKI dédiée** avec Easy-RSA
- Comprendre la différence entre tunnel non sécurisé et tunnel chiffré
- Analyser la **table de routage** résultante

## Manipulations réalisées

| Exercice | Description |
|----------|-------------|
| 1 | Connexion avec une configuration existante |
| 2 | Tunnel sans sécurité (mise en évidence du risque) |
| 3 | Création de la PKI avec Easy-RSA |
| 4 | Clé et certificat serveur |
| 5 | Clé et certificat client |
| 6 | Clé Diffie-Hellman et `ta.key` (HMAC) |
| 7 | Configuration `server.conf` et `client.conf` |
| 8 | Analyse de la table de routage |

## Concepts clés

- **PKI pour VPN** : authentification mutuelle client/serveur
- **Diffie-Hellman** : échange de clés sécurisé
- **Interface `tun0`** : interface réseau virtuelle du tunnel

## Outils

`OpenVPN` · `Easy-RSA` · `Kali Linux` · `Ubuntu`

📄 **[Compte rendu complet (PDF)](./rapport-tp7.pdf)**
