### ### MICROSOFT-CERTIFIED : Principes de base de Microsoft Azure

## Objectifs d’apprentissage

À l’issue de ce module, je pourrais :

- Définir le cloud computing.
- Décrire le modèle de responsabilité partagée.
- Définir les modèles de cloud, notamment public, privé et hybride.
- Identifier les cas d’usage appropriés pour chaque modèle de cloud.
- Décrire le modèle basé sur la consommation.
- Comparer les modèles tarifaires liés au cloud.

1.  Introduction aux fondamentaux de Microsoft Azure

Microsoft Azure est une plateforme Cloud computing offrant un ensemble croissant de services permettant d'aider les commerciaux dans la quête d'une solution efficace répondant à leurs objectifs.

Les services cloud d'Azure prennent en charge tous les aspects au plus simples au plus complexes, Azure propose un service web simple pour héberger les services commerciaux des entreprises dans le cloud.
Il s'occupe de la gestion sur des machines virtuelles personnalisées que ce soit pour :

* Le stockage distant
* Héberger les BDD
* La gestion centralisée  des comptes
* Services de l'IA et IoT (Internet des Objets)*

Les fondamentaux d'Azure sont basés sur une série de 3 parcours d'apprentissage qui permettront de se familiariser avec Azure et ses multitudes de fonctionnalités.

[Que vous soyez intéressé par les services de calcul, de réseau ou de stockage, découvrir les meilleures pratiques de sécurité Cloud, l’exploration des options de gouvernance et de gestion, considérez les Fondamentaux Azure comme votre guide personnalisé pour Azure.]

Azure offre un environnement portail temporaire appelé "BAC A SABLE", permettant de créer des ressources Cloud gratuitement.
Ce dernier ne demande pas une maitrise absolue en informatique mais le cas contraire pourrait être plus intéressant pour une vision globale et approfondie d'Azure Cloud Service.

Ce module permet de comprendre trois grands catégories très importantes pour l'apprentissage et à la certification :

##### Description des concepts du Cloud (25-30%)
##### Décrire l'architecture et le service Azure (35-40%)
##### Décrire le gestion et la gouvernance d'Azure (30-35%)


## QU'EST-CE QUE LE CLOUD COMPUTING ?

Le cloud permet de fournir les services informatiques sur internet. Ces services peuvent être l'infrastructure informatique telles que les machines virtuelles, le stockage, les bases de données et le réseau.

Les services cloud sont répandu sur d'autres offres informatiques classique tels que l'IoT, ML et l'IA.



![[Pasted image 20231129145332.png]]


## Définir les modèles du Cloud
Il existe trois principaux modèles du cloud, ils définissent le type de déploiement des ressources cloud.
## Cloud privé

Commençons par le cloud privé. Un cloud privé est, à certains égards, l’évolution naturelle d’un centre de données d’entreprise. Il s’agit d’un cloud (fournissant des services informatiques sur Internet) qui est utilisé par une seule entité. Le cloud privé offre un contrôle beaucoup plus important à l’entreprise et à son service informatique. Toutefois, il implique également plus de coûts et moins d’avantages par rapport à un déploiement de cloud public. Enfin, un cloud privé peut être hébergé dans votre centre de données local. Il peut également être hébergé dans un centre de données dédié hors site, notamment par un tiers qui le réserve exclusivement à votre entreprise.

## Cloud public

Un cloud public est créé, contrôlé et géré par un fournisseur de cloud tiers. Avec un cloud public, toute personne qui souhaite acheter des services cloud peut accéder aux ressources et les utiliser. La disponibilité publique générale est une différence clé entre le cloud public et le cloud privé.

## Cloud hybride

Un cloud hybride est un environnement informatique qui utilise à la fois les clouds public et privé dans un environnement interconnecté. Un environnement de cloud hybride peut permettre à un cloud privé de répondre à une demande temporaire accrue via le déploiement de ressources de cloud public. Le cloud hybride peut être utilisé pour fournir une couche de sécurité supplémentaire. Par exemple, les utilisateurs ont toute latitude pour choisir les services à conserver dans le cloud public, et ceux à déployer sur leur infrastructure de cloud privé.

Le tableau suivant met en évidence quelques aspects comparatifs clés entre les modèles de cloud.

![[Pasted image 20231129153305.png]]






## Azure VMware Solution

Que se passe-t-il si vous êtes déjà établi avec VMware dans un environnement de cloud privé, et si vous souhaitez migrer vers un cloud public ou hybride ? Azure VMware Solution vous permet d’exécuter vos charges de travail VMware dans Azure avec une intégration et une scalabilité transparentes.


# Décrire le modèle basé sur la consommation

Lorsqu'on compare les modèles d'infrastructure informatique, il y a deux types de dépenses à considérer. Dépenses d’investissement ("CapEx") et dépenses d’exploitation ("OpEx").

Les CapEx sont généralement des dépenses uniques et initiales pour l’achat ou la sécurisation de ressources tangibles. L'achat d'un nouveau bâtiment, le repavage du parking, la construction d'un centre de données ou l'achat d'un véhicule d'entreprise sont des exemples de CapEx.

En revanche, l'OpEx consiste à dépenser de l'argent sur des services ou des produits au fil du temps. La location d’un centre de conventions, le crédit-bail d’un véhicule de société ou l’abonnement à des services cloud sont autant d’exemples d’OpEx.

Le cloud computing relève des OpEx, car il fonctionne selon un modèle basé sur la consommation. Avec le cloud computing, vous ne payez pas pour l’infrastructure physique, l’électricité, la sécurité ou tout ce qui est associé à la maintenance d’un centre de données. À la place, vous payez pour les ressources informatiques que vous utilisez. Si vous n’utilisez aucune ressource informatique ce mois-ci, vous ne payez pas pour ces dernières.

Ce modèle basé sur la consommation présente de nombreux avantages, notamment :

- Pas de frais initiaux.
- Nul besoin d’acheter et de gérer une infrastructure coûteuse que les utilisateurs n’exploitent pas toujours au maximum.
- Possibilité de payer pour des ressources supplémentaires quand elles sont nécessaires.
- Possibilité de cesser de payer pour les ressources qui ne sont plus nécessaires.

Avec un centre de données classique, vous essayez d’estimer les besoins futurs en ressources. En cas de surestimation de vos calculs, vous dépensez plus que nécessaire pour votre centre de données, et vous risquez de perdre de l’argent. En cas de sous-estimation de vos calculs, votre centre de données atteindra rapidement sa capacité maximale, et vos applications et services risquent de souffrir d’une baisse de performances. La correction d’un centre de données sous-dimensionné peut prendre beaucoup de temps. Vous devrez peut-être commander, recevoir et installer davantage de matériel. Vous devrez également ajouter de l'alimentation électrique, de la climatisation et des connexions réseau pour le matériel supplémentaire.

Dans un modèle basé sur le cloud, vous n’avez pas à vous soucier de l’obtention des ressources nécessaires. Si vous constatez que vous avez besoin de plus de machines virtuelles, ajoutez-en. Si la demande diminue et si vous n’avez pas besoin d’autant de machines virtuelles, supprimez les machines selon les besoins. Dans tous les cas, vous ne payez que pour les machines virtuelles que vous utilisez, et non pour la « capacité supplémentaire » dont dispose le fournisseur de cloud.

## Comparer les modèles de tarification Cloud

Le cloud computing consiste à fournir des services informatiques sur Internet en utilisant un modèle tarifaire de type paiement à l’utilisation. Vous payez généralement uniquement pour les services Cloud que vous utilisez, ce qui vous aide à :

- Planifier et gérer vos coûts d’exploitation.
- D’exécuter votre infrastructure plus efficacement
- Adapter la mise à l'échelle à l'évolution de vos besoins commerciaux

En d’autres termes, L'informatique en nuage est un moyen de louer de la puissance de calcul et du stockage à partir du centre de données de quelqu'un d'autre. Vous pouvez utiliser les ressources cloud de la même façon que les ressources dans votre propre centre de données. Toutefois, contrairement à votre propre centre de données, quand vous avez fini d’utiliser les ressources cloud, vous les rendez. Vous êtes facturé uniquement pour ce que vous utilisez.

Au lieu de maintenir des processeurs et des espaces de stockage dans votre centre de données, vous les louez pour la durée dont vous en avez besoin. Le fournisseur Cloud s'occupe de la maintenance de l'infrastructure sous-jacente pour vous. Le Cloud vous permet de résoudre rapidement vos défis commerciaux les plus difficiles et de proposer des solutions innovantes à vos utilisateurs.


#### Contrôle qualité des connaissances

![[Pasted image 20231129162420.png]]

![[Pasted image 20231129162457.png]]



<<<<<<< HEAD


### Décrire les avantages de la haute disponibilité et de la scalabilité dans le cloud

Durant la création ou le déploiement d’une application cloud, deux des aspects les plus importants à prendre en compte sont la durée de bon fonctionnement (ou haute disponibilité) et la capacité à gérer la demande (ou scalabilité).

![Alt text](image.png)


####  Haute disponiblité

Lors du deploiement d'une application, il est important que les ressources soient disponibles en cas de besoin.  Cela va permettre de garantir la disponibilité des servcives peu importe les interruptions ou les événements suceptibles de se produire.

Garantir la disponibilité du service est très important pour le bon contrôle du service lié aux incidents majeurs ou mineurs.

##### SERVICE SLA (SERVIVE LEVEL AGREEMENTS)
C'est un service qui garantit la disponibilité du service selon le besoin métier:

Est-ce que le SLA de 99% est il différent du SLA de 99,9% : OUI

Tout simplement un SLA de 99% peut être indisponible jusqu'à 1.6 heures par semaine soit 7,2 heures par mois et rester disponible 99% cette durée est cumulative et peut couvrir à plusieurs incidents d'indisponibilité de service.
Tandsique le SLA de 99,9% peut être indisponible que 10 min par semaine soit 42,2 min par mois.

La différence est donc importante, si le service est indisponible pour votre activité, la différence entre plusieurs minutes et plusieurs heures de temps d'arrêt sera considérable.

En général les services à haute disponibilité sont chers, chaque service Azure à son propre SLA.
![Alt text](image-1.png)


#### Scalabilité

C'est la capacité à ajuster ou à traiter les requêtes par rapport à la demande ou le temps d'exécution. L'unique avantage est que l'on peut payer juster un service de scalabilté selon ces besoins.
Le cloud étant un modèle basé sur la consommation, si la demande diminue vous pouvez reduire vos ressources ainsi que le coût.

Il exite deux types de scalabilité:

* Scalabilité Horizontale
* Scalabilité Verticale


#### Scalabilité Horizontale
La scalabilité horizontale consiste à ajouter ou soustraire un certain nombre de ressources.
C'est-à-dire, si vous rencontrez soudainement une forte augmentation de la demande, vos ressources déployées peuvent faire l’objet d’un scale-out (automatiquement ou manuellement). Par exemple, vous pouvez ajouter des VMs (machines virtuelles) ou des conteneurs supplémentaires à des fins de scale-out. De la même manière, en cas de baisse significative de la demande, les ressources déployées peuvent faire l’objet d’un scale-in (automatiquement ou manuellement).

#### Scalabilité Verticale
La scalabilité verticale vise à augmenter ou diminuer les capacités des ressources.
C'est-à-dire, si vous développez une application et si vous avez besoin de plus de puissance de traitement, vous pouvez effectuer un scale-up pour ajouter davantage de processeurs ou de RAM à la machine virtuelle. À l’inverse, si vous vous rendez compte que vous avez surestimé les besoins, vous pouvez effectuer un scale-down en réduisant les spécifications du processeur ou de la RAM.

![Alt text](image-2.png)

#### Décrire les avantages de la fiabilité et de la prévisibilité dans le Cloud

##### Fiabilité
La fiabilité est la capacité d’un système à reprendre son activité après une défaillance et à continuer à fonctionner. C'est également l'un des piliers du cadre Microsoft Azure Well-Architected.
vous pouvez deployer vos ressources sur l'echelle mondiale en toute fiabilité sans se souci de comment elles seront deployes.

Vous en saurez davantage sur la façon dont Azure tire parti de la mise à l’échelle au niveau à l'échelle mondiale pour garantir la fiabilité, plus loin dans cette série.


##### Prévisibilité et Performances dans le Cloud
La prévisibilité des performances et des coûts est fortement influencée par le cadre Microsoft Azure Well-Architected. Déployez une solution construite autour de ce cadre et vous avez une solution dont les coûts et les performances sont prévisibles.

La prévisibilité des performances se concentre sur la prédiction des ressources nécessaires pour offrir une expérience positive à vos clients. La autoscaling, l’équilibrage de charge et la haute disponibilité sont quelques-uns des concepts Cloud qui prennent en charge la prévisibilité des performances. Si vous avez soudainement besoin de plus de ressources, la autoscaling peut déployer des ressources supplémentaires pour répondre à la demande, puis se réduire lorsque la demande diminue. Ou, si le trafic est fortement concentré dans une zone, l'équilibrage de charge aidera à rediriger une partie de la surcharge vers des zones moins stressées" in the Performance section.


#### Décrire les avantages de la sécurité et de la gouvernance dans le Cloud
Qu’il s’agisse d’un déploiement de type infrastructure as a service ou software as a service, les fonctionnalités cloud prennent en charge la gouvernance et la conformité.
Selon votre modèle opérationnel, des patchs et mises à jour logiciels peuvent également être appliqués automatiquement, ce qui contribue à la fois à la gouvernance et à la sécurité.

Au niveau de la sécurité, vous pouvez trouver une solution cloud correspondant à vos besoins. Si vous souhaitez un contrôle maximal de la sécurité, le modèle infrastructure as a service vous fournit les ressources physiques mais vous laisse gérer les systèmes d’exploitation et les logiciels installés ainsi que les patchs et la maintenance. Si vous souhaitez que les patchs et la maintenance soient pris en charge automatiquement, les déploiements de type platform as a service ou software as a service sont peut-être les meilleures stratégies cloud.

#### Décrire les avantages de la facilité de gestion dans le cloud
L’un des principaux avantages du cloud computing réside dans les options de facilité de gestion. Il existe deux types de facilité de gestion pour le cloud computing.

* Gestion du Cloud
* Gestion dans le Cloud


#### Gestion du cloud
La gestion du cloud correspond à la gestion de vos ressources cloud. Dans le cloud, une organisation peut :

- Mettre à l’échelle automatiquement le déploiement des ressources selon les besoins.
- Déployer les ressources en fonction d’un modèle préconfiguré, ce qui permet d’éliminer le recours à une configuration manuelle.
- Effectuer le monitoring de l’intégrité des ressources et le remplacement automatique des ressources défaillantes.
- Recevoir des alertes automatiques basées sur des métriques configurées, ce qui vous permet de connaître les performances en temps réel.

#### Gestion dans le cloud
La gestion dans le cloud indique la façon dont vous pouvez gérer votre environnement et vos ressources cloud. L'entreprise peut les gérer :

- Via un portail web.
- Via une interface de ligne de commande.
- Via des API.
- En utilisant PowerShell.


#### MICROSOFT - AZURE 

- Décrire les régions, les paires de régions et les régions souveraines Azure
- Décrire les zones de disponibilité.
- Décrire les centres de données Azure.
- Décrire les ressources et les groupes de ressources Azure.
- Décrire les abonnements.
- Décrire les groupes d’administration.
- Décrire la hiérarchie des groupes de ressources, des abonnements et des groupes d’administration.




Navigation dans le bac à sable  avec l’interface de ligne de commande (CLI): Get -date pour obtenir la date actuelle 

Les commandes azure commence par la lettre az : az version 

Erp : {                                                                       
  "azure-cli": "2.55.0",
  "azure-cli-core": "2.55.0",
  "azure-cli-telemetry": "1.1.0",
  "extensions": {
    "ai-examples": "0.2.5",
    "ml": "2.22.0",
    "ssh": "2.0.2"
}
}

On peut utiliser l’interface CLI bash en entrant tout simplement bash dans Azure Cloud Shell

PS /home/mvoumbi> bash
mvoumbi [ ~ ]$ : mode bash donc on peut utiliser les commandes bash qu’on a habitude d’uitliser

et si on veut revenir en mode Shell il suffit d’entré pwsh

az upgrade
az interactive : permet d’utiliser le mode interactif Azure CLI 

lorsque le mode interactif est lancer plus besoin de d’enter az :

donc-🡪 version au lieu de az version

pour sortie entrant la commande exit

LES PRINCIPAUX COMPOSANTS ARCHITECTURAUX D’AZURE :

Ils sont divisés en deux composantes essentilles
Infrastructure physique 
Infrastructure de gestion

À la base de l’infrastructure physique d’Azure se trouvent les centres de données. D’un point de vue conceptuel, les centres de données s’apparentent à des centres de données de grandes entreprises. Il s’agit d’installations dont les ressources sont organisées dans des racks, avec une alimentation, un système de refroidissement et une infrastructure réseau dédiés.
En tant que fournisseur de services cloud mondial, Azure dispose de centres de données dans le monde entier. Cependant, ces centres de données individuels ne sont pas directement accessibles. Les centres de données sont regroupés dans des régions Azure ou des zones de disponibilité Azure conçues pour vous faire bénéficier d’une résilience et d’une fiabilité pour vos charges de travail vitales pour l’entreprise.

Zones de disponibilité
Les zones de disponibilité sont des centres de données physiquement séparés au sein d’une région Azure. Chaque zone de disponibilité est composée d’un ou de plusieurs centres de données équipés d’une alimentation, d’un refroidissement et d’un réseau indépendants. Une zone de disponibilité est configurée pour être une limite d’isolation. Si une zone de disponibilité tombe en panne, l’autre continue à fonctionner. Les zones de disponibilité sont connectées via des réseaux en fibre optique privés très rapides.





Paires de régions
La plupart des régions Azure sont associées à une autre région au sein d’une même zone géographique (par exemple États-Unis, Europe ou Asie) distante d’au moins 480 kilomètres. Cette approche permet la réplication de ressources à l’échelle d’une zone géographique, ce qui contribue à réduire les risques d’interruptions liées à des événements tels que des catastrophes naturelles, des troubles civils, des coupures de courant ou des pannes de réseau physique affectant une région entière. Par exemple, si une région formant une paire est touchée par une catastrophe naturelle, les services basculent automatiquement vers l’autre région de la paire de régions.





Décrire l’infrastructure de gestion Azure
Effectué 100 XP 
7 minutes
L’infrastructure de gestion comprend des ressources et des groupes de ressources, des abonnements et des comptes Azure. La compréhension de l’organisation hiérarchique vous aidera à planifier vos projets et produits dans Azure.

Ressources et groupes de ressources Azure
Une ressource est le bloc de construction de base d’Azure. Tout ce que vous créez, provisionnez, déployez, etc. est une ressource. Les machines virtuelles, les réseaux virtuels, les bases de données, les services cognitifs, etc. sont tous considérés comme des ressources dans Azure.


Création d'une VM à l'aide du portail Azure

1. Connectez-vous au portail Azure.

2. Sélectionnez Créer une ressource > Calcul > Machine virtuelle > Créer.

3. Le volet Créer une machine virtuelle s’ouvre sur l’onglet De base.

4. Vérifiez ou entrez les valeurs suivantes pour chaque paramètre. Si un paramètre n’est pas spécifié, laissez la valeur par défaut.


Paramètre                        Valeur
Abonnement                       Abonnement Concierge
Groupe de ressources                 Sélectionnez le nom du groupe de ressources qui commence par learn.
Nom de la machine virtuelle        my-VM
Région                                   Conservez la valeur par défaut
Options de disponibilité           Conservez la valeur par défaut
Type de sécurité             Conservez la valeur par défaut
Image                              Conservez la valeur par défaut
Architecture de machine virtuelle    Conservez la valeur par défaut
Exécuter avec la remise Azure Spot   Désactivé
Taille                             Conservez la valeur par défaut
Type d'authentification            Mot de passe
Nom d’utilisateur                    azureuser
Mot de passe                       Entrez un mot de passe personnalisé
Confirmer le mot de passe          Entrez à nouveau le mot de passe personnalisé
Aucun port d’entrée public         Aucun

5. Sélectionnez Vérifier et créer.

6. Sélectionner Créer
![Alt text](image-6.png)



Une fois que le déploiement a été créé, on peut vérifier la VM créée et toutes les ressources associées à la VM.

Pour ce faire,

1. Sélectionnez Accueil
2. Sélectionnez Groupes de ressources

3. Sélectionnez le groupe de ressources learn-9a4d3258-8f01-4123-86a2-090ecde575cd



### Décrire les services de calcul et réseau Azure

Dans ce module nous allons étudier les 3 option de calcul sur les VM, les conteneurs et les fonctions Azure.

il y'a deux manière de mettre à l'échelle les VM dans Azure
- Groupe identique des VM
- Groupe à haute disponibilité

Voici quelques exemples ou cas d’usage courants de machines virtuelles :

* Pendant le test et le développement. Les machines virtuelles offrent un moyen simple et rapide de créer différentes configurations de système d’exploitation et d’application. Le personnel chargé des tests et du développement peut ensuite facilement supprimer les machines virtuelles quand il n’en a plus besoin.

* Lors de l’exécution d’applications dans le cloud. La possibilité d’exécuter certaines applications dans le cloud public, par opposition à la création d’une infrastructure traditionnelle pour les exécuter, peut apporter des avantages économiques substantiels. Par exemple, une application peut avoir besoin de gérer les fluctuations de la demande. Arrêter des machines virtuelles lorsque vous n’en avez pas besoin ou les démarrer rapidement pour répondre à une augmentation soudaine de la demande signifie que vous payez uniquement pour les ressources que vous utilisez.

* Lors de l’extension de votre centre de données vers le Cloud : une organisation peut développer les capacités de son propre réseau local en créant un réseau virtuel dans Azure et en ajoutant des machines virtuelles à ce réseau virtuel. Des applications telles que SharePoint peuvent ensuite s’exécuter sur une machine virtuelle Azure au lieu de s’exécuter localement. Cette configuration permet de procéder à un déploiement plus simple ou moins onéreux que dans un environnement local.

* Pendant une reprise d’activité après sinistre : tout comme avec l’exécution de certains types d’applications dans le cloud et l’extension d’un réseau local au cloud, vous pouvez faire des économies significatives en suivant une approche IaaS pour la reprise d’activité après sinistre. En cas de panne du centre de données principal, vous pouvez créer des machines virtuelles s’exécutant sur Azure pour exécuter vos applications critiques, puis les arrêter quand le centre de données principal redevient opérationnel.


## La migration vers le Cloud avec les VMs

Les machines virtuelles constituent également un excellent choix quand vous passez d’un serveur physique au cloud (également appelé « lift-and-shift »). Vous pouvez créer une image du serveur physique et l’héberger dans une machine virtuelle avec peu ou pas de changements. Tout comme un serveur sur site physique, vous devez maintenir la VM : vous êtes responsable de la maintenance du système d'exploitation installé et du logiciel

# Tache 1 : Création d'une VM Lunix et installer Nginx

il faut se connecter au bac à sable ou à Azure Cloud Shell

az vm create --resource-group "learn-b2ef0595-4422-417e-8385-811627a0a255" --name my-vm --public-ip-sku Standard --image Ubuntu2204 --admin-username azureuser --generate-ssh-keys


Pour configurer la VM il faut entrée: 

az vm extension set --resource-group "learn-b2ef0595-4422-417e-8385-811627a0a255" --vm-name my-vm --name customScript --publisher Microsoft.Azure.Extensions --version 2.1 --settings '{"fileUris":["https://raw.githubusercontent.com/MicrosoftDocs/mslearn-welcome-to-azure/master/configure-nginx.sh"]}' --protected-settings '{"commandToExecute": "./configure-nginx.sh"}'

réponse de la config sous un script bash: 

#!/bin/bash

# Update apt cache.
sudo apt-get update

# Install Nginx.
sudo apt-get install -y nginx

# Set the home page.
echo "<html><body><h2>Welcome to Azure! My name is $(hostname).</h2></body></html>" | sudo tee -a /var/www/html/index.html



# Décrire Azure Virtual Desktop

C'est un service de virtualisation des postes de travail et des applications qui s'exécute dans le cloud. Il vous permet d’utiliser une version cloud de Windows depuis n'importe quel endroit.

Avec Azure Virtual Desktop, les données et les applications sont séparées du matériel local. le bureau réel et les applications s’exécutent dans le cloud, ce qui réduit le risque de laisser des données confidentielles sur un appareil personnel. De plus, les sessions utilisateur sont isolées dans des environnements à session unique et multi-session.


# Décrire les conteneurs Azure

# Comparaison entre VM et conteneurs : 2 techniques de virtualisations des applications



![Alt text](image-3.png)


### MICROSOFT-CERTIFIED : Azure Data Scientist Associate


=======
>>>>>>> bff3bf7ed9e8abee4590e6e9cd49b123f82441bb
