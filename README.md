# Titre du Notebook: Modélisation des Accidents de la Route

## Présentation du projet 
Ce projet vise à analyser et prédire la gravité des accidents de la route en France, en utilisant des données ouvertes fournies par le site data.gouv.fr, le portail français de l'open data. L'ensemble de données se compose de quatre fichiers CSV distincts, chacun apportant des informations cruciales sur les accidents de la route, les lieux où ils se sont produits, les véhicules impliqués, et les victimes concernées.











# Databricks-Accidents-Project

Examen : Créer et héberger un modèle prédictif

# Azure configuration 

1.   Créer un groupe de ressources nommé votre-nom-iut-sd3-exam (exemple : dupont-iut-sd3-exam) localisé en North Europe.

/// aller sur azur microsoft

Faire -> https://portal.azure.com/#home

/// crée une ressource group 

Faire -> Create a ressource 

/// configuration ressource group 

Ressource group -> LESUR-nom-iut-sd3-exam

Region -> North Europe

3.  Créer une instance Azure Databricks dans ce groupe de ressource avec les configurations suivantes :

/// crée une un environement databricks  

Faire -> Create an Azure Databricks workspace

/// configaration databricks

Workspace name ->  LESUR-iut-sd3-databricks

Region : North Europe

Pricing Tier : Premium (+ Role-based access controls)



 
# Databricks configuration 


1.	Créer un cluster avec les configurations ci-dessous :
/// creation du cluster
Faire -> Compute (create compute)

# Cluster configuration 
/// Configuration du cluster   
o	Name : iut_sd3_exam
o	Policy : Unrestricted
o	Single node
o	Access mode : No isolation shared
o	Databricks Runtime Version : 14.2 ML (Spark 3.5.0, Scala 2.12)
o	⚠️ Ne pas utiliser Photon Acceleration
o	Node type : Standard DS3 v2 14GB Memory, 4 Cores
o	Terminate after : 60 min of inactivity


 






