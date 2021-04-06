# Uporaba interneta, po starosti in spolu #


### Pogled na podatke glede na spol ###
Za začetek sva podatke uvozila v Jupyter Notebook s pomočjo knjižnjice pandas.
![Uvoz](/images/uvoz.png)

Dobila sva tabelo podatkov, katero lahko uporabljava za prikazovanje.
![Tabela](/images/tabela.png)
## Domen Žukovec ##
Opazil sem, da najbolj uporabljene internetne storitve skozi leta težko prikazujem ker se najbolj popularne prikažejo večkrat (tudi do petkrat).
Odločil sem se, da bom za začetni prikaz uporabil samo leto 2015 in se kasneje posvetil še ostalim letom.

Prikaz namena uporabe interneta za moške(levo) in ženske(desno) vseh starosti leta 2015:
![Prvi graf](/images/1.png)

Na podoben način sem nato prikazal še uporabo interneta med ženskami in moškimi za 3 različne starostne skupine. Ampak je bil prikaz z "bar" grafom neprimeren, saj ni bil kaj pretirano zanimiv. Opaziti se je dalo, da se med moškimi in ženskami namen uporabe interneta razlikuje ne samo med spoloma ampak tudi glede na starostno skupino, a ker obstajajo boljši načini za prikaz sem se odločil, da jih tu ne bom prikazal in se bom kasneje posvetil boljšemu prikazu.

Zanimalo me je tudi kako se gibljejo najbolj priljubljeni nameni uporabe interneta med starostnimi skupinami pri ženskah in moških.

Moški:
![leto moški](/images/letomoški.png)

Ženske:
![leto ženske](/images/letoženske.png)

Nato sem se odločil, da bi rad prikazal razliko med številom uporabe interneta med ženskami in moškimi skozi leta.
![M vs Z](/images/mvsz.png)

Po izrisu grafa sem ugotovil, da mi tak prikaz ne pomaga, saj so razlike skozi leta lahko odvisne od števila ljudi, ki so delili svoje podatke in ne prikazujejo dejanskega trenda uporabe interneta.

Odločil sem se da bom kljub temu poskusil še izris prikaza uporabe interneta skozi leta za različne starostne skupine (Prikaz samo moškega spola):
![M vs Z](/images/starostne_skupine.png)

Spet sem takoj pomislil da so lahko padci (leta 2016 pri moških starih 16-24 in leta 2018 pri moških starih 25-54) samo posledica števila podatkov, ki so jih tisto leto uspeli pridobiti. Zanimalo me je, če si bi lahko namesto z številkami lahko pomagal z deleži (npr. za leto 2015 sem število uporabnikov interneta starostne skupine 16-24 delil z številom vseh uporabnikov istega leta)

Starosti: 16-24 ... 25-54 .. 55-74(Prikaz samo moškega spola).
![M vs Z](/images/starostne_skupine_deleži.png)

Ko sem že mislil, da so zdaj grafi dejanski prikaz uporabe interneta skozi leta za starostne skupine moških, sem se spomnil, da odstopanje spet lahko povzroča samo število podatkov, ki so jih tisto leto pridobili za določeno starostno skupino. Lahko se je zgodilo, da so leto 2017 preprosto dobili manj podatkov za uporabnike starosti 16-24.

Torej ugotovil sem, da bo prikaz podatkov skozi vsa leta neprimeren, saj so odvisni od števila uporabnikov, ki so dali podatke (in seveda tudi koliko od teh uporabnikov je bilo moških ali žensk ter koliko so bili stari). Bolj pametno se bi bilo posvetiti iskanju zanimivih prikazov enega leta na enkrat. Mogoče bom lahko potem, ko bom imel dobre prikaze in podatke za določena leta, lahko s pomočjo le teh prikazal tudi kaj zanimivega skozi več let skupaj.




## Dragan Spasovski ##

Ker sem se lotil vizualizacije podatkov glede na starost udeležencev ankete, sem si kot osnovni primer vzel leto 2015. Namen tega je, da dobim občutek, kako približno izgledajo podatki in da bi mogoče dobil kakšen namig, na kaj naj sem pozoren v prihodnosti. 
![2015leta](/images/2015leta.png)

Iz grafov je bilo očitno, da (vsaj v letu 2015) večino anketirancev internet uporablja za Pošiljanje in prejemanje e-pošte, (najbolj popularen med izbirami, saj je ali najbolj ali 2. najbolj uporabljen namen), Iskanje informacij za blago ali storitev in Branje novic. Če odvzamemo "konstanti", ki sta e-pošta in iskanje informacij za blago ali storitev, "mlajša" generacija od 16-24 internet uporablja še za sodelovanje v družabnih omrežjih, medtem pa lahko tudi opazimo naraščajoči trend pri osebah srednjih-starejših let in sicer Iskanje informacij povezanih z zdravjem.

Podatki so bili dokaj podobni tem, kar sem pričakoval, zato sem naredil še iste grafe skozi leta, le tokrat zanemarim starost.

### Leto 2015: ###
![2015](/images/2015.png)

### Leto 2016: ###
![2016](/images/2016.png)

### Leto 2017: ###
![2017](/images/2017.png)

### Leto 2018: ###
![2018](/images/2018.png)

Do leta 2018 imamo spet naše konstante, z izjemo Gledanja video vsebin na internetu (Youtube), Iskanja informacij za zdravje in Sodelovanje v družabnih omrežjih.

### Leto 2019: ###
![2019](/images/2019.png)

Tukaj opazimo Predvajanje glasbe, predvidevam, da je to zaradi Gledanja video vsebin na internetu.
### Leto 2020: ###
![2020](/images/download.png)

Tukaj sem opazil najbolj zanimiv podatek in sicer Uporaba odprtokodnih storitev in programov.


Zaradi variranja podatkov na 5. , 4. in 3. mestu, me je zanimalo, kako se je spreminjalo število rednih uporabnikov interneta, glede na leto in starost.

### Redni: ###
![redni](/images/redni.png)

Graf relativno linearno raste, z izjemo majhnega platoja v letu 2017.

### Starost 16-24: ###
![1624](/images/1624.png)

Saj so najmlajši in odraščali skupaj z razvojem interneta, se redni uporabniki interneta (v zadnjih 3 mesecih) gibljejo isto kot vsi uporabiki.

### Starost 25-34: ###
![2534](/images/2534.png)

Zanimivo je to, da je edina starostna skupina, ki ne raste. Mogoče je kakšen vzrok za to?

### Starost 35-44: ###
![3544](/images/3544.png)

Od tukaj naprej grafi začnejo rasti. Začne se starost, kjer niso vsi odraščali z internetom.

### Starost 45-54: ###
![4555](/images/4555.png)

### Starost 55-64: ###
![5565](/images/5565.png)

### Starost 65-74: ###
![4555](/images/6574.png)

Od leta 35 do 55 graf raste a ne tako hitro, kot pri ljudjeh, ki so 55+.

Grafi prikažejo kar nekaj zanimivosti, katere nameravam odkriti. Zanima me povezava med dogajanjem v letu in uporabo interneta.
