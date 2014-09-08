#Boolesche Variablen

Mit den booleschen Variablen erhalten unsere Hamster ein "Gehirn" und können sich den Wert boolescher Ausdrücke merken, d.h. also die Werte `true` und `false`.

##Definition boolescher Variablen

	boolean <Bezeichner> [=<boolescher Asudruck>];

	z.B.:

	boolean x = true;
	boolean y = false;
	boolean z = x && !y;	

	boolean rFrei = rechtsFrei();
	boolean lFrei = linksFrei();
	boolean freiheit = rFrei && lFrei;
