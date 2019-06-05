# arvutiv6rgud
Hendrik Metsallik: võrgu testid
´´´
Lesson 1

Ping - Saab vaadata kas ühendus sinu ja mõne muu hosti vahel on võimalik.

printf - Saab sisestada teksti ja suuda eristada mõnda käsku näiteks \n et tekst hakkaks uuelt realt.

nc - Andmete edastamine internetiühenduste vahel.

| (pipe) - Outputi ülekandmine teise kohta.

-l - Paneb nc kindlale portile kuuldele.

Control-D - Disconnectib netcati portist.

> - Saab saata nc commandi vastuse file sisse.
´´´

Lesson 2

CTRL + C - Lõpetab kindla protsessi näiteks ping käsu.
host - Nagu DNS, veebilehe sisse kirjutamisel tõlgib selle IP-ks.
dig - nagu host, aga annab rohkem informatsiooni.


Lesson 3

Käske väga polnud, vaid rääkis rohkem kuidas maailmas pole piisavalt IP-si kõigile ning sellele on juba lahendus. 
Praegune lahendus on NAT süsteem, ruuteritel on private IP mis on maja peale jaotatud.


Lesson 4

tcpdump - Saab vaadata DNS trafficut.
Rääkis miks on packetid vajalikud ja kuidas nad töötavad.
Pika aja peale kui üks pool ei saa teiselt vastust siis ühendus katkeb.


Lesson 5

traceroute - Näitab kõiki IP-si mida sa läbisid enne kui jõudsid soovitud aadressile.
Käske oli vähe ja rääkis rohkem, et ruuter ei suuda lasta väga suurt arvu packeteid korraga läbi ning mida ta teeb selle jaoks.
Rääkis ka, et seadmetel on firewall, mis filtreerib tegevust seadme ja võrgu vahel.


# Mida ma huvitavat teada sain
Portid 1023 ja vähem on reserveeritud.

IPv4 aadresseid on üle 4,3 miljardit.

IP-d on jagatud octetidesse ja IP-l on eraldi veel host IP-d.

Inimestel saab olla samad IP-d kui nad on NAT-iga eraldatud.

Ühendusvea asukohast saab teada errori käitumisest, näiteks TCP-ga "timeoutid".

Sain teada kuidas timeout tekib.

Interneti operaatorid nimetavad enda "node"-d läheduses olevate lennujaamadega, et neid oleks geograafiliselt kergem leida.

Packetitel on Time to live, et ei tekiks infinite loopi.
