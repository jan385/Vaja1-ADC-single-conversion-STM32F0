# Vaja1-ADC-single-conversion-STM32F0
b) Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to? 

     PC0

c) Koliko ADC pretvornikov ima vaša razvojna ploščica? 

    1

d1) Izbrani ADC pretvornik ima oznako s trikotnikom. Kaj to pomeni? 

       To pomeni da je pin zaseden oz.  je delno v konfliktu z drugim pinom

d2) Kaj morate storiti, da razrešite to omejitev?

       Da se ga znebimo, kliknemo na PA0 na ploščici in nato klikenmo Reset_State

e) Razširite razdelek ADC. Koliko je vseh vhodnih kanalov?
   
     Vseh vhodnih kanalov je 16

f) Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina?

    Poleg njega se  izpiše ADC_IN10

h) V Configuration kliknemo ADC gumb. V Parameter settings izberite ločljivost pretvorbe na 8-bitno, torej je območje vrednosti od 0 ÷ 255. Kakšne so še ostale možne ločljivosti pretvorbe in območja vrednosti?
     
     a.  6-bitno, od 0 do 63

     b. 10-bitno, od 0 do 1023

     c. 12-bitno, od 0 do 4095

Komentar: ARM mikroprocesor smo sprogramirali tako, da izvede posamične ADC pretvorbe z izbranim potenciometrom
