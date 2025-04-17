# 🧠 Projet Réseau : HSRP - DHCP - DNS - WEB

Ce projet Packet Tracer met en œuvre une architecture réseau complète incluant :

- 🛡️ **HSRP (Hot Standby Router Protocol)** : redondance des routeurs pour une haute disponibilité.
- 🧭 **DHCP (Dynamic Host Configuration Protocol)** : attribution automatique des adresses IP.
- 🌐 **DNS (Domain Name System)** : résolution de noms de domaine.
- 🕸️ **Serveur Web** : hébergement local d’un site web.

---

## 📁 Contenu du dépôt

- `projet HSRP - DHCP - DNS - WEB.pkt` : fichier Cisco Packet Tracer du projet.

---

## 🎯 Objectifs pédagogiques

- Mettre en œuvre un réseau résilient avec **HSRP**.
- Configurer un **serveur DHCP** centralisé.
- Déployer un **serveur DNS** local.
- Fournir un service web via un **serveur HTTP**.
- Assurer la **tolérance aux pannes** avec une IP virtuelle partagée.

---

## ⚙️ Fonctionnalités réseau

- Deux routeurs configurés en **HSRP** (IP virtuelle active/passive).
- Un serveur **DHCP** distribuant les IP aux clients automatiquement.
- Un serveur **DNS** pour la résolution de noms internes (ex: `site.local`).
- Un **serveur Web** hébergeant une page consultable depuis les clients.
- Des **PC clients** connectés via des switches, tous fonctionnels.

---

## 🚀 Comment tester le projet

1. Ouvrir le fichier `.pkt` dans **Cisco Packet Tracer**.
2. Lancer la simulation.
3. Depuis un PC client :
   - Tester la **connexion réseau** (ping vers les routeurs et les serveurs).
   - Ouvrir le navigateur et accéder à `http://site.local`.
   - Simuler une **panne du routeur actif** pour observer le basculement HSRP.

---

## 📦 Outils utilisés

- Cisco Packet Tracer
- Protocoles : HSRP, DHCP, DNS, HTTP

---

## 📝 Auteur

Souhaliho BAMBA.

---

## 📸 Aperçu 

![image](https://github.com/user-attachments/assets/3d324384-2bd0-4a17-bae6-0e8979e7a685)


---

