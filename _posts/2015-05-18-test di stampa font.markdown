---
published: true
title: Test di stampa font
layout: post
---
Grazie a dei test di stampa effettuati prima del mio arrivo con la prima stampante, era stata individuata una serie di font che fossero facilmente stampabili e leggibili e che fossero di tipologie distinte tra di loro. Tra questi ne sono stati selezionati 5 con cui partire su cui proseguire i test.  

![font1](https://raw.githubusercontent.com/Giuzzo/Giuzzo.github.io/master/link_img/14-01.jpg) ![font2](https://raw.githubusercontent.com/Giuzzo/Giuzzo.github.io/master/link_img/14-02.jpg)

Tutti i font selezionati hanno licenza libera, scaricabili da [fontsquirrel.com](http://www.fontsquirrel.com/) o a questo [link](https://github.com/Giuzzo/Giuzzo.github.io/tree/master/fonts_testati).
Come visibile nell'immagine sovrastante per ogni font sono state definite delle dimensioni minime di stampa.

*NB* Caratteri o disegni con spessore di linea troppo ridotti non sono supportati dal profilo di [Cura](https://github.com/Giuzzo/Giuzzo.github.io/tree/master/profili_cura) precedentemente testato, in tal caso è necessario ridurre il parametro "Nozzle Size".

In ogni caso il profilo di stampa ottimale è legato alla tipologia di cioccolato che si sta utilizzando ed alle condizioni di temperatura ambientale.

Qui sotto sono visibili le foto dei test.

![latin modern](https://raw.githubusercontent.com/Giuzzo/Giuzzo.github.io/master/link_img/16.jpg)

![leckerlie one](https://raw.githubusercontent.com/Giuzzo/Giuzzo.github.io/master/link_img/17.jpg)

![noto serif](https://raw.githubusercontent.com/Giuzzo/Giuzzo.github.io/master/link_img/18.jpg)

![quicksand bold](https://raw.githubusercontent.com/Giuzzo/Giuzzo.github.io/master/link_img/19.jpg)

![raleway bold](https://raw.githubusercontent.com/Giuzzo/Giuzzo.github.io/master/link_img/20.jpg)

Per ottenere gli STL dei vari testi in modo rapido è stato utilizzato il software di grafica [Inkscape](https://inkscape.org/it/) e la sua estenzione [PathsToOpenScad](http://www.thingiverse.com/thing:25036).
Nelle impostazioni di esportazione i parametri inseriti sono stati extrude=0.6 e smooth=0 (in modo da ottenere testi formati da un solo livello di stampa.
Aprendo il file .scad così ottenuto con [OpenScad](http://www.openscad.org/) è sufficente processarlo (F6) ed esportarlo in STL.

In alternativa è possibile utilizzare l'applicazione [123d Design](http://www.123dapp.com/design) all'interno della quale può essere importato direttamente un file .svg. Tuttavia l'estrusione in questo caso va fatta in modo manuale ed in generale l'operazione risulta essere più lenta.

Tutti i software sopra citati hanno licenza libera.

Ovviamente è possibile ottenere i file STL importando i testi in formato cad in qualsiasi programma di modellazzione.
