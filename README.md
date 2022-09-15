# EpicEnergyServices


Progetto simulativo crm. Associato ad ogni cliente abbiamo diverse fatture. Gli indirizzi dei clienti sono associati alle province ed ai comuni che vengono scaricati da due file csv presenti nella cartella.
Esercizio realizzato grazie al framework Springboot ed utilizza le seguenti tecnologie: Spring web, Jpa, Thymeleaf, OPenCSV, POstgreSQL e Lombok.

ADMIN:

    { "userName" : "admin", "password" : "admin" }

USER:

    { "userName" : "user", "password" : "user" }

Token in Postman ---> "Authorization" ----> Request ---> "Type" : Bearer Token)

Inserimento Cliente :

    { "ragioneSociale": "Miaio", "partitaIva": "TR3252351", "email": "miao@mail.it", "dataInserimento": "2019-01-12", "dataUltimoContatto": "2022-02-14", "fatturatoAnnuale": 735383, "pec": "miaoi@mail.it", "telefono": "3394521723", "emailContatto": "bau@mail.it", "nomeContatto": "Miao", "cognomeContatto": "Bau", "telefonoContatto": "3347809123", "sedeLegale": { "via": "via Erbe", "civico": 1, "localita": "Roma", "cap": 39100, "comune": { "id": 3457 } }, "sedeOperativa":  { "via": "via Milano", "civico": 22, "localita": "Roma", "cap": 3457 }, "tipoCliente": "SRL" }

Inserimento fattura :


{ "anno": 2021, "data": "2021-01-03", "importo": 3434, "numeroFattura": 39, "stato": "PAGATA", "cliente": { "id": "1" } }


La gestione dell'interfaccia é da considerarsi incompleta!
