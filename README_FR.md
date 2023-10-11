Matériel un OrangePi5Plus lien fournisseur officiel version 16Gb DDR4:

[<img src="https://raw.githubusercontent.com/bbaranoff/OPi5Plus_Media_Center/main/pi5-plus-26.png"  width="50%" height="50%">](https://fr.aliexpress.com/item/1005005585029938.html?gatewayAdapt=glo2fra)

Une alimentation adaptée (IMPORTANT !!!!!) celle-ci par exemple attention aussi à bien prendre la "couleur" EU dans AliExpress (vous risquez d'avoir du mal à brancher un plrise américaine !)

[<img src="https://raw.githubusercontent.com/bbaranoff/OPi5Plus_Media_Center/ef955da02e8918e0d673091ec93c00e14725298e/Orange-Pi-5-adaptateur-d-alimentation-5V-4a-chargeur-20W-USB-Type-C-prise-EU-US.jpg" width="20%" height="20%">](https://fr.aliexpress.com/item/1005005078736401.html?gatewayAdapt=glo2fra)

Télécharger balenaEtcher pour Windows:

[<img src="https://raw.githubusercontent.com/bbaranoff/OPi5Plus_Media_Center/main/balena_logo.svg" width="20%" height="20%">](https://github.com/balena-io/etcher/releases/download/v1.18.11/balenaEtcher-Setup-1.18.11.exe)

Télécharger l'image OPi5Plus_Media_Center 

[<img src="https://raw.githubusercontent.com/bbaranoff/OPi5Plus_Media_Center/main/Library.jpg" width="20%" height="20%">](https://drive.google.com/file/d/19eOtLbYPvVjBqDh5ySviZfLc3JrUll1e/view?usp=sharing)

Une fois téléchargé,ouvrir balena etcher :
![](balena.png)

Après selectionner "Flash From file"
Séléctionnez votre carte SD
FLASH
Mettez votre carte SD sur l'OrangePi

!! Il n'y a pas de jeux ni de source pour les chaines vous devez donc les trouver vous même...
L'image est faite pour qu'un support NVMe se monte directement sur /home/paris/Retropie
vous devez donc avoir dans le NVMe un dossier roms avec le nom de vos consoles exemple (nvme_root)/roms/n64/mario_kart.n64 qui sera automatiquement monté sur /home/paris/Retropie/roms/n64/mario_kart.n64
