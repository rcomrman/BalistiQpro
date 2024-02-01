Projet de Simulateur Balistique avec Interface Kivy et Reconnaissance Vocale
Description
Ce projet vise à créer un simulateur balistique interactif avec une interface utilisateur développée en Kivy. L'application permet à l'utilisateur de choisir un fusil de sniper, de fournir des informations telles que l'angle de tir, la vitesse et la direction du vent, puis simule la trajectoire du projectile. De plus, la reconnaissance vocale est intégrée pour permettre à l'utilisateur de fournir certaines informations en parlant.

Prérequis
Assurez-vous d'avoir les bibliothèques nécessaires installées. Vous pouvez le faire en exécutant la commande suivante :

bash
Copy code
pip install kivy matplotlib numpy pyttsx3 SpeechRecognition
Veuillez noter que l'installation de PyAudio peut nécessiter des dépendances supplémentaires. Vous pouvez suivre les instructions spécifiques à votre système d'exploitation ici.

Structure du Projet
main.py: Le script principal qui lance l'application Kivy.
sniper_images/: Dossier contenant les images des fusils de sniper.
README.md: Ce fichier explicatif.
Comment Utiliser l'Application
Exécutez le script main.py en utilisant Python.
Sur la première page, cliquez sur l'image du sniper que vous souhaitez utiliser. Suivez les instructions en haut de la page.
Une fenêtre de simulation apparaîtra, demandant des informations telles que l'angle de tir, la vitesse et la direction du vent, ainsi que l'écart de la représentation graphique.

continuité du projet :
un système de reconnaissance vocal étais intégré a la base, mais les ordinateurs de l'écoles ne comportant pas de micro je n'ai pue avoir la confirmation du bon fonctionnenment et ai donc supprimer cette option
une application mobile étais envisager ce qui n'a pue aboutir par manque de temps 
