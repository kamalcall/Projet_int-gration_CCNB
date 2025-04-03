##INTRODUCTION##
Ce projet vise à moderniser l'infrastructure IT d'une PME en mettant en place une solution professionnelle et sécurisée basée sur Active Directory (AD), pfSense, et Wazuh. L'objectif est de répondre aux besoins croissants de sécurité informatique, notamment via la gestion centralisée des identités, l'authentification robuste, et la haute disponibilité des communications. Dans un contexte où les cyberattaques deviennent de plus en plus sophistiquées, il est essentiel pour les PME de disposer d'une infrastructure capable de résister aux menaces tout en garantissant la continuité des opérations.
Les principaux enjeux de cybersécurité incluent la protection des données sensibles, la prévention des intrusions malveillantes, et la conformité aux normes de sécurité. L'utilisation d'Active Directory permet une gestion centralisée des utilisateurs et des politiques de sécurité, tandis que pfSense et Wazuh renforcent respectivement la sécurité réseau et la surveillance proactive des systèmes. Ces technologies permettent de réduire les risques liés aux accès non autorisés, aux vulnérabilités réseau, et aux violations de données.

</br></br>
##APERÇU DU PROJET ET ARCHITECTURE DE LA SOLUTION## 
Le projet a pour but de déployer une infrastructure IT moderne et sécurisée comprenant :
•	Un AD principal et un AD secondaire : pour la gestion des identités et la redondance (Gestion des utilisateurs, groupes, politiques de sécurité & Réplication des données pour assurer la redondance et la haute disponibilité).
•	pfSense : configuré pour l'authentification via Active Directory (AD) et la sécurisation des communications (Pare-feu/routeur avec authentification LDAP/LDAPS via AD).
•	Mise en place d'un accès à distance sécurisé au réseau de l'entreprise via OpenVPN pour les utilisateurs autorisés.
•	Wazuh : Plateforme pour la détection d'intrusions et la surveillance centralisée. 
Ces objectifs visent à améliorer la sécurité globale de l'infrastructure, à garantir la haute disponibilité des services, et à fournir une base solide pour des futurs développements

<img>
