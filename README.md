# Progetto ApprofodimentiSpring
In questo progetto si sono approfonditi i seguenti temi di Spring:<br>
1. Spel Spring (validazione tramite Spel)<br>
	<La classe che fa la validazione si chiama SpelValidator, ed è richiamata dalla classe di test SpelValidationTest	  
2.  ValidatingItemProcessor<br>
	Il test del processor Spring è stato fatto utilizzando la classe di test ValidatingItemProcessorTest
	
# Progetto CreazioneXmlExample
In questo progetto sono stati generati degli XML di esempio con le seguenti librerie:
	- Castror (SerializzaXmlCastror)
	- Groovy + Spring (SerializzaXmlGroovy)
	- XStream (SerializzaXmlXStream + SerializzaXmlXStreamConverter)

# Progetto EhCacheExample
In questo progetto è approfondito il tema del caching di metodi con EhCache e Spring
La classe App.java richiama più volte uno stesso metodo e mostra quante volte viene chiamato il metodo vero e proprio
e quante viene preso quanto recuperato dalla cache

# Progetto GreenMailExample
In questo progetto si è approfondito il tema testing di classi che si occupano di inviare mail con GreenMail
La classe di cui si vuole eseguire il test è BaseMailSenderImpl. Il test è eseguito dalla classe GreenMailTest

# Progetto MongoDbExample
In questo progetto si è approfondito MongoDb con Spring.
Si è simulata la creazione di un "Document" (assomiglia ad un dto) con id avt005tb.
Abbiamo creato un "Service" per accedere alla collezione di dati (Avt005TbService).
Il tutto è stato testato attraverso la classe MongoDBTest, la quale recupera i dati da un DB in ram e li inserisce nel NoSQL DB,
per poi ricercarli.
ATTENZIONE!!!!!!!! SERVE LA PARTE SERVER PER UTILIZZARE QUESTO ESEMPIO

# Progetto PdfBoxExample
In questo progetto si è approfondita la libreria PdfBox, in particolare si sono provate le seguenti funzionalità:
	- Trasformazione di un PDF in un file di testo per poter fare le opportune verifiche di contenuto

# Progetto QuartzExample
In questo progetto si è approfondita la libreria Quartz integrata con Spring.
Sono stati fatti i seguenti esempi:
	- Trigger che gira ogni 5 secondi attraverso un SimpleTriggerBean
	- Trigger che gira ogni 5 secondi attraverso un CronTriggerBean
	- Trigger che gira da Lunedì a Venerdì alle 8:00 attraverso un CronTriggerBean
	
# Progetto VelocityExample
In questo progetto si è approfondita la libreria Velocity. L'esempio (VelocityTemplate.java) crea una mail utilizzando un template.
	
