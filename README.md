# OC-ASRS-Projet-8-Supervisez-le-SI-d-une-entreprise
OpenClassrooms : Administrateur Systèmes, Réseaux et Sécurité 2024-2025
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Qu'allez-vous apprendre dans ce projet ?

Votre rôle sera de mettre en œuvre un système de supervision de la performance d’un site web, en utilisant des outils tels que Nagios et RSyslog. Vous configurerez les sondes pour surveiller divers paramètres. Votre mission comprendra également la rédaction de documentation détaillée pour chaque sonde, expliquant les mesures à prendre en cas d'alerte ou d'incident.
 
En quoi ces compétences sont-elles importantes pour votre carrière ?

Les compétences que vous allez développer au cours de ce projet sont cruciales pour assurer une supervision efficace du système d'information. Vous apprendrez à gérer les données de supervision pour prévenir et résoudre rapidement les incidents, garantissant ainsi la fiabilité et la performance du site web. Ces compétences sont essentielles pour tout administrateur système désireux de maintenir une infrastructure IT robuste et réactive.

 
Prêt à démarrer votre projet ?

Vous allez réaliser un projet réaliste, présenté sous forme de mission en entreprise. Il se rapproche d'une mission typique effectuée sur le terrain.

Le projet est découpé en trois sections :

    Mission - Présentation, qui présente le contexte de votre mission,
    Mission - Détails, qui présente les détails de la mission, sous forme d’échanges avec les collègues,
    Livrables et Soutenance, qui décrit les livrables à fournir et le déroulement de la soutenance de validation.

Prenez soin de lire le projet en entier avant de commencer, pour comprendre ce qui est attendu de vous.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Mission - Présentation

L’entreprise MediaSanté, une entreprise spécialisée dans la mise à disposition de données de santé, reçoit depuis quelque temps des plaintes quant à la vitesse de chargement de son site web. 
Un ensemble de points de couleur verte et bleue font apparaître une croix de pharmacie à coté du titre médiasanté écrit en noir.

Vous êtes embauché en freelance par la directrice de MediaSanté pour un contrat consistant à installer des sondes permettant de surveiller le futur site web.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Mission - Détails

En vous connectant ce matin, vous découvrez un mail de la directrice de MediaSanté.

 

De : Megan Nielsen
À : Moi
Objet : Mise en place d’un superviseur et de sondes sur notre site web. Détails de la mission.

Bonjour, 

 

Suite à notre conversation téléphonique, voici comme convenu notre confirmation par écrit. Nous avons bien reçu ton devis suite à notre besoin d'évaluation de la vitesse de chargement de notre site web, et j’ai le plaisir de t’informer que nous venons de le valider. 

 

L'équipe technique souhaite que tu vérifies les points suivants avec chaque sonde, et que tu suives les différentes étapes de cette checklist (Tu pourras suivre aussi leur procédure virtualbox si besoin).

Pourras-tu nous fournir un tableau des indicateurs à suivre avec leurs noms, leurs fonctions, et leurs paramètres pour déclencher un warning ou une alerte ?

Tu trouveras en pièce jointe notre logo à intégrer sur le site WordPress.

 

Une fois que ton travail sera testé et validé, on le passera en production. 

 

N'oublie pas de rédiger la documentation du système de supervision afin que nous puissions agir en cas d’incident. En gros, pour chaque sonde, il nous faut les commandes et mesures à prendre en cas d’alerte. 

 

Je reste à ta disposition pour tout complément d’information, n'hésite pas à solliciter l’équipe si besoin !

 

Très bonne journée à toi et à bientôt,

 

Cordialement,

Megan Nielsen
Directrice MediaSanté

Pièce jointe : 
Média Santé logo
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Livrables et soutenance
Livrables du projet

    Une copie d’écran montrant la configuration Nagios des deux machines au format PNG,
    Une archive .tar.gz contenant les fichiers de configuration de RSyslog pour chaque machine .gz.
    Un tableau des indicateurs à suivre avec leur nom, leur fonction et leurs paramètres, pour déclencher un warning ou une alerte, sous format PDF
    La documentation du système de supervision au format PDF avec pour chaque sonde, les mesures à prendre en cas d’incident (commande Linux et/ou mesure).

Pour faciliter votre passage devant le jury, déposez sur la plateforme, dans un dossier zip nommé “Titre_du_projet_nom_prénom”, tous les livrables du projet comme suit : Nom_Prénom_n° du livrable_nom du livrable_date de démarrage du projet. Cela donnera : 

    Nom_Prenom_1_config_nagios_mmaaaa
    Nom_Prenom_2_config_Rsyslog_mmaaaa
    Nom_Prenom_3_indicateurs_mmaaaa
    Nom_Prenom_4_documentation_mmaaaa

Par exemple, le premier livrable peut être nommé comme suit : Dupont_Jean_1_X_012022.
 
Bannière annonçant la soutenance du projet

Durant la présentation orale, l’évaluateur interprétera le rôle de Megan Nielsen. La soutenance est structurée de la manière suivante :

    Présentation des livrables (15 minutes) 
        Vous présenterez les 7 sondes qui vous permettent de vérifier l’état du serveur web puis la configuration de RSyslog entre les deux serveurs.
        Vous présenterez la documentation du système de supervision.

    Discussion (10 minutes) 
        L’évaluateur jouera le rôle de Megan. Il vous challengera sur les points suivants :
            Rôle de chaque sonde Nagios.
            Paramétrage et rôle de RSyslog.
            La précision de votre documentation de supervision.

    Débriefing (5 minutes)
        À la fin de la soutenance, l'évaluateur arrêtera de jouer le rôle de Megan pour vous permettre de débriefer ensemble.

Votre présentation devrait durer 15 minutes (+/- 5 minutes). Puisque le respect des durées des présentations est important en milieu professionnel, les présentations en dessous de 10 minutes ou au-dessus de 20 minutes peuvent être refusées.
 

Vous disposez désormais de l’intégralité des éléments nécessaires à la bonne réalisation du projet, à vous de jouer !
