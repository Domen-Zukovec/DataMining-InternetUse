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
