# Orendain-Guifi

Orendaingo Guifi.Net sareareari buruzko eskuliburua.

## Sarrera

Orendaingo Guifi.Net sarearen  elementuak azalduko dira dokumentu honetan, nola konfiguratzen diren, nola konpondu arazoak daudenean, mantenu lanak nola egiten diren eta bezero berriak sarera lotzeko zer egin behar den.

## Sarearen deskribapena

Orendaingo Guifi.Net sarea hiru osagai nagusiz osatuta dago:

* Herriaren zuntz sarea, kultur etxeko rack-etik kaskoko ia etxe guztietara doana. Etxe bakoitzera zuntz dedikatu bat doa, ez da PON erako egitura bat.
* Kultur etxeko rack-a. Bertan router nagusia, zuntza optikoko sitema, antenen alimentagailuak eta UPSa (bateria sistema argia joaten bada) daude. Movistarrek bere FTTH zuntz kaxa bat jarri du rack-aren ondoan.
* Kultur etxeko antenakAntenek zuntza iristen ez den etxeetara ematen du seinalea, Urkolamendiko errepikagailura eta Guifi.Net-eko gainontzeko sarera konektatzea ahalbidetzen du.
* Urkolamendiko errepikagailua. Kultur etxera begira antena bat du eta beste bat seinalea banatzeko.

## Sarearen osagaiak

### Herriko zuntz sarea

Herriko zuntz sarea zuntz monomodo-ko 12 hariko 10 mangeraz osatua dago, arketetan torpedoak daudelarik banatzeko.

### Kultur etxeko rack-eko aparailuak

Kultur etxeko rack-eko aparailuen deskripzioa, goitik behera hasita. 

<img src="media/Orendain_rack_1.jpg" alt="drawing" width="500"/>

Aparailua                                                               | Norena                   | Arduraduna    | Zertarako    
------------------------------------------------------------------------|--------------------------|---------------|-------------------------------------------------
Kaskoko etxe bakoitzera zuntz irteerak  (4 rack unitate)                | Orendaingo herriarenak   | ?             | Etxe bakoitzera doan zuntza ordenatuta jartzeko
Zuntza banatzeko espiludun aparailuak (Spliterr-ak)                     | Orendaingo herriarenak   | ?             | OLT-tik irtetzen den argia banatzeko (64 aldiz banatu liteke gehienez)
Huawei SmartAX MA5608T OLT aparailua                                    | Guifi.Net fundazioarena  | ?             | GPON erako zuntza sare bat kudeatze ahalbidetzen du
Mikrotik RB2011 routerra                                                | Orendaino herriarena     | ?             | OLTra konektatutako bezeroak, antenen sarea eta interneterako irteerak kudeatzen ditu
Antenen alimentagailua                                                  | Orendaino herriarena     | ?             | Antenei argi indarra ematen die
Antenetara konexio panela                                               | Orendaino herriarena     | ?             | Antenetara konexioak era txukun batean jartzen ditu

### Kultur etxeko antenak

Kultur etxe gainean antenak daude kokatuta. Antenak dauden egitura Televes etxearen 360 sistemako mastillekin eginda dago, oinarri bat eta puntera bat erabiliz, punteran tubo bat du sartuta. Bientoekin lotuta dago eta guztira 7 metroko altuera izango du. Antenaren oinarritik 80mm-ko bi tubo jaisten dira rack-a dagoen tokira.

Antenen deskribapena goitik behera.

<img src="media/Orendain_Antenak.jpg" alt="drawing" width="500"/>

Antena                                                                  | Norena                   | Arduraduna    | Zertarako    
------------------------------------------------------------------------|--------------------------|---------------|-------------------------------------------------
Mikrotik OmniTik antena                                                 | Orendaingo herriarenak   | ?             | Zuntza ez duten etxeei interneta ahalbidetu. Alde guztitara zabaltzen du seinalea (ominidirekzionala da), baina indar gutxirekin
Ubiquiti Rocket M5 + AM-5G20-90 antena - Hegoaldera begira              | Orendaingo herriarenak   | ?             | Zuntza ez duten etxeei interneta ahalbidetu
Ubiquiti Rocket M5 + AM-5G20-90 antena - Iparraldera begira             | Orendaingo herriarenak   | ?             | Zuntza ez duten etxeei interneta ahalbidetu
Ubiquiti NanoBeam                                                       | ?                        | ?             | ?
Ubiquiti PowerBeam - ¿Baliarrainera begira?                             | ?                        | ?             | ¿Baliarraingo udaletxeko Guifi.Net supernodoarekin konektatu?
Ubiquiti PowerBeam - Ollaunera begira                                   | ¿Orendaingo herriarenak? | ?             | Ollaun mendiko Guifi.Net supernodoarekin konektatu
Ubiquiti PowerBeam AC 400 ISO antena - Urkolamendira begira             | Orendaingo herriarenak   | ?             | Urkolamendiko Supernodo errepikagailura konektatu
Ubiquiti PowerBeam AC 620 antena - Usurbera begira                      | Orendaingo herriarenak   | ?             | Usurbeko Guifi.Net supernodoarekin konektatu - Talaia-ren Interneteko sarbidea ahalbidetu

## Dokumentazioa

Proiektu originalaren dokumentazioa honakoa da:

