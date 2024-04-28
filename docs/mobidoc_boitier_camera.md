# Caméra pour Mobidoc
## 1/ Introduction
La caméra est l'élément central de la station de documentation mobidoc. La documentation de [l'atelier des chercheurs](https://latelier-des-chercheurs.fr/) propose d'utiliser une webcam USB. J'ai fais le choix d'utiliser plutôt une camér raspberry pour sa facilité d'usage avec une raspberry pi.

J'ai donc choisis la configuration suivante :
 * D'utiliser la pi cam HQ (Haute Qualité).
 * Avec un convertisseur CSI HDMI pour avoir un câble HDMi qui est plus facile à manipuler que la nappe. 
 * Un objectif à focale variable. 
 
<section style="border: 2px solid; padding: 20px; border-radius:20px;" >
Cette version est un dérivé du travail produit par l'atelier des chercheurs :
	<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://latelier-des-chercheurs.fr/docs/station-de-documentation">Mobidoc</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://latelier-des-chercheurs.fr/">L'atelier des chercheurs</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>
</section>


## 2/ Matériel et fournitures
### 2.1 Fournitures

|Dénomination|Visuel|Mes fournitures|Qt|
|------|------|-----|--|
|Pi camera HQ|![Picam HQ](https://assets.raspberrypi.com/static/ee30c4f49820a9787a203666ccd64c37/9ff6b/03b5b033-5aca-40a7-ae4a-1592a9403890_CAM%2BHERO%2BALT%2B2.webp)|[GoTronic](https://www.gotronic.fr/art-camera-hq-12-mpx-c-cs-sc0261-33781.htm)|1|
|Convertisseur CSI HDMI pour pi cam|![Convertisseur CSI HDMI](https://www.gotronic.fr/ar-extension-camera-csi-via-hdmi-b0091-34398.jpg)|[Gotronic](https://www.gotronic.fr/art-extension-camera-csi-via-hdmi-b0091-34398.htm)|1 lot de 2|
|Câble HDMI|||1|
|Filament PETG ou PLA pour imprimante 3D|||4m|
|Vis M2*8mm|||4|
|Visserie M2,5||||
|Vis M6*30mm tête hexagonale|||1|
|Ecrou M6|||1|
|Entretoises en laiton M2,5*5+5mm|||3|
|Entretoises en laiton M2,5*11+6mm|||3|
|Rondelles M2,5|||3|

### 2.2 Matériel
 * Imprimante 3D ;
 * Clés alens ;
 * Tournevis ;

### 2.3 Impressions
 * Boitier pour caméra Pi HQ ;
 * Couvercle pour caméra Pi HQ :
 * Rotule ;
 * Rotule femelle ;
 * 2 vis ;

## 3/ Assemblage
 * Positionner l'écrou M6 dans son emplacement au fond du boîtier ;
![Positionner l'écrou M6]()
 * Insérer la vis M6*30mm dans la rotule ;
 * Visser la rotule à l'arrière du boitier ; 
![Visser la rotule]()
 * Rassembler, 4 vis M2*8mm et un convertisseur CSI HDMI ;
![Rassembler, 4 vis M2*8mm et un convertisseur CSI HDMI]()
 * Positionner le convertisseur CSI HDMI ;
 * Veiller à placer le connecteur HDMI face à l'ouverture ;
 * Visser le convertisseur au fond du boîtier à l'aide d'une clé allen ;
![Positionnement du convertisseur CSI HDMI]()
 * Rassembler 3 entretoises en laiton M2,5*5+5mm ;
![Rassembler 3 entretoises en laiton]()
 * Visser les 3 entretoises aux emplacements prévus ; 
![Visser les 3 entretoises]()
 * Connecter la nappe à la picam. Attention ! La partie bleu doit se retrouver sur le dos de la caméra.
![Connecter la nappe]()
 * Rassembler 3 entretoises M2,5*11+6mm et 3 rondelles M2,5;
![Rassembler 3 entretoises M2,5*11+6mm et 3 rondelles M2,5]()
 * Positionner la piCam sur son emplacement ;
 * La maintenir en vissant les 3 entretoises avec une rondelle pour supprimer le jeu ;
 * Visser l'objectif en enlevant la bague C-CS ; 
![Positionner la caméra]()

 * Refermer le couvercle ;
 * Il sera nécessaire pour cela de retirer temporairement les 2 vis de réglages de l'objectif. 
 * Visser le couvercle.
 

## Licence
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://remorque-atelier.readthedocs.io/fr/latest/">Mobidoc</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://www.guillaumeleguen.xyz/">Guillaume Leguen</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>

Cette version est un dérivé du travail produit par l'atelier des chercheurs :
<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://latelier-des-chercheurs.fr/docs/station-de-documentation">Mobidoc</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://latelier-des-chercheurs.fr/">L'atelier des chercheurs</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC-SA 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"></a></p>