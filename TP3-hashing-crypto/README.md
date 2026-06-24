# TP3 — Hachage & Cryptographie

Laboratoire couvrant les fonctions de hachage, les attaques sur mots de passe, et le chiffrement d'e-mails.

## Objectifs

- Implémenter et utiliser des fonctions de hachage (SHA-256, MD5)
- Mener des attaques par dictionnaire et par brute force
- Comprendre le rôle du **salt** et de **bcrypt**
- Démontrer une **collision MD5**
- Chiffrer et signer des e-mails avec **GPG**

## Manipulations réalisées

| Étape | Description |
|-------|-------------|
| Hachage | Script Python (SHA-256) + commandes Linux (`md5sum`, `sha1sum`, `sha256sum`) |
| Dictionnaire | Génération avec **CeWL**, attaque par dictionnaire |
| Brute force | Cassage de mots de passe faibles |
| Salt & bcrypt | Protection contre les rainbow tables |
| Collision MD5 | Démonstration de deux fichiers différents avec le même hash MD5 |
| Chiffrement e-mail | Configuration Thunderbird + GPG, vérification de l'illisibilité côté Gmail |

## Concepts clés

- **Hachage ≠ Encodage ≠ Chiffrement** : différences fondamentales et cas d'usage
- **Importance du salt** : pourquoi deux utilisateurs avec le même mot de passe doivent avoir des hash différents
- **Symétrique vs asymétrique** : pourquoi le chiffrement d'e-mails repose sur l'asymétrique

## Outils

`Python` · `Linux` · `CeWL` · `bcrypt` · `Thunderbird` · `GPG`

📄 **[Compte rendu complet (PDF)](./rapport-tp3.pdf)**
