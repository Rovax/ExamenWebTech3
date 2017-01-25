Eclipse crasht bij opstarten, bij eender welke java vm, zowel 32 bit als 64 bit.
Gisterenavond werkte deze nog perfect.
Ik heb enkele screenshots geupload die de error window demonstreren.



Theorie:
REST vs. SOAP:
Het fundamentele verschil tussen de twee is dat SOAP een protocol is, terwijl REST een architectuur stijl is.
SOAP is nauwgebonden aan de server, en bij enige wijziging bij client of server wordt de verbinding verbroken.
REST is minder nauwgebonden en kan met aanpassingen omgaan.


Type Safety in REST:
Een eerste, zeer simplistische methode om type safety te creeren is door gebruik te maken van getClass() en te verzekeren dat we het juiste type hebben.
Als we niet het juiste type hebben, wordt er een error weergegeven.

Een andere methode is om nooit de data te gebruiken in dezelfde functie als waarin ze wordt opgevraagd. 
Bij het doorgeven aan een andere functie die een parameter van een specifiek type verwacht,
wordt er dan een error gegeven als dit niet correct is.