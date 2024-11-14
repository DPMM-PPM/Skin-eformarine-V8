
# skin-eform Marine

=======

Skin ILIAS 8 - eformarine

Ce dépôt contient le skin personnalisé pour ILIAS 8. Suivez les instructions ci-dessous pour installer le skin sur votre instance ILIAS.
Prérequis

    Accès à une instance ILIAS 8.
    Accès SSH ou accès direct au serveur où ILIAS est installé.
    Git installé sur votre serveur (pour la méthode de clonage).

Instructions d'installation
Méthode 1 : Cloner le dépôt GitHub

    Connectez-vous à votre serveur via SSH ou accédez directement au répertoire d'installation d'ILIAS.

    Naviguez vers le répertoire Customizing/global/skin de votre instance ILIAS :

cd /chemin/vers/votre/instance/ILIAS/Customizing/global/skin

Clonez le dépôt GitHub dans le répertoire eformarine :

    git clone https://github.com/vincent-sayah/skin-eform.git eformarine

Méthode 2 : Télécharger le fichier ZIP

    Allez sur la page du dépôt GitHub : skin-eform.

    Cliquez sur le bouton "Code" et sélectionnez "Download ZIP".

    Téléchargez le fichier ZIP sur votre ordinateur.

    Décompressez le fichier ZIP.

    Connectez-vous à votre serveur via SSH ou accédez directement au répertoire d'installation d'ILIAS.

    Naviguez vers le répertoire Customizing/global/skin de votre instance ILIAS :

cd /chemin/vers/votre/instance/ILIAS/Customizing/global/skin

Téléchargez le contenu du fichier ZIP décompressé dans le répertoire eformarine :

    unzip /chemin/vers/le/fichier/zip/skin-eform-main.zip -d eformarine

Étape 2 : Vérifier l'installation

    Assurez-vous que le répertoire eformarine a été créé et contient les fichiers du skin :

    ls eformarine

    Vérifiez que les fichiers du skin sont correctement installés et qu'il n'y a pas d'erreurs de permission.

Étape 3 : Activer le skin dans ILIAS

    Connectez-vous à l'interface administrateur d'ILIAS.
    Allez dans le menu "Administration" > "Skin and Style".
    Sélectionnez le skin "eformarine" et activez-le pour votre instance ILIAS.

Étape 4 : Tester le skin

    Accédez à votre instance ILIAS et vérifiez que le skin "eformarine" est correctement appliqué.
    Testez les différentes pages et fonctionnalités pour vous assurer que le skin fonctionne comme prévu.

Mise à jour du skin

Pour mettre à jour le skin avec les dernières modifications du dépôt GitHub, suivez ces étapes :
Méthode 1 : Cloner le dépôt GitHub

    Naviguez vers le répertoire eformarine :

cd /chemin/vers/votre/instance/ILIAS/Customizing/global/skin/eformarine

Récupérez les dernières modifications du dépôt GitHub :

    git pull origin main

Méthode 2 : Télécharger le fichier ZIP

    Allez sur la page du dépôt GitHub : skin-eform.

    Cliquez sur le bouton "Code" et sélectionnez "Download ZIP".

    Téléchargez le fichier ZIP sur votre ordinateur.

    Décompressez le fichier ZIP.

    Connectez-vous à votre serveur via SSH ou accédez directement au répertoire d'installation d'ILIAS.

    Naviguez vers le répertoire Customizing/global/skin de votre instance ILIAS :

cd /chemin/vers/votre/instance/ILIAS/Customizing/global/skin

Téléchargez le contenu du fichier ZIP décompressé dans le répertoire eformarine :

    unzip /chemin/vers/le/fichier/zip/skin-eform-main.zip -d eformarine

    Vérifiez que les fichiers ont été mis à jour correctement.

Support

Pôle pédagogie Marine (PPM) - Vincent SAYAH


>>>>>>> e818123 (initial commit)
