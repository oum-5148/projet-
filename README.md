
# *Tunisair-ENSI travel agency* ✈️
once you start the application , you will first have to identify as a client or as an admin , for the record each one has its own functions and purpose .

![enter image description here](https://scontent.ftun4-2.fna.fbcdn.net/v/t1.15752-9/321788408_688534736149337_714876014067655136_n.png?_nc_cat=109&ccb=1-7&_nc_sid=ae9488&_nc_ohc=2KCjPUQn4UYAX-IAbv1&_nc_ht=scontent.ftun4-2.fna&oh=03_AdTRJRSr5bejdvTfdI7mgIJ5R8kNQQ03Nh7okh9TYuBuDQ&oe=63D7CC6A)


1 - Client  : 

![enter image description here](https://scontent.ftun4-2.fna.fbcdn.net/v/t1.15752-9/321421683_486335763582485_5731640649417185805_n.png?_nc_cat=106&ccb=1-7&_nc_sid=ae9488&_nc_ohc=xuPiUBwFjTkAX8Y6Y0g&_nc_ht=scontent.ftun4-2.fna&oh=03_AdTqvKvflF5N33nbgkPA3Bf8kOoZjyt2Hboi4Wu4LJbJ3w&oe=63D7C4D6)

 - **saisir un voyage** : 
 this calls the function named `ajout-voyage()` that takes different inputs from user to fill out the details of the trip such as destination , date , hotel...
 
 ![enter image description here](https://scontent.ftun4-2.fna.fbcdn.net/v/t1.15752-9/322812534_838588790735285_3295141610088920335_n.png?_nc_cat=108&ccb=1-7&_nc_sid=ae9488&_nc_ohc=trRtRFwIrREAX9Sb641&_nc_ht=scontent.ftun4-2.fna&oh=03_AdT3RIkRySn-H5MUzghydxLrBdDNXEYQJcS5PSWDRjSIUQ&oe=63D7A6AA)
 
 - **chercher un voyage** : 
 
 ![enter image description here](https://scontent.ftun4-2.fna.fbcdn.net/v/t1.15752-9/321524182_3526220397660270_8658667390714568446_n.png?_nc_cat=105&ccb=1-7&_nc_sid=ae9488&_nc_ohc=Z0XfI_JYvxcAX8wEfQO&tn=YpVRh6Bn7I98kOjE&_nc_ht=scontent.ftun4-2.fna&oh=03_AdQBL1OixYqqnFW34K_UCIWsF3nQB20GcJ9YxE3jWIJp4Q&oe=63D7D130)
 
 There are two ways to look for a trip :
- the first calls a function named `rechercher()` that allows you to narrow your research by entering two dates , it then displays the flights in between those dates .
- the second calls a function named `rechercher1()` that displays the flights available on a specific date entered by the user . 
 
 ⛔The trips are stocked in a file named  `basededonnee`  that has all of the available trips in the format **(departure/destination/date)** . 
- **Afficher le panier :** 

![enter image description here](https://scontent.ftun4-2.fna.fbcdn.net/v/t1.15752-9/322021579_558974679132298_2590757437353603709_n.png?_nc_cat=104&ccb=1-7&_nc_sid=ae9488&_nc_ohc=MWicBp3TldAAX_EV4-w&_nc_ht=scontent.ftun4-2.fna&oh=03_AdTB_-fQMSsGHaaKkmQbbq_jHmSQOZsiGnjP3rHP1s1o7g&oe=63D79AE9)

- afficher la drescription : 
  this calls a function named `panier()` that displays the trips that were booked with all of their details. 
 
 ![enter image description here](https://scontent.ftun4-2.fna.fbcdn.net/v/t1.15752-9/322148287_828730438192317_3089172347572780044_n.png?_nc_cat=103&ccb=1-7&_nc_sid=ae9488&_nc_ohc=g1JKy4h5V68AX_BYq2C&_nc_ht=scontent.ftun4-2.fna&oh=03_AdQ9h-QR45-IRYyh9fe3o7qofmS6ZzR2BtGjdcpcAKI9ig&oe=63D7AE9B)
 
 - Supprimer un voyage : 
   this fisrt displays the booked trips by calling `panier()` then calls a function named  `supprimer()` that take the ID of a trip as a parameter and deletes it  .
  - modifier un voyage : 
   this fisrt displays the booked trips by calling `panier()` then calls a function named  `modif()` that take the ID of a trip as a parameter and allows the user to change certain informations about a trip . 
  
  ![enter image description here](https://scontent.ftun4-2.fna.fbcdn.net/v/t1.15752-9/321651025_530471715700174_8639122817600823490_n.png?_nc_cat=102&ccb=1-7&_nc_sid=ae9488&_nc_ohc=MeBkUA0axlMAX-AIHs_&_nc_ht=scontent.ftun4-2.fna&oh=03_AdTHcOnjfFtus08Y_LP3hWET7e5DaxaWcVI1NI1naMumVA&oe=63D7C8BF)

2- Admin : 

![enter image description here](https://scontent.ftun4-2.fna.fbcdn.net/v/t1.15752-9/322658543_644067050831027_1201658255945126309_n.png?_nc_cat=111&ccb=1-7&_nc_sid=ae9488&_nc_ohc=M_ap4XdrprIAX_cxy5C&tn=YpVRh6Bn7I98kOjE&_nc_ht=scontent.ftun4-2.fna&oh=03_AdSUDhZM3C0dEMC1p3cl-SDD1lqwJP0y0ClEPkILOd7WPw&oe=63D7C3CE)

- **saisir un voyage** : 
this calls a function named `saisir()` that allows the admin to add any number of new trips to the file **basededonnee** .  

![enter image description here](https://scontent.ftun4-2.fna.fbcdn.net/v/t1.15752-9/321422546_1534899770347113_7568654052852880242_n.png?_nc_cat=103&ccb=1-7&_nc_sid=ae9488&_nc_ohc=45JOWJopIwgAX_29USV&_nc_ht=scontent.ftun4-2.fna&oh=03_AdQmn87vZxvbCG57_DONP84FP6a-p5SHNHGAbs40PIUAMg&oe=63D7C62F)

- **afficher toutes les voyages** : 
this calls a function named `afficher()` that takes the date base's name ( which is a file ) as a parameter and displays all of its content . 

![enter image description here](https://scontent.ftun4-2.fna.fbcdn.net/v/t1.15752-9/322125148_1103452113662303_8178863986054934208_n.png?_nc_cat=110&ccb=1-7&_nc_sid=ae9488&_nc_ohc=Yl1Yg8knEmYAX8VA4T7&tn=YpVRh6Bn7I98kOjE&_nc_ht=scontent.ftun4-2.fna&oh=03_AdSyBH8eTilTnOHbdprPWvHmXlsvDdS7PdvfRWdo73A5zw&oe=63D7B53A)
