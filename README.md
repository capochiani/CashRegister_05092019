# CashRegister_05092019 💸💰
<br>
Esercizio REGISTRATORE DI CASSA
<br>
Data: 05.09.2019
<br><br>
Specifiche del progetto:

<i>Implementare un programma per un registratore di cassa.
Deve quindi essere possibile effettuare le classiche registrazioni di spese
con i relativi prodotti. </i>

- Stampa lo scontrino (attraverso la scrittura di un file su disco).
- Applicazione degli sconti
- Calcolo del totale con l'IVA.

<b>Elenco requisiti:</b><br>

- Effettuare la registrazione degli importi per i singoli prodotti.
- Effettuare la stampa dello scontrino come file di testo su disco.
- Poter applicare sconti al totale.
- Tenere in considerazione l'IVA sulla spesa.
- Tutte le operazioni devono essere agganciate a un DB. 
- Tutti i prodotti sono tassati con la stessa aliquota IVA. <br>
- _DELETE: Il prezzo di ogni prodotto può essere modificato durante la registrazione. <br/>

Opzionale: Disegnare l'interfaccia per essere fluibile da schermi touch.
<br><br>
<b>Elenco specifiche: </b><br/>
1. Deve essere sempre ben visibile l'ammontare attuale dello scontrino. <br/>
2. E' possibile selezionare un prodotto dal menù a tendina.
3. Una volta selezionato un prodotto, non deve essere possibile modificarne il prezzo ma può essere solo aggiunto tramite l'apposito pulsante.
4. L'applicazione dello sconto deve avvenire selezionando l'opportuna voce nel menu a tendina del prodotto.
5. Nella fase di selezione del prodotto anonimo, la pulsantiera numerica ritorna abilitata per l'inserimento del pezzo.
6. Verrà adottato un DB basato su MariaDB, per la memorizzazione degli scontrini e dei prodotti.
7. Il valore dei aliquota IVA sarà memorizzato come costante all'interno dell'applicazione.
