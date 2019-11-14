#Jednostavan modul
Cilj ove vezbe je da se krene od "Hello" modula sa samo init_module i exit_module funkcijama, te da se napravi jednostavan drajver koji ispisuje poruke u terminalu kada se nesto pokusa upisati ili procitati iz njega.
Resenje je dato u "Hello_static" i "Hello_dynamic" direktorijumima. Dobijeni su makefajlovi pomocu kojih se moduli mogu kompajlirati pozivom komande "make".
	- Hello_static koristi staticko alociranje te je potrebno pozvati komande "mknod /dev/hello c 240 0" i "insmod Hello.ko".
	- Hello_dynamic koristi dinamicko alociranje te je potrebno samo pozvati "insmod Hello.ko". Gledati ispise kernel poruka pomocu "dmesg" komande.  
