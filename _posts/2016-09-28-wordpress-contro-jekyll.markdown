---
layout: post
title:  "Jekyll vs. Wordpress la formica che batte il colosso"
date:   2016-09-28 3:20:25
categories: feature wordpress jekyll
tags: featured wordpress blog jekyll blog
image: /assets/article_images/2016-09-28-wordpress-contro-jekyll/wordpress-vs-jekyll-boxe.jpg
image2: /assets/article_images/2016-09-28-wordpress-contro-jekyll/wordpress-vs-jekyll-boxe-mobile2.jpg
---
Ho usato Wordpress per gli ultimi 4 anni o più e, lungo il tragitto, è stato un buon compagno. Purtroppo è ancora molto lontano dall'essere perfetto.

***Lo ha dimostrato un'esperienza effettuata con un blog ad alto traffico che trattava videogiochi, che mi ha dimostrato:***

> *- Un blog in wordpress a pieno carico va molto lento*
> *- La cache non funziona come dovrebbe*
> *- Sono stato infettato da malware*

Non che non mi sia preparato per questo genere di problemi, ho installato W3 Total Cache, aggiornato l'hosting con un piano adeguato al mio traffico, installati plugin per tutelare la sicurezza del mio sito e seguito alla lettera le "best practice".

#### Tutti questi accorgimenti presi hanno giovato al mio blog in Wordpress?

Certo, ma non abbastanza, *i risultati non mi hanno mai soddisfatto appieno guardando i rapporti qualità prezzo*, così quando ho chiuso quel blog ho deciso di rinunciare al vantaggio principale di wordpress, essere in grado di pubblicare contenuti in modo rapido, decidendo di guardare altrove.

#### Dopo attente ricerche su web ho scoperto un prodotto interessantissimo: [Jekyll](https://jekyllrb.com/).

## Jekyll è esattamente quello che mi serviva!

Un generatore di **blog statico**. Ciò significa che, invece di installare software lato server costruito con un linguaggio come PHP, è possibile utilizzare la riga di comando sul computer locale che esegue il sito web per generare file statici (HTML, CSS, ecc).

Quindi caricare i file generati da qualsiasi server web e, beh, questo è il tuo blog.

>Anche se [**Jekyll**](https://jekyllrb.com/) potrebbe sembrare semplicemente una geniale alternativa a WordPress, questo approccio statico ha una serie di vantaggi reali su WordPress.

# Per progetti web con strutture semplici Jekyll è meglio di Wordpress

## #1 WordPress è eccessivo.

Ad oggi Wordpress è il CMS di gestione contenuti più vasto che ci sia. Puoi fare quasi tutto con esso, da un e-commerce a un piccolo social network. È un ottimo prodotto ma si è evoluto molto più di quel che erano le sue radici e funzioni, e ne possiede troppe molte più di quel che hi bisogno per un semplice blog.

>Jekyll, in confronto, è una piattaforma di blogging pura. Per alcuni, questo obiettivo sarà limitante, ma se si desidera creare un sito solo per eseguire un blog, e delle landing page promozionali, Jekyll offre tutto il necessario.

Un esperienza di scrittura è senza pari, poiché il contenuto è costruito con i file Markdown, ed è possibile utilizzare qualsiasi editor di testo per creare i tuoi contenuti, lavorare e testare le modifiche in locale per poi effettuare l'upload delle stesse quando regolate a puntino.

*Personalmente, io uso* ***Atom*** *sia per scrivere codice che i miei post, ma qualsiasi altra opzione va bene.*

Lo strumento "migliore" dipende sempre dal contesto, dal tipo di progetto da sviluppare, ma, sempre più, penso che una piattaforma semplice come ***Jekyll sia degna di essere considerata tra le prime opzioni per un blog personale o una struttura di mini siti pubblicitari.***

## #2 WordPress fa fatica sotto pressione.

Pochi mesi dopo il lancio di un mio blog, un aumento del traffico ha visto centinaia di persone riversarsi contemporaneamente tra le pagine del mio blog.

Pensavo a questo... Il mio duro lavoro sta dando i suoi frutti! Poi il blog, proprio grazie all'eccessivo traffico, ha crashato e rimasto tale per le successive ore, nelle quali i lettori provavano ad accedere e ricevevano un errore dal mio hosting. Una brutta figura che mi ha fatto apparire come dilettante e fatto sprecare un mucchio di tempo e risorse senza raggiungere i risultati desiderati.

>Naturalmente, **WordPress non è l'unica applicazione lato server che potrebbe avere problemi quando si riceve una grande quantità di traffico,** ma ci sono in giro un bel po' di storie di blog WordPress che vanno in crash proprio nel momento sbagliato - anche con tutte le corrette ottimizzazioni - e non c'è niente di più sciocco di doversi preoccupare di tecnicismi per il  blog quando esso diventa popolare.

*Passando a Jekyll, però, questo rischio è inesistente:*

Il caricamento di file statici pone una minima quantità di carico su un server. La quantità di carico è quasi imperccettibile. Questo rende molto difficile che il blog vada in crash  (il vostro servizio hosting deve essere proprio di pessima qualità in caso accada).

Inoltre puoi ospitare il tuo sito web su Amazon S3 o un altro **servizio di cloud hosting** rendendo quasi impossibile per il tuo blog un crash, *dato che le risorse su cloud hosting sono automaticamente scalate in base al carico di lavoro.*

>Forse il tuo blog non è ancora abbastanza popolare perché vada in crash, oppure entra sistematicamente in crash a picchi di traffico alti e tu non te ne sei mai accorto, ma è sicuramente una cosa poco saggia mettere a repentaglio mesi o anni di lavoro per poi non essere visibile proprio nel momento in cui si ottiene l'attenzione desiderata che è anche l'obiettivo di avere un sito web o blog.

## #3 WordPress è lento.

Le stesse ragioni per le quali **WordPress da problemi sotto carico**, sono da imputare anche al fatto che è lento: ed è anche normale, perché basa la sua struttura su chiamate di codice e database dinamici.
Si può riuscire a rendere più veloce wordpress, grazie a delle ottimizzazioni a livello di codice, ma è come cercare di far andare veloce una tartaruga, non è nella sua natura.

**Ottimizzare un blog Jekyll, d'altra parte, è facile e puoi:**

> 1. *Ospitare la struttura Jekyll su un server nginx*
> 2. *Puoi minimizzare il codice HTML e CSS senza appositi plugin il tutto è integrato di default*
> 3. *Hai un maggior controllo in fase di progettazione e design oltre ad essere più semplice apportare modifiche  (wordpress ha un buon supporto per quanto riguarda i temi grafici, ma con Jekyll è molto meno laborioso implementare nuovi design)*

Ma anche senza alcuna ottimizzazione, già il fatto che i blog Jekyll sono fatti di file statici, è sufficiente per farli caricare più velocemente della maggior parte dei blog WordPress.

Pensa che questo blog, *ospitato gratuitamente* da **github carica a velocità folli** per il tipo di hosting e struttura (ha una velocità di caricamento inferiore ad 1 secondo)

## #4 WordPress è un obiettivo sempre più succulento per gli hacker.

>Più è popolare un software diventa, più diventa un probabile bersaglio per hacker e maleintenzionati. Questo significa che installare il WordPress è una bomba a orologeria e che qualcuno inevitabilmente si divertirà con essa? No?

Nei miei anni di attività posso ricordare solo una falla importante nella storia della sicurezza di wordpress. Ed i problemi seri si presentano solo se non si aggiorna regolarmente il CMS appena uscito gli aggiornamenti. Inoltre con i molti plugin di sicurezza possiamo dire di stare tranquilli.

Detto questo tra lo stare tranquilli ed avere l'assoluta sicurezza io scelgo la seconda perché avere un sito web, magari già popolare, infettato è un'esperienza abbastanza dolorosa per la tua immagine e costosa per il portafoglio se non sei un tecnico oltre al rischio di perdere tutti i tuoi dati se non ti sei prevenuto con un backup.

Il vantaggio di **Jekyll** è che, sul server, sono presenti solo file statici. Non c'è nulla di dinamico che può essere sfruttato per un exploit.

#### Ci sono altri modi in cui un hacker potrebbe entrare nel tuo sito?

Sicuro. Ma solo attraverso le onnipresenti minacce di social engineering, come quando qualcuno tenta di ottenere il nome utente e la password per un server. Ma, molto importante, non c'è il rischio che un hacker penetri attraverso un exploit in un plugin scritto male o tramite un problema all'interno di Jekyll.

Se in caso si verifica un attacco, o se c'è stata una perdita di dati per qualche altra ragione, allora il processo di recupero backup, non potrebbe essere più semplice:

Rigenera il blog sulla tua macchina e fai di nuovo l'upload da locale sul server.

>**Se avete bisogno di un nuovo server**, allora così sia. Non c'è niente di "pesante" e complicato da spostare come un database, o qualcosa di speciale per installare. Basta pagare per un nuovo server, caricare i file su di esso, modificare il file di config con 2 stringhe dove specifichi gli indirizzi, e il gioco è fatto. Sei tornato in azione!

## #5 Ospitare WordPress è costoso.

Solitamente la soluzione per i problemi di velocità su Wordpress che ho visto finora è quella di pagare di più per il web hosting. Ci sono servizi di hosting che sono appunto dedicate alla soluzione di questi problemi e può portare un livello soddisfacente la qualità e velocità del tuo sito web.

Ma questi servizi hanno un costo. Alcuni sosterranno che "si devono spendere soldi per fare soldi", ma non ha sempre senso questo ragionamento. La non sostenibilità del mio blog sui videogiochi, ad esempio, erano i margini di spesa bassi. Se avessi speso di più in hosting, sarebbe stato molto significativo per il fatturato.

>Provando ad ottimizzare al meglio il blog wordpress sono arrivato a poter spendere circa 20€ al mese, ma il blog sarebbe andato ancora in crash all'arrivo di burst di traffico imprevedibili.

**Se metto a confronto il vecchio blog con questo mio nuovo, be diciamo, potrei ricevere 10.000 visite nella prossima ora e non farebbe una piega, nonostante utilizzi un hosting da 5 $ mese tramite digital ocean.**

Per tagliare ulteriormente i costi, potresti ospitare il tuo blog su **Amazon S3**. Non solo si scala senza limiti, non importa quanto traffico ricevi, mediamente la maggior parte delle persone spende un paio di dollari per l'hosting con questa soluzione. (Il vantaggio di Digital Ocean Digital è la velocità, per questo costa un po di più.)

## Conclusione

>Wordpress rimane una soluzione valida per un certo tipo di utenza e se hai finito di leggere questo articolo rispondendo a tutti i punti sfavorevoli sopra elencati non valgano il passaggio a Jekyll probabilmente dal tuo punto di vista hai ragione, dovresti continuare ad utilizzare wordpress.

**Non voglio spingere Jekyll per il gusto di farlo.** Tuttavia, credo che un sacco di blogger (e un sacco di lettori di blog) ne gioverebbero molto sia in termini di SEO che in termini di usabilità, velocità, gradevolezza di navigazione, sostenibilità e costi del proprio sito passando da un prodotto dinamico ad uno statico.

### E' tutta questione di prospettiva, tipo di progetto, budget e conoscenze tecniche.

>Se ti è piaciuto l’articolo ti sarei grato se lo condividessi qui sotto, è un piccolo sforzo per te ed un grande aiuto per entrambi perchè mi permetterai di avere un feedback per eventuali nuovi articoli :)
