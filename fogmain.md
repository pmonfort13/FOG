# INSTALACIO D'UN SERVIDOR FOG

`Octavian Mihalcea`
`Pau Monfort`

## Index
* Introducció
* Instal·lar i configurar FOG Project
* Capturar client Windows
* Capturar client Ubuntu
* Instal·lar imatge Windows
* Instal·lar imatge Ubuntu
* Instal·lar snapin


## Introducció


## Instal·lar i configurar 

Abans d'instal·lar el FOG, hem preparat la maquina on farem l'instal·lació amb un ubuntu i posar-li una IP estàtica:

![imatge](/fotos/image11.png)

Anem a la web de FOG Project i descarreguem l'instal·lador amb _tar.gz_
![imatge](/fotos/image16.png)

El descomprimim i executem l'script _./install.sh_ que hi ha dins de la carpeta /bin:
Seguim la instalació i les preguntes que ens va fent, ho deixem tot per defecte i configurem la IP del server:
![imatge](/fotos/image17.png)

![imatge](/fotos/image12.png)

Un cop instal·lat, anem al navegador i entrem a la IP del server per obrir la interficie gràfica del FOG:
![imatge](/fotos/image5.png)

Abans de configurar-lo, hem de canviar uns parametres del DNS i instalar _DNSMASQ_ per evitar problemes de dns:
![imatge](/fotos/image22.png)

![imatge](/fotos/image19.png)

![imatge](/fotos/image8.png)

I ja estaria preparat el FOG per treballar!


## Capturar desde client Windows:

Un cop tot configurat, anem al menú d'imatges i crer _una nova imatge_
Li posem un nom _windows10_ i selecionem el sistema operatiu
![imatge](/fotos/image15.png)

Ara hem d'obrir la màquina de la que volem capturar la imatge i iniciar-la per xarxa, a le sopcions que ens surten, seleccionem `Quick Registration and Inventory`:
![imatge](/fotos/image10.png)

Si comprovem al FOG podem veure que ens surt un nou host registrat:
![imatge](/fotos/image24.png)

Entrem dintre i li associem la imatge _WINDOWS10_ que hviem creat abans
![imatge](/fotos/image7.png)

Ara ja podem anar a `Basic Tasks` i capturar el dispositiu:
![imatge](/fotos/image23.png)

Quan tornem a iniciar la màquina a capturar, se'ns iniciarà directament per xarxa i ens sortirà el proces de captura i automaticament començarà a clonar la màquina:
![imatge](/fotos/image1.png)


## Capturar desde client Ubuntu:

Creem una imatge amb el Sistem Operatiu Ubuntu i seguidament iniciem la màquina Ubuntu que volem capturar per xarxa i fem el `Quick Registration and Inventory`: 
![imatge](/fotos/image9.png)

Podem comprovar que ens surt la imatge al FOG tot i que surt amb el logo de Windows, si entrem veurem que és Ubuntu:

![imatge](/fotos/image10.png)

Li assignem la imatge Ubuntu per desar-la
![imatge](/fotos/image21.png)

I a `Basic Tasks` configurem per iniciar la Captura del dispositiu:
![imatge](/fotos/image6.png)

Quan tornem a iniciar la màquina a capturar, se'ns iniciarà directament per xarxa i ens sortirà el proces de captura i automaticament començarà a clonar la màquina:
![imatge](/fotos/image23.png)



## Instal·lar imatge Windows:

Per instal·lar la imatge Windows, hem agafat una maquina qualsevol que tenim, en aquest cas la windows_fog de la que haviem capturat pero ja haviem fet canvis, com per exemple canviar el fons:
![imatge](/fotos/image26.png)

Per instal·lar-li la imatge, hem d'iniciar per xarxa i selecciona l'opció de `Deploy Image`:
![imatge](/fotos/image4.png)

Seguidament per qüestions de seguretat, ens demanarà _usuari_ i _contrasenya_ del FOG server
![imatge](/fotos/image14.png)

I ens deixarà escollir la imatge que volem instal·lar-li:
![imatge](/fotos/image3.png)

Quan li donem _enter_ començarà la instal·lació que pot tardar un poc però es farà ot automàtic:
![imatge](/fotos/image2.png)

Finalment, s'inicia la màquina i veiem que està en l'estat que estava quan la vam capturar i tot instalat correctament:
![imatge](/fotos/image27.png)


## Instal·lar imatge Ubuntu:

Entrem a la màquina que volem instal·lar l'ubuntu i iniciem per xarxa i seleccionem l'opció `Deploy Image`:
![imatge](/fotos/image18.png)

Posem l'usuari i contrasenya del FOG:
![imatge](/fotos/image14.png)

I seleccionem la imatge d'ubuntu que volem instal·lar:
![imatge](/fotos/image3.png)

Quan li donem _enter_ començarà la instal·lació que pot tardar un poc però es farà ot automàtic:
![imatge](/fotos/image25.png)


## Instal·lar paquet snaping:

Per a crear un paquet snaping haurem d’anar a snaping managment. Aquí crearem un nou snaping. En el nostre cas utilitzarem el paquet 7zip, el qual es un paquet amb extensio .msi.
![imatge](/fotos/image20.png)


![imatge](/fotos/image28.png)

![imatge](/fotos/image29.png)

![imatge](/fotos/image30.png)

![imatge](/fotos/image31.png)

![imatge](/fotos/image32.png)

![imatge](/fotos/image33.png)

![imatge](/fotos/image34.png)

![imatge](/fotos/image35.png)

![imatge](/fotos/image36.png)

![imatge](/fotos/image37.png)

![imatge](/fotos/image38.png)



## Capturar imatge client Windows 

## Capturar imatge client Ubuntu

## Instal·lar imatge Windows

## Instal·lar imatge Ubuntu

## Instal·lar paquet amb snapping


