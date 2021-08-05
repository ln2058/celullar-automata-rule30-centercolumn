Cellular Automata Rule 30 Middle Column Calculator
--- Tool for generating the center column for Rule 30 cellular automata

* Output list of 0 and 1
* Very slow for calculating large sequences

--- Use
* Change max_gen to desired number of iteration (only even number) and just run program


--- How it works
* It uses a array of 2 rows and starts with one "on" state in the middle
* It then applies the rules for the second row
* The second row is copied into the first row and the process is repeated again
	- This is done to save memory, as having all rows loaded will vastly limit the scope of output