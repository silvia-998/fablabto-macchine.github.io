# Vinylcut

## Cosa si può fare con la Vinylcut
È un macchinario a controllo numerico utilizzato per il taglio di fogli di plastica autoadesiva (chiamata vinile) e materiali in fogli con uno spessore massimo di 0,5 mm.    
[Per maggiori informazioni](https://en.wikipedia.org/wiki/Vinyl_cutter)

Tramite vinylcut si possono produrre banner, striscioni, prespaziati, grafica veicolare, insegne, segnaletica, vetrofanie, retroilluminati, stencil e termo-adesivi per magliette. È inoltre possibile trasformare la macchina in un plotter da disegno a penna, grazie ad appositi adattatori. 

[esempio 1](inserire immagine)   
Foto e link dell'esempio.

Esempi di lavorazione. (Applicazioni)

## Strumenti e file 
Per il taglio dei vinili è ovviamente necessaria una Vinylcut con tutti i suoi accessori utili. Questa deve però essere collegata ad un computer (fornito dal Fablab) contenente i driver e i programmi necessari. Infine serve il materiale da tagliare, è possibile portarlo da fuori, ma se ne può trovare un ampio campionario in sede.   

<!-- Sostituire immagine con foto del tavolo con tutto sopra. Mettere scritte per dire cosa sono i vari elementi (Campionario, PC, schermo, vinylcut ecc.) -->
![foto campionario](cambio foto) 

### Vinylcutter Roland CAMM-1 SERVO GX-24

| Caratteristiche tecniche           | Valori                                   |   
|:-----------------------------------|:-----------------------------------------|   
| Velocità di taglio                 | Da 10 a 500 mm/sec. (tutte le direzioni) |   
| Pressione della lama               | Da 30 a 250 gf                           |   
| Risoluzione del Software           | 0,025 mm/passo                           |   
| Spessore massimo del materiale     | 0,5 mm                                   |   
| Larghezza del materiale caricabile | Da 50 a 700 mm                           |   
| Grandezza massima area di taglio   | Larghezza: 584 mm Lunghezza: 25 m        |   
| Grandezza minima area di taglio    | Larghezza:  Lunghezza:                   |   
| Precisione di ripetizione          | ±0.1 mm o inferiore                      |      

Per informazioni più specifiche consultare la [scheda tecnica](src/Scheda-tecnica.pdf) e il [manuale dell'utente](/vinylcut/src/users-manual-en.pdf)

<!-- Aggiungere foto della Vinylcut con i nomi delle componenti principali -->

### Materiali
I materiali più utilizzati sono [vinile](http://www.tosingraf.com/vinili-adesivi-da-stampa-e-taglio.html), [poliestere](https://www.cplfabbrika.com/transfer/transfer-laser/poliestere-adesivo-stampabile.html) e [sandblast](https://www.fcsrl.com/categoria-prodotto/vinile-per-sabbiatura/), ma gestisce tranquillamente anche materiali più pesanti come [PVC flessibili](https://www.sinovinyl.com/product/color-pvc-graphic-cutting-vinyl-roll-film/), [floccati](https://tuttotransfer.it/termoadesivi-flex-e-flock-/termoadesivi-flock-floccato-velluto-scamosciato/) e [vinili riflettenti](https://stampacontinua.it/index.php?route=product/category&path=1437_1441).   
Lo spessore e le dimensioni del materiale dipendono dal macchinario e dalla lama di taglio, vedere le [caratteristiche tecniche](#vinylcutter-roland-camm-1-servo-gx-24)

### PC coi software
Computer con sistemi operativi successivi a Windows 98 SE.   
I plotter da taglio Roland sono equipaggiati con il software [CutStudio](https://www.rolanddg.it/prodotti/software/roland-cutstudio-software). Il software consente di creare loghi e scritte e di modificarli, allargandoli, ruotandoli, specchiandoli e scalandoli.

### File 
Il computer presente in laboratorio e collegato alla Vinylcut possiede i software necessari alle fasi di [preparazione del file](#preparare-il-file) e [taglio](#mandare-in-taglio).
#### Cutstudio    
Supporta file di formato BMP, JPG, STX, AI ed EPS. Accetta inoltre immagini acquisite da scanner TWAIN 32. 

#### Plug in per Inkscape   
Un'[estensione di Inkscape](https://wiki.inkscape.org/wiki/index.php/Inkscape_Extensions) permette di inviare il file di taglio a Cutsudio, ampliando le tipologie di file supportati da Cutstudio. Supporta file di formato SVG, STX AI, DXF, CDR, PDF, BMP, JPG, PNG e TIFF.

### Accessori (forbici taglierini ecc.)
#### Accessori compresi con la Vinylcut
Adattatore di corrente, cavo di alimentazione, lama, porta lama, taglierino di separazione, base del rullo, pinzette, materiale di prova, nastro applicativo, cavo USB, CD-ROM, manuale d’uso 

#### Accessori aggiuntivi
Chiavetta USB, forbici, altri tipi di lame, [_Transfer_ o pellicola di trasferimento](https://www.necchishop.com/prodotto/pellicola-per-il-trasferimento/) 

## Il processo di taglio
Per tagliare i fogli in vinile segui i passaggi illustrati in seguito.

### Accensione
Accendere computer e schermo e assicurarsi che il cavo USB sia collegato alla vinycut.
![foto-modificarla evidenziando tasti di accensione](vinylcut/../img/500x300.png)  

Accendere il macchinario tramite il tasto `POWER` .   
![foto-modificarla evidenziando tasti di accensione](vinylcut/../img/500x300.png)

### Caricare il materiale 
Abbassare la leva di caricamento (__loading lever__) sul retro a sinistra.
<!--  Foto della leva e freccia con la direzione per abbassarla -->
![foto prima e dopo](vinylcut/../img/500x300.png)   

Inserire posteriormente  il materiale facendolo scorrere attraverso la fessura della macchina e, se necessario, appoggiarlo al __portarotolo__.    
![foto allineamento](vinylcut/../img/500x300.png)

Spostare i due rulli di fissaggio (__pinch roller__) negli spazi bianchi segnati, facendoli scorrere dalla parte posteriore della macchina. 
![foto-aggiungere frecce spostamento](vinylcut/../img/500x300.png)   

Posizionare il materiale in modo che sia parallelo alle linee guida (__guide lines__) in rilievo alla base del macchinario e alzare la leva di caricamento (__loading lever__).   
![foto prima e dopo](vinylcut/../img/500x300.png)   

Sul display del pannello di controllo (__operation panel__) compare la scritta `"CARICO FOGLIO"`. Scegliere con i tasti `←` o `→` il tipo di supporto utilizzato, tra `"ROTOLO"`, `"FOGLIO"` o `"BORDO"`. Premere `ENTER` per confermare.  
![foto-evidenziare tasti necessari+foto completamento azione](vinylcut/../img/500x300.png)

### Preparare il file
Tramite USB mettere i file sul computer collegato al macchinario. Il file deve essere in uno dei formati citati in nella [sezione file](#file).   
![foto](vinylcut/../img/500x300.png)

Se il formato file è tra quelli letti da [Inkscape](#plug-in-per-inkscape), aprire quindi il programma e aprire il file contenente il contorno di taglio, seguendo il percorso _file_>_importa_>selezionare il file.  
![screen 02+screen 03](vinylcut/../img/500x300.png)   

È buona pratica fare un controllo delle linee cambiando la visualizzazione con il percorso _visualizza_>_modalità visualizzazione_>_scheletro_.  
![screen 04+screen 05](vinylcut/../img/500x300.png)   

Grazie all'[estensione](#plug-in-per-inkscape) è quindi possibile aprire il file direttamente su Cutstudio, seguendo il percorso _estensioni_>_Roland_>_open in Cutstudio_.   
![screen 06](vinylcut/../img/500x300.png)


Se il formato file è tra quelli letti da [Cutstudio](#cutstudio) si può decidere di aprire il file direttamente su questo programma seguendo il percorso (vedere percorso).   
![manca screen e screen 07](vinylcut/../img/500x300.png)       

La Vinylcut durante il [caricamento del materiale](#caricare-il-materiale) misura in automatico la dimensione della superficie utile di taglio. Per riportare queste misure sul foglio di lavoro seguire il percorso _tagliare_>_modifica_>_proprietà_>_get from machine_. Confermare quindi l'operazione cliccando su _ok_ nelle prime due finestre, ma facendo attenzione a selezionare _annulla_ nell'ultima (come mostrato in foto).   
![screen 08-modificare inserendo flusso comandi completo](vinylcut/../img/500x300.png)   
  
Utilizzare il comando _spostare_ (in alto a destra) per posizionare i contorni in corrispondenza dell'origine di taglio.   
Per ridurre o aumentare le dimensioni del contorno si può agire sulle frecce agli angoli del file o modificare i valori nella colonna destra (spuntare la casella _Conserva Aspetto_ per mantenere le proporzioni).   
![screen 09-evidenziare comando spostare in alto e modifica dimensioni di lato](vinylcut/../img/500x300.png)

### Impostare i parametri di taglio
In base al materiale è possibile modificare la pressione della lama pannello di controllo (__operation panel__) premendo sul tasto `FORCE`. Quindi modificare i grammi forza con `↑` e `↓` e premere infine `ENTER` per confermare la selezione.
![foto-evidenziare tasti necessari](vinylcut/../img/500x300.png)   

Il __display__ dovrebbe ora indicare la pressione della lama (espressa in gf), ma anche la velocità di taglio e la distanza di Offset. Quest'ultima dipende dalla lama montata ed è importante assicurarsi sempre che l'Offset indicato coincida con quello della lama in utilizzo.     
![foto display + in futuro foto dello sticker che indica le caratteristiche della lama](vinylcut/../img/500x300.png)   

Prima di procedere al taglio è buona pratica fare dei test.Tramite i tasti `←` e `→` si posiziona il carrello di taglio (__cutting carriage__) in uno spazio inutilizzato, quindi premere il tasto `TEST` per almeno un secondo.   
Il taglio è ben fatto se si riesce a spellicolare il cerchio senza rimuovere il quadrato al suo interno e se la superficie dello strato protettivo è segnata (vedere foto di seguito).  
![foto tastierino-evidenziare tasti necessari+foto step del test](vinylcut/../img/500x300.png)

### Mandare in taglio
Prima di avviare il taglio su un rotolo è bene impostare il punto di origine. Nel caso del rotolo il punto di origine dipende dalla posizione di caricamento ed è quindi utile cambiare il punto di origine del taglio: spostare ilcarrello di taglio (__cutting carriage__) nel punto di origine desiderato con i tasti `←`, `→`, `↑` e `↓`. Nella posizione desiderata premere `ORIGIN` sul pannello di controllo (__operation panel__).
![foto tasto origine](vinylcut/../img/500x300.png)

Si può dunque avviare il taglio da Cutstudio, seguendo il percorso _tagliare_>_ok_.     
![screen 10-evidenziare tasti](vinylcut/../img/500x300.png)

Per variare la pressione della lama durante il taglio, è possibile regolarla dallo slider `PEN FORCE`.   
![foto tastierino evidenziando pen force+risultato finale taglio](vinylcut/../img/500x300.png) 

A taglio eseguito si può portare in avanti il materiale con il tasto `↓` del pannello di controllo (__operation panel__) e nel caso si stia utilizzando un rotolo, tagliare il rettangolo lavorato.
![foto tastierino evidenziando pen force+risultato finale taglio](vinylcut/../img/500x300.png)   

A fine lavorazione o per cambiare il materiale bisogna estrarre il rotolo o il foglio. Questo passaggio è simile alla [fase di caricamento](#caricare-il-materiale) e consiste nell'alzare la leva di caricamento (__loading lever__) ed estrarre il materiale.   
![caricare il materiale ma al contrario](vinylcut/../img/500x300.png)

### Spegnimento 
A fine utilizzo, spegnere la Vinylcut tenendo premuto il tasto `POWER`.   
![foto-modificarla evidenziando tasti di accensione](vinylcut/../img/500x300.png)   

Espellere la USB dal computer e procedere con lo spegnimento del computer. Per ultimo spegnere lo schermo del computer.  
![screen 11-12](vinylcut/../img/500x300.png)      

## Il post-processing
Per iniziare il post-processing si deve rimuovere l'adesivo in eccesso sia nella parte esterna, sia in quella interna al contorno di taglio.   
![2 foto+risultato](vinylcut/../img/500x300.png)  

Per poter trasferire l'adesivo dalla carta protettiva alla superficie di applicazione, bisogna usare il [__Transfer__ o pellicola di trasferimento](https://www.necchishop.com/prodotto/pellicola-per-il-trasferimento/). Tagliare dunque un pezzo di __Transfer__ abbastanza grande da coprire tutto lo sticker.   
![foto](vinylcut/../img/500x300.png)   

Applicare quindi il __Transfer__ assicurandosi di avere un'adesione completa e omogenea allo sticker. Per un'ulteriore prova si può sollevare leggermente il __Transfer__ e controllare che lo sticker vi rimanga attaccato, come mostrato in foto.  
![foto](vinylcut/../img/500x300.png)   

Finalmente si può applicare lo sticker sulla superficie desiderata!   
Separare il transfer e l'adesivo dalla carta protettiva, posizionarlo sulla superficie scelta e incollarlo in modo omogeneo.   
![foto](vinylcut/../img/500x300.png)

## FAQ