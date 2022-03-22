# Workflow Templates

## Variabili
Le variabili di un workflow vanno nel nodo **env** del workflow.
###### Descrizioni
Per descrivere una variabile aggiungere un commento dopo averla dichiarata.
Queste sono le keyword supportate dagli strumenti di generazione workflow Regesta:
- OPTIONAL: Dato un valore di default, se l'utente non cambia valore il workflow deve funzionare ugualmente
- HIDDEN: Campo che non viene mostrato dai generatori
- PASSWORD: Campo che rappresenta una password
Esempio:
```
env:
  VAR_ESEMPIO1: false #OPTIONAL Descrizione varibile 1
  VAR_ESEMPIO2: abc1234 #PASSWORD OPTIONAL Descrizione variabile 2
  WKF_TEMPLATE: esempio #HIDDEN
```
