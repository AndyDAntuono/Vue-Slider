Esercizio di oggi: *Vue Slider*
nome repo: vue-slider
*Descrizione:*
Partendo dal markup della versione svolta in js plain, rifare lo slider ma questa volta usando Vue.
*Bonus:*
1- al click su una thumb, visualizzare in grande l'immagine corrispondente
2- applicare l'autoplay allo slider: ogni 3 secondi, cambia immagine automaticamente
3- quando il mouse va in hover sullo slider, bloccare l'autoplay e farlo riprendere quando esce
*Consigli del giorno:*
- regola d'oro: riciclare ovunque possibile! Questo significa che per la parte di markup possiamo recuperare html e css dell'esercizio svolto qualche giorno fa: è già tutto pronto!
- il riciclo spesso va a braccetto con le funzioni! Sapendole sfruttare bene, l'esercizio si riduce a poche righe

/*SOLUZIONE*/
- attivo il vue
- prendo l'array di oggetti fornitomi e lo inserisco all'interno di data del vue
- vado sul file html e nel tag div .title sostituisco il src del tag img e lo collego con la chiave image
- faccio la stessa cosa con alt
- collego il tag h3 alla chiave title di slides
- collego il tag p con alla chiave text di slides