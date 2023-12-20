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
### MICROSOFT-CERTIFIED : Azure Data Scientist Associate


=======
>>>>>>> bff3bf7ed9e8abee4590e6e9cd49b123f82441bb
