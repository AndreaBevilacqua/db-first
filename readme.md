Esercizio di oggi: DB First
nome repo: db-first
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
Per la consegna, potete inserire la vostra tabella in un file markdown come vi ho fatto vedere a lezione, oppure farla su Excel, Fogli Google ecc e fare uno screen.
Non sono sicuro del fatto che possiate caricare direttamente un Excel, chiedo conferma a 
@Michele Spiller
 e 
@Marius Minia
Buon lavoro e a domani!


Colonne | Tipo | Attributi |
------- | ----- | -------- |
Id | BIGINT | PRIMARY_KEY, AUTOINCREMENT |
Marca | CHAR(13) | NOTNULL, UNIQUE |
Chilometraggio | INT | NOTNULL, DEFAULT(0)
Prezzo | FLOAT | NOTNULL, DEFAULT(0) |
Stato_vendita | BOOL/TINYINT(1) | NOTNULL, DEFAULT(0) |
Anno | DATA | NOTNULL

