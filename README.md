# Projet de Robot Humanoïd InMoov

![dd](https://user-images.githubusercontent.com/65183668/84666953-040e0d00-af22-11ea-8e1c-515a02e23173.jpg)

InMoov est le premier robot Open Source à taille humaine entièrement imprimé en 3d.
Répliquable sur n’importe quelle petite imprimante 3D avec une surface d’impression de 12x12x12cm, celui-ci est conçu comme une plateforme de développement autant pour les Universités, les Laboratoires que pour les Hobbyistes. Son concept basé sur le partage et la communauté, fait qu’il est déjà répliqué pour un bon nombre de projets partout à travers le monde.

Site Officiel de InMoov: [[http://inmoov.fr|]]

## Etape 1: Liste du matériel
----
La première étape du projet sera de créer un index avec toutes les pièces et le matériel nécessaire à la création du robot. Vous pouvez trouver la liste standard sur le site officiel ainsi que le mapping par défaut de l'électronique à cette adresse :[[http://inmoov.fr/default-hardware-map]].

Voici la liste du matériel que nous avons utilisé:

#### Général

Composante | Nombre
--- | ---
Arduino Mega   | 2
NervoBoard: http://inmoov.fr/shop/ | 1
Camera Hercules HD  | 1 ou 2
Screw Allen countersunk M3x20MM   | 75
Screw Allen countersunk M4x20MM   | 75
Screw Allen countersunk M8x100MM   | 25
Phillips Flat-Head Wood Screws M3x12MM  | 150
Phillips Flat-Head Wood Screws M4x20MM  | 100
0,8mm braided /fishing line. 200LB  | 100M

#### Main et avant-bras

Composante | Nombre
--- | ---
servos HK15298B   | 10
servos MG996r   | 2
1500gr natural PLA  | 1
extension spring 5mm diameter, 1cm length(13/64″x13/16″)  | 10

#### Biceps et Epaule

Composante | Nombre
--- | ---
servos Hitec HS805BB | 8 
1500gr natural PLA  | 1

#### Tête et torse

Composante | Nombre
--- | ---
servos Hitec HS805BB HEAD 4 AXIS   | 2
servos HK15298B JAW MECHANISM   | 1
Servo DS929hvCorona EYE MECHANISM   | 3
5500gr natural PLA  | 1
eFuel switch Power supply 6V-15V Output 20Amps.  | 1
Mini PC speaker 4Ohm 6W | 2
PIR sensor retriggered | 1
Cables and wires | -

#### Estomac

Composante | Nombre
--- | ---
servos Hitec HS805BB	   | 2
Vigor VSD-11AYMB or CYS model S8218  | 2

#### Pièces imprimées en 3D

[[http://inmoov.fr/inmoov-stl-parts-viewer/|La librairie]] des pièces à imprimer en 3D se trouve sur le site officiel de InMoov

## Etape 2: Fabrication du Robot
----
### Mains et avant-bras

Imprimer les pièces suivantes issues du site officiel de [[http://inmoov.fr/inmoov-stl-parts-viewer|InMoov]] : 

  * 1x Thumb
  * 1x Index
  * 1x Majeure
  * 1x Auriculaire
  * 1x Pinky
  * 1x Bolt_entretoise
  * 1x Wristlarge
  * 1x Wristsmall
  * 1x topsurface
  * 1x coverfinger
  * 1x robcap3
  * 1x robpart2
  * 1x robpart3
  * 1x robpart4
  * 1x robpart5
  * 1x rotawrist2
  * 1x rotawrist1
  * 1x rotawrist3
  * 1x WristGears
  * 1x CableHolderWrist



Les pièces nécessiteront très certainement d'être retravaillés et sablés, limés pour que l'assemblage puisse se faire.


#### Chapitre 1 - Le lit des servos

![14537018_10209079147327184_2104450424_o](https://user-images.githubusercontent.com/65183668/84666894-fbb5d200-af21-11ea-821d-0863c0223987.jpg)

Commencez par assembler les pièces Robpart2 et Robpart5 ainsi que les pièces Robpart3 et  Robpart4. Pour cela plusieurs solutions existent. Nous avons choisi d'assembler les pièces en les soudant grâce à un Doodler ou crayon 3D. Vous pouvez également utiliser de la colle epoxy.



![14825615_10209330587413029_1803931665_n](https://user-images.githubusercontent.com/65183668/84666908-fd7f9580-af21-11ea-8b92-d7f3a6afa3c9.jpg)
Dans la pièce Robpart5, insérez deux écrous de 4mm de diamètre. Si les écrous ne rentrent pas correctement, vous pouvez les chauffer avec un pistolet à air chaud et enfoncer l'écrou à l'aide d'une pince



![14877070_10209330601613384_819280263_n](https://user-images.githubusercontent.com/65183668/84666929-007a8600-af22-11ea-9744-0ee8b696cd5a.jpg)
Fixez maintenant le tensioneur au servo-bed en le vissant. L'image ci-contre montre l'assemblage final.



![14885918_10209330591373128_1677111359_n](https://user-images.githubusercontent.com/65183668/84666939-01abb300-af22-11ea-909d-a3954651b9a1.jpg)
![14793937_10209330595013219_1128035763_n](https://user-images.githubusercontent.com/65183668/84666899-fc4e6880-af21-11ea-9e68-0ea17bc369a3.jpg)
Limez ensuite le servo-bed pour qu'il rentre correctement dans la pièce Robpart5 et sécurisez avec deux vis à bois de 3mm de diamètre



![14872701_10209330603213424_4607447_n](https://user-images.githubusercontent.com/65183668/84666917-feb0c280-af21-11ea-83f5-7e04a058b5b9.jpg)
Vous pouvez maintenant fixer les servos moteur au servo-bed.



![14826187_10209330606093496_693523336_n](https://user-images.githubusercontent.com/65183668/84666911-fd7f9580-af21-11ea-9c04-3a3953601275.jpg)
![14877895_10209330608173548_1648792011_n](https://user-images.githubusercontent.com/65183668/84666934-01131c80-af22-11ea-9cb4-e3d0b8336db5.jpg)
![14874944_10209330602653410_1764824731_n](https://user-images.githubusercontent.com/65183668/84666919-feb0c280-af21-11ea-93d2-d6fc26599d73.jpg)
Repercez des trous avec un forêt de 2mm de diamètre sur la pièce ServoPulley. Vissez ensuite la tête de servo (pièce en plastique blanche sur la photo) qui venait avec le servo à la pièce ServoPulley. Coupez et limez la partie des vis qui dépasse.



![arduinopowersupply1](https://user-images.githubusercontent.com/65183668/84666951-040e0d00-af22-11ea-889e-f06090bb8b2c.png)

Il est maintenant temps d'utiliser votre arduino pour positionner tous les servos à leur zéro. Pour cela connectez les servos comme sur l'image à droite et téléversez le script qui suit à l'arduino. Une fois tous les servos à zéro, vissez les têtes de servos.

```
#include <Servo.h>

Servo servothumb;          // Define thumb servo
Servo servoindex;          // Define index servo
Servo servomajeure;
Servo servoringfinger;
Servo servopinky;
Servo servowrist;
Servo servobiceps;
Servo servorotate;
Servo servoshoulder;
Servo servoomoplat;
Servo servoneck;
Servo servorothead;

void setup() { 
  servothumb.attach(2);  // Set thumb servo to digital pin 2
  servoindex.attach(3);  // Set index servo to digital pin 3
  servomajeure.attach(4);
  servoringfinger.attach(5);
  servopinky.attach(6);
  servowrist.attach(7);
  servobiceps.attach(8);
  servorotate.attach(9);
  servoshoulder.attach(10);
  servoomoplat.attach(11);
  servoneck.attach(12);
  servorothead.attach(13);
  
} 

void loop() {            // Loop through motion tests
  alltovirtual();        // Example: alltovirtual
  delay(4000);           // Wait 4000 milliseconds (4 seconds)
//alltorest();           // Uncomment to use this
//delay(4000);           // Uncomment to use this
//alltomax();            // Uncomment to use this
//delay(2000);           // Uncomment to use this
 
  
 
}
// Motion to set the servo into "virtual" 0 position: alltovirtual
void alltovirtual() {         
  servothumb.write(0);
  servoindex.write(0);
  servomajeure.write(0);
  servoringfinger.write(0);
  servopinky.write(0);
  servowrist.write(0);
  servobiceps.write(0);  
  servorotate.write(20);    //Never less then (20 degree)
  servoshoulder.write(30);  //Never less then (30 degree)
  servoomoplat.write(10);   //Never less then (10 degree)
  servoneck.write(0);
  servorothead.write(0);
}
// Motion to set the servo into "rest" position: alltorest
void alltorest() {         
   servothumb.write(0);
  servoindex.write(0);
  servomajeure.write(0);
  servoringfinger.write(0);
  servopinky.write(0);
  servowrist.write(0);
  servobiceps.write(0);     
  servorotate.write(90);    //Never less then (20 degree)
  servoshoulder.write(30);  //Never less then (30 degree)
  servoomoplat.write(10);   //Never less then (10 degree)
  servoneck.write(90);
  servorothead.write(90);
}



// Motion to set the servo into "max" position: alltomax
void alltomax() {
  servothumb.write(180);
  servoindex.write(180);
  servomajeure.write(180);
  servoringfinger.write(180);
  servopinky.write(180);
  servowrist.write(180);
  servobiceps.write(85);      //Never more then (85 or 90degree)
  servorotate.write(110);     //Never more then (110 degree)
  servoshoulder.write(130);   //Never more then (130 degree)
  servoomoplat.write(70);     //Never more then (70 degree)
  servoneck.write(180);
  servorothead.write(180);
 
}

```

#### Chapitre 2 - Un poignet solide
![14813726_10209330602213399_1425257949_n](https://user-images.githubusercontent.com/65183668/84666904-fce6ff00-af21-11ea-9270-112cabbc4d70.jpg)
 Commencer par retirer le support d'impression de la pièce RotaWrist1.


![14813486_10209330614653710_1569073861_n](https://user-images.githubusercontent.com/65183668/84666903-fc4e6880-af21-11ea-880d-2705d60c33cb.jpg)
![14875355_10209330616533757_2109052605_n](https://user-images.githubusercontent.com/65183668/84666926-ffe1ef80-af21-11ea-987c-eb180a41f241.jpg)

Coller les pièces RotaWrist1 et Robpart2 ensemble.



![14886093_10209330604893466_1287679062_n](https://user-images.githubusercontent.com/65183668/84666940-02444980-af22-11ea-8966-fb78cc707001.jpg)
![14826318_10209330605373478_252957937_n](https://user-images.githubusercontent.com/65183668/84666914-fe182c00-af21-11ea-82f2-a81fa8337348.jpg)
Insérer et sécuriser le servo MG996 avec des vis à bois où les vis fournies avec le servo. Ce servo permet une rotation sur 180 degrés.



![14875234_10209330619413829_320311069_n](https://user-images.githubusercontent.com/65183668/84666924-ff495900-af21-11ea-9e16-c89d7af9e0fd.jpg)
Insérer le petit engrenage imprimé en 3D dans la tête de servo.



![14875177_10209330621613884_103538102_n](https://user-images.githubusercontent.com/65183668/84666920-feb0c280-af21-11ea-831f-0d7780a58f95.jpg)
Coller la pièce CableHolderWrist sur le servo avec de la colle chaude ou de l'epoxy.



![14813743_10209330629374078_697909758_n](https://user-images.githubusercontent.com/65183668/84666907-fd7f9580-af21-11ea-9b71-51a9e6b65522.jpg)
![14877195_10209330630014094_335057588_n](https://user-images.githubusercontent.com/65183668/84666930-007a8600-af22-11ea-940b-31dbda64f34d.jpg)
Assembler les pièces RotaWrist3, RotaWrist2 et l'engrenage ensemble. Ajouter de la graisse sur l'engrenage pour la lubrification.



#### Chapitre 3 - Des doigts agiles


![14826357_10209330645094471_157082954_n](https://user-images.githubusercontent.com/65183668/84666916-fe182c00-af21-11ea-8b50-ef7e06dabf45.jpg)
![14875186_10209330643574433_309624239_n](https://user-images.githubusercontent.com/65183668/84666923-ff495900-af21-11ea-92b7-e94c20ce422c.jpg)
Retravailler (lime et perçage) et assembler les doigts. Le tutoriel de Gaël Langevin peut vous aider: https://www.youtube.com/watch?v=0t2uhAyf2-c&t=0s



#### Chapitre 4 - Assemblage


Il faut mainteant prendre une décision en ce qui concerne les capteurs de pression au niveau des doigts. Il y a trois trous dans la pièce WristLarge. Les trous du milieu correspondent aux trous pour les fils des capteurs.


![14877912_10209330645614484_1570921748_n](https://user-images.githubusercontent.com/65183668/84666935-01131c80-af22-11ea-8a04-8da7134db07f.jpg)
![14885780_10209330645734487_704509598_n](https://user-images.githubusercontent.com/65183668/84666938-01abb300-af22-11ea-8115-be5678bfe2d4.jpg)
Couper 10 fil de 75cm de long dans le fil de pêche. Insérer les fils dans les trous de la pièce Wristlarge. Passer également les fils électriques si vous choisissez la version avec les capteurs de pression.



![14875392_10209330646534507_1356990718_n](https://user-images.githubusercontent.com/65183668/84666927-ffe1ef80-af21-11ea-938e-5e9df3825aa6.jpg)
![14886209_10209330646934517_615485775_n](https://user-images.githubusercontent.com/65183668/84666941-02444980-af22-11ea-9f32-73e4afdad10d.jpg)
![14877013_10209330647614534_1831833427_n](https://user-images.githubusercontent.com/65183668/84666928-ffe1ef80-af21-11ea-81d4-f73bbca5063b.jpg)
Passer ensuite les fils dans le poignet.



![14877872_10209330648174548_1022353349_n](https://user-images.githubusercontent.com/65183668/84666932-01131c80-af22-11ea-81f3-46ecba3d2c56.jpg)
Relier la main, le poignet et l'avant bras.



![14813738_10209330649294576_768310113_n](https://user-images.githubusercontent.com/65183668/84666906-fce6ff00-af21-11ea-8859-028fef1b1646.jpg)
Attacher les fils aux servos moteurs. Vous pouvez utiliser les ressorts pour garder la tension dans les fils comme sur l'image ci-contre. Lors de cette étape, il faut que les servos soient à zéro ou à 180°



### Biceps

#### Chapitre 1 : Hacker des servos




![14826235_10209330650814614_964250519_n](https://user-images.githubusercontent.com/65183668/84666912-fe182c00-af21-11ea-805f-2fee50e6a7f8.jpg)
![15450944_10209730921301126_1261817229_n](https://user-images.githubusercontent.com/65183668/84666950-040e0d00-af22-11ea-8486-540c36f05a7b.jpg)
La première étape est un petit hack du servo. Dans un premier temps il faut ouvrir le servo. Commencer par dessouder le moteur et retirer le pcb. Sortir ensuite le potentiomètre du servo. avant de ressouder et refermer le servo, il faut couper la partie du plus gros engrenage qui sert de frein. 


#### Chapitre 2 : Un biceps énorme et sec


![15355852_10209730921661135_160754325_n](https://user-images.githubusercontent.com/65183668/84666942-02444980-af22-11ea-9348-a3d58d4fdfbf.jpg)
{{ :projets:15356894_10209730942021644_1738978765_n.jpg?nolink&150|}}
![15401459_10209730939821589_475638466_n](https://user-images.githubusercontent.com/65183668/84666946-02dce000-af22-11ea-9238-55b0008077c0.jpg)
Assembler ensemble les pièces RotmitV1 et RotgearV1. L'assemblage doit contenir les trois pièces comme sur les images ci-contre.



![15356080_10209730928701311_1845123894_n](https://user-images.githubusercontent.com/65183668/84666943-02dce000-af22-11ea-8cb7-125e6fd1e067.jpg)
![15415913_10209730947941792_1036767612_n](https://user-images.githubusercontent.com/65183668/84666947-03757680-af22-11ea-9db8-aa72fa6a0eaa.jpg)
Fixer le servo moteur sur l'assemblage puis fixer la vis sans fin sur la tête de servo. Vous pouvez tester l'assemblage avec le code arduino. Le tout doit tourné sans bruit et de façon fluide. Avant de fermer l'assemblage, il faut ajouter de la graisse.



![15356994_10209730948901816_1682317291_n](https://user-images.githubusercontent.com/65183668/84666945-02dce000-af22-11ea-8aac-04e6f367d74c.jpg)
Refermer l'assemblage et placer le potentiomètre dans le support prévu. Il faut tester la rotation du bras pour placer correctement le potentiomètre.



![15416058_10209730956101996_1746648175_n](https://user-images.githubusercontent.com/65183668/84666948-03757680-af22-11ea-9c7a-76ad9bd927ff.jpg)
![15435721_10209730962222149_926330082_n](https://user-images.githubusercontent.com/65183668/84666949-03757680-af22-11ea-9d04-7310318ca7b3.jpg)
Assembler les pièces higharmV1 et rotmitV1 ensemble. Attention, si vous utilisez du PLA pour l'impression il est nécessaire de le chauffer avec un pistolet thermique (heatgun) pour éviter la casse.




### Epaules et torse

En construction FIXME

### Tête

En construction FIXME

### Estomac

En construction FIXME

## Etape 3: Installation et utilisation de MyRobotLab
----
FIXME
