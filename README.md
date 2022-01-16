# Création et Gestion de l'infrastructure cloud de mon entreprise

Installer un serveur WordPress (le site de l’entreprise) sur AWS en utilisant :
```
•	RDS pour le stockage de la base de données
•	S3 pour le stockage des médias (via le plugin amazon-web-services)
•	EC2 et Docker pour le serveur web
•	ELB pour distribuer les requêtes sur les instances EC2
•	CloudFormation pour automatiser la création de l’infrastructure
```
Utilisation du service ELB pour la répartition des requêtes vers les différentes zones de disponibilité (AZ).

Création d'une instance EC2 destinée à héberger l’application intranet sur un sous-réseau privé.

Création d'un serveur de fichier dans le réseau local de mon entreprise

Création d'une liaison VPN entre mon réseau Onpremise et mon réseau aws.

Utilisation de CloudWatch pour déclencher l'autoscaling en cas d'un surcharge du processeur d'une instance.

Utilisation du service SNS pour m'alerter dans le cas d'un autoscaling.

Sécuriser mon Infrastructure à l'aide la ressource Groupe de sécurité.

**Outils : Cloudformation, EC2, ELB, RDS, S3, autoscaling, Security groups, VPC, Internet Gateways, NAT Gateways, Elastic Ips…**

