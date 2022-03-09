<template>
  <v-row justify="center" align="center">
    <v-col cols="12" sm="12" md="12">
      <v-card id="dashboard"
      flat>

    <v-app-bar
      color="white"
      flat
    >
      <v-app-bar-nav-icon @click.stop="drawer = !drawer"></v-app-bar-nav-icon>
 <v-card-text>FOGLIO ILLUSTRATIVO: INFORMAZONI PER IL PAZIENTE
        </v-card-text>
    </v-app-bar>

    <v-navigation-drawer
      v-model="drawer"
      absolute
      bottom
      temporary
    >
      <v-list
        nav
        dense
      >
        <v-list-item-group
          v-model="group"
          active-class="deep-purple--text text--accent-4"
        >
        <scrollactive>
          <v-list-item>
            <v-list-item-title> <a href="#uno" class="scrollactive-item">1 COS’E’ LEVOBREN E A COSA SERVE</a></v-list-item-title>
          </v-list-item>

          <v-list-item>
            <v-list-item-title> <a href="#due" class="scrollactive-item">2 COSA DEVE SAPERE PRIMA DI USARE LEVOBREN</a></v-list-item-title>
          </v-list-item>
          </scrollactive>
        </v-list-item-group>
      </v-list>
    </v-navigation-drawer>
   
       
        <v-card-title class="headline">
         <h1><br>
         LEVOBREN</h1><br>
        </v-card-title>
         <v-card-title class="headline">
         <h4>25mg COMPRESSE<br>
25mg/ml GOCCE ORALI SOLUZIONE<br>
25mg/2ml SOLUZIONE INIETTANTE</h4>
        </v-card-title>
        <v-card-text>
      
<h1>LEVOSULPIRIDE</h1>
<p><br><strong>Legga attentamente questo foglio prima di usare questo medicinale perché contiene importanti
informazioni per lei.</strong><br>
- conservi questo foglio. Potrebbe aver bisogno di leggerlo di nuovo.<br>
- se ha qualsiasi dubbio, si rivolga al medico o al farmacista.<br>
- questo medicinale è stato prescritto soltanto per lei. Non lo dia ad altre persone, anche se i
sintomi della malattia sono uguali ai sui, perché potrebbe essere pericoloso.<br>
- se si manifesta un qualsiasi effetto indesiderato, compresi quelli non elencati in questo foglio, si
rivolga al medico o al farmacista. Vedere paragrafo 4.<br><br>
<strong>Contenuto di questo foglio:</strong><br>
1. Cos’è Levobren e a cosa serve<br>
2. Cosa deve sapere priam di usare LEVOBREN<br>
3. Come usare LEVOBREN<br>
4. Possibili effetti indesiderati<br>
5. Come conservare LEVOBREN<br>
6. Contenuto della confezione e altre informazioni</p>
</v-card-text>
  <v-card-text id="uno">
<h2>1 COS’E’ LEVOBREN E A COSA SERVE</h2><br>
Levobren contiene la sostanza attiva levosulpiride che appartiene ad una classe di medicinali
chiamati “psicolettici, antipsicotici (neurolettici)”.<br>
Agisce stimolando la motilità dello stomaco e dell’intestino (procinetico).<br>
Levobren è indicato per il trattamento per brevi periodi di tempo:<br>
- di una malattia dovuta ad un ritardo svuotamento dello stomaco (sindrome dispetica) dovuto a
cause come tumori o forme di somatizzazione dovute all’ansia e caratterizzata dalla perdita di
appetito (anoressia), eccessiva produzione di gas nell’intestino (meteorismo), senso di tensione
nella parte alta dello stomaco, mal di testa dopo i pasti, bruciore di stomaco, eruttazioni, diarrea,
stitichezza. Levobren le viene prescritto dal medico in quanto non ha risposto in precedenza alla
terapia con altri medicinali.<br>
- dei sintomi di vomito e nausea (causati da farmaci utilizzati per il trattamento dei tumori).
Levobren le viene prescritto dal medico in quanto lei non ha risposto in precedenza alla terapia
con altri medicinali.<br>
- dei sintomi di un disturbo dell’orecchio interno che influenza equilibrio e udito ( sindrome di
Mènière), caratterizzato da vertigini, ronzii delle precchie (tinnito), perdita di udito e nausea.
</v-card-text>


<v-card-text id="due">
  <h2>2 COSA DEVE SAPERE PRIMA DI USARE LEVOBREN</h2><br>
<strong>Non prenda Levobren</strong><br>
- se è allergico a levosulpiride o ad uno qualsiasi degli altri componenti di questo medicinale
(elencati al paragrafo 6)<br>
- se ha un tumore della ghiandola surrenale (feocromocitoma)<br>
- se soffre di convulsioni (epilessia)<br>
- se è affetto da disturbi mentali (stasi maniacali, fasi maniacali delle psicosi maniaco-depressive)<br>
- se ha un tumore al seno (mastopatia maligna)<br>
- se ha un sanguinamento, ostruzioni meccaniche o perforazioni dello stomaco e dell’intestino<br>
- se è o sospetta di essere in gravidanza o se sta allattando al seno (vedere “Gravidanza e
allattamento”).
</v-card-text>
  <v-card-text>
<strong>Avvertenze e precauzioni</strong><br>
Si rivolga al medico o farmacista prima di prendere Levobren.<br>
- eviti di usare Levobren contemporaneamente ad altri psicofarmaci (neurolettici).<br>
Il medico le prescriverà Levobren con cautela solo dopo aver valutato:
- se è anziano;<br>
- se soffre di una malattia che riduce la sua capacità di ricordare, parlare e ragionare (demenza);<br>
- se lei ha fattori di rischio per l’ictus (stroke), se soffre di malattie legate alla circolazione del
sangue (cardiovascolari) o qualcuno nella sua famiglia ha o ha avuto coaguli (trombi), in quanto
Levobren può causare formazione di trombi.
</v-card-text>
  <v-card-text>
<strong>Avverta immediatamente il medico se:</strong><br>
manifesta febbre (iperpiressia), rigidità dei muscoli, difficoltà nei movimenti (acinesia), battito del
cuore irregolare (tachicardia, aritmie) e pressione del sangue irregolare, sudorazione, alterazioni
dello stato di coscienza che possono progredire fino allo stupore a al coma, perché potrebbe avere
una malattia denominata “sindrome maligna dei neurolettici”, che può essere fatale. In questo
caso <strong>deve interrompere l’assunzione di Levobren e contattare immediatamente il suo medico</strong>
che le prescriverà una terapia adeguata.<br>
Se avrà necessità di riprendere il trattamento con antipsicotici, il medico la sottoporrà a dei
controlli.<br>
Se sta assumendo medicinali anticolinergici (farmaci che bloccano l’azione dell’acetilcolina,
sostanza coinvolta nella trasmissione degli impulsi nervosi), narcotici e analgesici (antidolorifici)
poiché possono ridurre gli effetti di Levobren (vedere paragrafo “Altri medicinali e Levobren”).
</v-card-text>
  <v-card-text>
<strong>Altri medicinali e Levobren</strong><br>
Informi il medico o il farmacista se sta assumendo, ha recentemente assunto o potrebbe assumere
altro medicinale.<br>
Faccia particolarmente attenzione e informi il medico se sta assumendo i seguenti medicinali:<br>
- altri psicofarmaci, medicinali usati per disturbi psichiatrici in particolare neurolettici,<br>
- in concomitanza con medicinali che alterano il battito del cuore (prolungano il QT), il rischio di
insorgenza di anomalie al battito del cuore (aritmie cardiache) aumenta,<br>

- medicinali chiamati anticolinergici (utilizzati per contrastare una sostanza coinvolta nella
trasmissione degli impulsi nervosi, presente nel nostro organismo chiamata “acetilcolina”),
medicinali utilizzati per dormire (narcotici) e medicinali utilizzati contro il dolore (analgesici), in
quanto influenzano gli effetti di Levobren sulla motilità di stomaco e dell’intestino,<br>
- medicinali che determinano alterazioni di sostanze presenti nell’organiamo chiamate
“elettroliti”.
</v-card-text>
  <v-card-text>
<strong>Levobren con cibi, bevande e alcool</strong><br>
Durante il trattamento con Levobren non assuma alcool.
</v-card-text>
  <v-card-text>
<strong>Gravidanza e allattamento</strong><br>
Se è in corso una gravidanza, se sospetta o sta pianificando una gravidanza, o se sta allattando con
latte materni chieda consiglio al medico o al farmacista prima di usare questo medicinale.
</v-card-text>
  <v-card-text>
<strong>Gravidanza</strong><br>
<strong>Non usi</strong> Levobren se è in gravidanza o pensa di esserlo. Se assume antipsicotici (“convenzionali o
atipici”), incluso Levobren, durante gli ultimi 3 mesi di gravidanza, il suo bambino potrebbe
sperimentare i seguenti sintomi dopo la nascita, tremore, rigidità e/o debolezza muscolare,
sonnolenza, agitazione, problemi respiratori e difficoltà nell’assunzione di cibo.
Contatti il medico se il suo bambino mostra uno qualsiasi di questi sintomi.
</v-card-text>
  <v-card-text>
    <strong>Allattamento</strong><br>
<strong>Non usi</strong> Levobren durante l’allattamento.
</v-card-text>
  <v-card-text>
<strong>Guida di veicoli e utilizzo di macchinari</strong>
Con l’uso di dosaggi elevati possono verificarsi sonnolenza, torpore e movimenti involontari
(discinesie). Tenga conto di ciò se deve guidare veicoli e utilizzare macchianri che richiedono un
elevato livello di vigilanza per la loro possibile pericolosità.
</v-card-text>
  <v-card-text>
<strong>Levobren compresse contiene lattosio</strong><br>
Se il medico le ha diagnosticato un’intolleranza ad alcuni zuccheri, lo contatti prima di prendwre
questo medicinale.
</v-card-text>
  <v-card-text>
<strong>Levobren gocce orali contiene para-idrossibenzotati</strong><br>
Può causare reazioni allergiche (anche ritardate).
        </v-card-text>
    
      </v-card>

   
    </v-col>
  </v-row>
</template>

<script>
  export default {
    data: () => ({
      drawer: false,
      group: null,
    }),

    watch: {
      group () {
        this.drawer = false
      },
    },
  }
</script>
