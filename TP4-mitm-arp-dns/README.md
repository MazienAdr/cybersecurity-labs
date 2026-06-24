# TP4 — Attaques réseau : ARP Spoofing, MITM & DNS Poisoning

Laboratoire de sécurité offensive démontrant l'interception de trafic sur un réseau local.

## Objectifs

- Réaliser une attaque **ARP Spoofing** pour se positionner en Man-in-the-Middle
- Intercepter et analyser le trafic d'une victime avec **Wireshark**
- Mener une attaque de **DNS Poisoning** avec Ettercap
- Identifier les vulnérabilités exploitées et proposer des **contre-mesures**

## Attaques réalisées

### 1. ARP Spoofing & Man-in-the-Middle
- Reconnaissance et état initial du réseau
- Empoisonnement du cache ARP de la victime et de la passerelle
- Activation du routage IP (`ip_forward`) pour rester transparent
- Vérification du chemin avec `tracepath`
- Capture et analyse du trafic (identifiants en clair)

### 2. ARP Spoofing & DNS Poisoning
- Configuration d'**Ettercap** et du plugin `dns_spoof`
- Redirection de la victime vers un site contrôlé
- Vérification depuis la machine cible (Ubuntu)

## Contre-mesures étudiées

- Détection ARP (entrées statiques, outils de surveillance)
- DNSSEC
- Chiffrement de bout en bout (HTTPS)

## Outils

`Kali Linux` · `arpspoof` · `Ettercap` · `Wireshark` · `Ubuntu`

📄 **[Compte rendu complet (PDF)](./rapport-tp4.pdf)**
