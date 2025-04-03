# 📌 Introduction

Ce projet vise à moderniser l'infrastructure IT d'une PME en mettant en place une solution professionnelle et sécurisée basée sur **Active Directory (AD)**, **pfSense**, et **Wazuh**. 

L'objectif est de répondre aux besoins croissants en **sécurité informatique**, notamment via :
- La **gestion centralisée des identités**
- Une **authentification robuste**
- Une **haute disponibilité des communications**

🔹 Dans un contexte où les cyberattaques deviennent de plus en plus sophistiquées, il est essentiel pour les PME de disposer d'une infrastructure capable de **résister aux menaces** tout en garantissant la **continuité des opérations**.

### 🔒 Enjeux de cybersécurité :
- **Protection des données sensibles**
- **Prévention des intrusions malveillantes**
- **Conformité aux normes de sécurité**

🔹 L'utilisation d'**Active Directory** permet une **gestion centralisée** des utilisateurs et des politiques de sécurité, tandis que **pfSense** et **Wazuh** renforcent respectivement la **sécurité réseau** et la **surveillance proactive des systèmes**.

---

# 🛠️ Aperçu du Projet et Architecture de la Solution

Ce projet a pour but de **déployer une infrastructure IT moderne et sécurisée**, comprenant :

✅ **Active Directory**
- Un **AD principal** et un **AD secondaire** pour la gestion des identités et la redondance
- Gestion des **utilisateurs, groupes, et politiques de sécurité**
- Réplication des données pour assurer **la haute disponibilité**

✅ **pfSense**
- Configuré pour l'**authentification via AD** (LDAP/LDAPS)
- Sécurisation des **communications et du réseau** (pare-feu/routeur)

✅ **Accès à distance sécurisé**
- Mise en place de **OpenVPN** pour les utilisateurs autorisés

✅ **Wazuh**
- Plateforme pour la **détection d'intrusions** et la **surveillance centralisée**

📌 **Objectifs principaux :**
- **Améliorer la sécurité** globale de l'infrastructure
- **Garantir la haute disponibilité** des services
- **Fournir une base solide** pour des futurs développements

---

## 🖼️ Schéma de l'Architecture

![Architecture du projet](./assets/architecture.png)
