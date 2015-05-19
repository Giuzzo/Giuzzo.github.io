---
published: true
title: Font monoline
layout: post
---
Oltre ad i font selezionati si è cercato di svillupare un modo per poter ottenere un testo scritto con una linea unica continua (senza che l'estrusore si stacchi mai dal piano all'interno della stessa parola) in modo da ottenere un'effetto simile a quello di una **scrittura calligrafica**.

Il primo tentativo è stato quello di ottenere un STL in cui il corpo delle lettere fosse formato da una singola superficie e non da un volume.

Semplificando il problema alle due dimensioni,normalmente tutti i font hanno un proprio corpo che viene scalato in funzione delle proprie dimensioni.
E' stato possibile ottenere dei testi che fossero formati da una linea di spessore noto a prescindere dal corpo del testo grazie ad un'estenione del software di grafica os [Inkscape](https://inkscape.org/).

L'estensione in questione utilizza dei Font Hershey, ed è scaricabile a  [questo link](http://www.evilmadscientist.com/2011/hershey-text-an-inkscape-extension-for-engraving-fonts/) nel quale sono presenti anche le istruzioni per l'installazione e l'utilizzo.

![testoHershey](https://github.com/Giuzzo/Giuzzo.github.io/blob/master/link_img/21.JPG?raw=true)

Una volta scritto il testo desiderato è possibile esportarlo in un formato CAD e ricavare l'STL estrudendo la geometria su un qualunque programma di modellazione per superfici. Nel caso specifico è stato utilizzato il software [Rhinoceros](https://www.rhino3d.com/it/).

Ovviamente non è possibile in questo caso semplificare l'operazione con OpenScad come descritto nel [post precedente](http://giuzzo.github.io/2015/05/18/test%20di%20stampa%20font.html), in quanto non è possibile utilizzare softwares che lavorino per solidi in quanto questi non permettono l'estrusione di una linea senza spessore.

Una volta importato l'STL così ottenuto all'interno di Cura non è però stato possibile ottenere un gcode che permettesse di avere una stampa monoline del tutto corretta.
Sarà quindi necessario approfondire l'argomento in futuro.
