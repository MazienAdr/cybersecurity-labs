# TP6 — PKI & HTTPS

Mise en place d'une infrastructure à clés publiques (PKI) complète et déploiement d'un serveur HTTPS sécurisé.

## Objectifs

- Examiner la chaîne de certification d'un certificat existant
- Construire une **Autorité de Certification (CA)** avec OpenSSL
- Générer et signer des certificats serveur
- Configurer **Apache en HTTPS** avec redirection automatique HTTP → HTTPS

## Manipulations réalisées

| Étape | Description |
|-------|-------------|
| Examen certificat | Analyse de la chaîne SSL et du contenu d'un certificat X.509 |
| Création de la CA | Autorité de certification auto-signée (validité 10 ans) |
| CSR serveur | Génération de la demande de signature Apache |
| Signature | Signature du certificat serveur par la CA |
| Export PKCS#12 | Conditionnement clé + certificat |
| Configuration Apache | Activation SSL, écoute sur 443 |
| Import navigateur | Installation de la CA et du certificat client dans Firefox |
| Redirection | HTTP → HTTPS automatique |

## Concepts clés

- **Chaîne de confiance** : CA racine → certificat serveur
- **Certificats X.509** : structure, validité, usage
- **TLS** : établissement d'une connexion chiffrée

## Outils

`OpenSSL` · `Apache` · `Firefox` · `Linux`

📄 **[Compte rendu complet (PDF)](./rapport-tp6.pdf)**
