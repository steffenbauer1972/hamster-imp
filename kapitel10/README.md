#Wiederholungsanweisung

##Kopfgesteuert

	while( <boolescher Ausdruck> )
		Anweisung;

	z.B.:

	while( vornFrei() )
		vor();


#Fußgesteuert

	do
		Anweisung;
	while( <boolescher Ausdruck> );

	z.B.:

	do 
		linksUm();
	while( !vornFrei() );
