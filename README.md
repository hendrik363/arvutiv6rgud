# arvutiv6rgud
Hendrik Metsallik: võrgu testid  
```
Lesson 1*    
  
Ping - Lubab vaadata kas ühendus on võimalik sinu ja mõne teise hosti vahel.   
printf - Saab sisestada teksti ja suuda eristada mõnda käsku näiteks \n et tekst hakkaks uuelt realt.  
nc - Andmete edastamine internetiühenduste vahel.  
| (pipe) - Outputi paigaldus teise kohta.  
-l - Paneb nc kindlale portile kuuldele.  
Control-D - Disconnectib netcati portist.  
> - Saab saata nc käsu vastuse faili.  
```  
```  
Lesson 2*

CTRL + C - Lõpetab kindla protsessi nagu näiteks ping käsu.
host - Sarnane DNS-ile, veebilehe sisse kirjutamisel tõlgib selle IP-ks.
dig - sarnane host-ile, kuid väljastab rohkem informatsiooni.
```  
```  
Lesson 3*

Käske väga polnud, kuid ta rääkis kuidas maailmas ei ole piisavalt IP-si igaühele ning kuidas sellele on juba lahendus olemas. 
Lahenduseks on NAT süsteem, ruuteritel on privaatne IP, mis on maja peale jaotatud.
```  
```  
Lesson 4*

tcpdump - Saab jälgida DNS trafficut.
Rääkis miks on vajalikud packetid ning kuidas nad töötavad.
Pärast pikka aega kui üks pool ei saa teiselt vastust siis ühendus katkeb.
```  
```  
Lesson 5*

traceroute - Näitab kõiki IP-si mida läbiti enne kui jõuti soovitud aadressile.
Jällegi oli käske vähe ning pigem rääkis, et ruuter ei ole võimeline laskma väga palju packeteid korraga läbi ja mis on selle lahenduseks.
Rääkis ka, et seadmetel on firewall, mis filtreerib tegevust seadme ja võrgu vahel.
```  
```  
# Mida ma huvitavat teada sain  
Packetitel on eluaeg, et ei tekiks lõpmatud loopi.

Portid 1023 ja vähem on reserveeritud.

Sain teada kuidas timeout tekib.

IP-l on eraldi host IP-d ning IP-d on jagatud octetidesse.

Inimestel saab olla samad IP-d kui nad on NAT-iga eraldatud.

Ühendusvea asukohast saab teada errori käitumisest, näiteks TCP-ga "timeoutid".

Packetitel on eluaeg, et ei tekiks lõpmatud loopi.
```  
