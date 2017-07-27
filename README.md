# magento2-traduzione-italiana
Magento 2 - Traduzione Italiana ufficiale


# Magento2 Italian Language Pack (it_IT)
This is a Italian Localization Pack generated from [crowdin official Magento2 translations project](https://crowdin.com/project/magento-2).


# Installation
## Via composer
To install this translation with composer you need to have [Composer](https://getcomposer.org) installed.

Update the composer.json file:
```
“require”: {
	...
	“antoniocarboni/magento2-traduzione-italiana”:"dev-master”
},

 "repositories": [
    { "type": "vcs", "url":  "https://github.com/antoniocarboni/magento2-traduzione-italiana" }
    ],
    
```
and via SSH:

```
cd <magento2 path>
composer update
bin/magento setup:static-content:deploy it_IT
bin/magento cache:clean
```

## Manually
* Download the translations from crowdin:
https://crowdin.com/project/magento-2
* and paste it in Magento root
* Download the files package from this repository and copy in app/i18n/antoniocarboni/it_It/.



# Contribute
You can help to improve the translation suggesting or vote the translations :
[https://crowdin.com/project/magento-2/it]#



=======================================================================================

# magento2-traduzione-italiana
Magento 2 - Traduzione Italiana ufficiale


# Magento2 Italian Language Pack (it_IT)
Questa è la traduzione italiana ufficiale generata dal [progetto di traduzione ufficiale di Magento 2 su crowdin](https://crowdin.com/project/magento-2).


# Installazione
## tramite composer
Per installare Magento2 tramite composer è necessario avere lo stesso [Composer](https://getcomposer.org) installato e funzionante.
Aggiorna il tuo file composer.json:
```
“require”: {
	...
	“antoniocarboni/magento2-traduzione-italiana”:"dev-master”
},

 "repositories": [
    { "type": "vcs", "url":  "https://github.com/antoniocarboni/magento2-traduzione-italiana" }
    ],
    
```
e tramite riga di comando:

```
cd <magento2 path>
composer update
bin/magento setup:static-content:deploy it_IT
bin/magento cache:clean
```


## Manualmente
* Scarica la traduzione da caricandola da crowdin indirizzo:
https://crowdin.com/project/magento-2
* Scarica l’intera traduzione e copiala nella root di Magento.
* Scarica il pacchetto di registrazione della traduzione da questo repository e posizionalo in app/i18n/antoniocarboni/it_It/.



# Come Contribuire
Per aiutarci a migliorare la traduzione o votare le stringhe già tradotte:
[https://crowdin.com/project/magento-2/it]#

## Note di compilazione
1. Il language package non deve contenere traduzioni dipendenti dal contesto; per le frasi che si prevede possano essere diverse a seconda del tema o progetto utilizzeremo il dizionario del tema.
Un esempio: "VAT number" non è stato tradotto in "P. IVA" perché alcuni progetti potrebbero richiederne la traduzione in "Partita Iva" oppure "Codice Fiscale o P. Iva".


