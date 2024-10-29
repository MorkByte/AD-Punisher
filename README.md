# ADUserLister - Active Directory User Enumeration via LDAP

ADUserLister è uno script PowerShell progettato per enumerare gli utenti di Active Directory utilizzando una connessione LDAP, evitando l'autenticazione Kerberos. Questo script è utile per ambienti in cui l'accesso Kerberos non è disponibile o non è configurato e dove è possibile accedere tramite LDAP.

## Caratteristiche

- Connessione diretta a Active Directory tramite LDAP
- Enumerazione degli utenti in Active Directory senza necessità di autenticazione Kerberos
- Filtraggio per ottenere solo gli utenti (esclusi altri oggetti come computer o gruppi)

## Prerequisiti

- PowerShell (versione 3.0 o successiva)
- Accesso alla directory LDAP del dominio specificato
- Permessi di lettura su Active Directory (senza autenticazione Kerberos)

## Installazione

1. Clona questo repository sul tuo ambiente locale:
   ```bash
   git clone https://github.com/tuo-username/ADUserLister.git
