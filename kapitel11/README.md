#Boolesche Funktionen

Boolesche Funktionen erlauben das Schreiben eigener "Testbefehle", z.B. linksFrei() oder rechtsFrei().

Ändern boolesche Funktionen den Programmkontext, spricht man von einem Nebeneffekt(  side effect, Seiteneffekt ).

##Boolesche Return-Anweisung
	
	return <boolescher Ausdruck>;

	z.B.:

	return true;
	return false;

	return vornFrei();
	return vornFrei() && kornDa();

##Funktionsdefinition

	boolean fktName() {

		return <boolescher Ausdruck>;
	}

##Funktionsaufruf

	...
	if( fktName() ) {

		...
	}

	while( fktName() ) {

	}
