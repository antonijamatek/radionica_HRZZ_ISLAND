Ovo je repozitorij koji uključuje podatke i skripte za analizu kontinuiranih mjerenja svjetlosti u programskom jeziku R u sklopu radionice HRZZ projekta ISLAND: **"Obrada kontinuiranih mjerenja u biološkoj oceanografiji".**

**Instalacija programskog jezika R:**
https://cloud.r-project.org/

Izaberi: download R for Linux/macOS/Windows, zatim na "Install R for the first time" i zatim na Download R-4.4.0 for Linux/macOS/Windows. 

**Instalacija sučelja R studio:**
https://posit.co/download/rstudio-desktop/

Niže na stranici nalaze se opcije za različite operacijske sustave. 

Paket je skup funkcija koji su grupirani zajedno radi lakšeg korištenja. Primjerice paket „plotly” sadrži funkcije za izradu grafičkih prikaza u programskom jeziku R.

Pri instalaciji programskog jezika dobijete i skup osnovnih paketa za korištenje, te postoji mnogo dodatnih paketa koje možete naknadno instalirati.

**Za instalaciju i učitavanje paketa potrebnih za rad na radionici preuzmite i pokrenite sljedeće skripte u R studiu:**

1. Paketi_instalacija.R - sve potrebne funkcije koje ćemo trebati pri analizi 
2. Paketi_ucitavanje.R - naredbe za učitavanje instaliranih paketa prije početka rada

Otvoriti skriptu Paketi_instalacija.R, te pokrenuti naredbe "install.packages()" klikom na ctrl + enter.

Učitavanje paketa će se odraditi na radionici. 
Također, cijeli proces ćemo ponoviti i na samoj radionici ukoliko imate problema sa samostalnom instalacijom programa i/ili paketa.

**Podaci**

**Zrmanja.zip** 
- csv. datoteke sa vrijednostima intenziteta svjetlosti (LUX) na površini i 8 m dubine. Mjerenja su uzimana u periodu od 30.04 do 03.05. 2024. godine. Iako su mjerenja uzimana u kraćem periodu, ovaj set podataka biti će pokazni primjer kako prepoznati probleme/šumove u podacima i odrediti da li su podaci reprezentativni i prikladni za daljnje analize. Senzori su mjerili u intervalu od svake minute i svakih 5 minuta.

**Lastovo.zip**
- csv. datoteke sa PAR (eng. photosynthetically active radiation) vrijednostima na 10 m i 40 m dubine. Mjerenja su uzimana u periodu od kraja srpnja do početka listopapa u 2022. godini na južnoj strani otoka Lastova (postaja Struga). Senzori su mjerili u intervalu od svakih 5 minuta. Ovaj set podataka je primjer dugog niza mjerenja. 

  ![image](https://github.com/antonijamatek/radionica_HRZZ_ISLAND/assets/144710084/68dcc0f4-4aea-4730-a558-c7c7d5197a5d)

**Rad na vlastitim podacima je dobro došao :)**


**RADNE SKRIPTE**

- .Rproj - projekt kojeg stvaramo unutar R sučelja kako bi sačuvali rad u svim skriptama koje koristimo
- .R - R skripta u kojoj se nalazi kod na kojem radimo

1. Uvod u R.zip : zip datoteka sastoji se od dva file - a: Uvod u R.Rproj i osnovne radnje u R-u.R. U ovom dijelu se upoznajemo sa osnovama strukture podataka i pridruživanja varijabli unutar sučelja R Studio

2. LUX.zip: zip datoteka u kojoj se nalazi direktorij u kojem ćemo provoditi analizu tijekom radionice. U direktoriju nalaze se potrebne radne skripte i podaci.  

3. PAR.zip: zip datoteka u kojoj se nalazi direktorij sa skriptama i podacima za provođenje analize dugog vremenskog niza PAR-a. Skripte sadrže potpuni kod te će sudionici imati pristup kodu i nakon radionice kako bi mogli samostalno vježbati i učiti, te primjeniti kod na vlastitim podacima. 
