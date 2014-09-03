#Bedingte Anweisung

##Testbefehle

* `vornFrei()`
* `kornDa()`
* `maulLeer()`

##Bedingte Anweisung

	if( <boolescher Ausdruck> )
		Anweisung;

	z.B.:

	if( vornFrei() )
		vor();

	if( kornDa() )
		nimm();

	if( !maulLeer() )
		gib();

##Bedingte Anweisung mit Alternative

	if( <boolescher Ausdruck> )
		Anweisung;
	else
		alternativeAnweisung;

	z.B.:

	if( vornFrei() )
		vor();
	else
		linksUm();
