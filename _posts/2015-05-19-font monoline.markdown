---
published: true
title: Font monoline
layout: post
---
Oltre ad i font selezionati si è cercato di svillupare un modo per poter avere un testo scritto con una linea unica continua (senza che l'estrusore si stacchi mai dal piano all'interno della stessa parola) in modo da ottenere un'effetto simile a quello di una **scritta calligrafica**.

Il primo tentativo è stato quello di ottenere un STL in cui il corpo delle lettere fosse formato da una singola superficie e non da un volume.
Tutti i font tradizionali hanno un proprio corpo che viene scalato in funzione delle proprie dimensioni, è stato possibile ottenere dei testi che fossero formati da una linea di spessore noto a prescindere dal corpo del testo grazie ad un'estenione del software di grafica os [Inkscape](https://inkscape.org/).

L'estensione in questione utilizza dei Font Hershey, ed è scaricabile al [link](http://www.evilmadscientist.com/2011/hershey-text-an-inkscape-extension-for-engraving-fonts/) nel quale sono presenti anche le istruzioni per l'utilizzo.

![testoHershey](https://github.com/Giuzzo/Giuzzo.github.io/blob/master/link_img/21.JPG?raw=true)

Una volta scritto il testo desiderato è possibile esportarlo in un formato CAD e ricavare l'STL estrudendo la geometria su un qualunque programma di modellazione per superfici. Nel caso specifico è stato utilizzato il software [Rhinoceros](https://www.rhino3d.com/it/).

Ovviamente al contrario di quanto scritto nel post precedente non è possibile utilizzare programmi di modellazione che lavorino per solidi.

Una volta importato l'STL così ottenuto all'interno di Cura non è però stato possibile ottenere un gcode che permettesse di avere una stampa monoline del tutto corretta.
Sarà quindi necessario approfondire l'argomento in futuro.
