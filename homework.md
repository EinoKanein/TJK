# TJK
<img width="1440" alt="Näyttökuva 2021-9-12 kello 17 04 51" src="https://user-images.githubusercontent.com/85149952/132990691-ad121fe3-f416-42a9-97ff-3880681cf3f4.png">
-Ensin julistetaan että nimi == 'Eino Kanerva'
-Sitten printataan se.
<img width="1440" alt="Näyttökuva 2021-9-12 kello 14 43 37" src="https://user-images.githubusercontent.com/85149952/132986434-77c573de-a4a2-462d-95d0-bf9dd0eae3c9.png">
-seuraavaksi: getwd()
  ->Saan tietää mikä on tiedostopolku
  ->sitten setwd('/Users/einokanerva/Desktop/KOULU-R')
  ->Nyt on wd meikän uusi kansio
  <img width="1440" alt="Näyttökuva 2021-9-12 kello 15 01 58" src="https://user-images.githubusercontent.com/85149952/132986763-412fdc7e-1bae-4251-a95c-41ffb0208d43.png">
-x1 mitta-asteikko=laatueroasteikko
-x2 mitta-asteikko=laatueroasteikko
-x3 mitta-asteikko=suhdeasteikko
-x4 mitta-asteikko=laatueroasteikko
-x5 mitta-asteikko=suhdeasteikko
-x6 mitta-asteikko=suhdeasteikko
-x7 mitta-asteikko=järjestysasteikko
-x8 mitta-asteikko=suhdeasteikko
-x9 mitta-asteikko=suhdeasteikko
-Jos aineistossa olisi x10=opiskelijan syntymävuosi, se olisi jatkuva muuttuja(continuous variable) ja sen mitta-asteikko olisi suhdeasteikko(ratio scale)
  ->Voidaan ajatella 120v sitten olleen ajanhetken olevan se nollahetki
-Ohessa barplot x7
<img width="1440" alt="Näyttökuva 2021-9-12 kello 14 29 30" src="https://user-images.githubusercontent.com/85149952/132986884-b9316770-b6bc-4afe-a483-714dc08cd3d4.png">
-plot(x7,x6) eli "kuinka tarpeellisena näkee tilastotieteen" vs. "ennen kurssia suoritetun matikan testin pistemäärä"
<img width="1440" alt="Näyttökuva 2021-9-12 kello 16 47 16" src="https://user-images.githubusercontent.com/85149952/132990103-1fcd025e-e180-4a71-8b22-4ad57a1b1b11.png">
-Barplot niin, että numeroarvot on muutettu sanallisiksi.
<img width="1440" alt="Näyttökuva 2021-9-12 kello 16 54 49" src="https://user-images.githubusercontent.com/85149952/132990356-cae61def-a38d-4b7f-9c9f-d79481fdbd98.png">
-hist(x8)
<img width="1440" alt="Näyttökuva 2021-9-12 kello 16 56 09" src="https://user-images.githubusercontent.com/85149952/132990402-b13fad90-a332-4e74-9566-1b9620088156.png">
-plot(x8)
<img width="1440" alt="Näyttökuva 2021-9-12 kello 17 05 21" src="https://user-images.githubusercontent.com/85149952/132990712-1a9b96fa-a056-45b9-b78b-8e2946d3714e.png">
______
<img width="1440" alt="Näyttökuva 2021-9-15 kello 9 57 47" src="https://user-images.githubusercontent.com/85149952/133385576-f35156d9-cdd9-480d-8b4e-6223f347f363.png">
<img width="1440" alt="Näyttökuva 2021-9-15 kello 10 02 23" src="https://user-images.githubusercontent.com/85149952/133386529-7e11964b-dab4-47f3-891f-45d07b146995.png">
<img width="1440" alt="Näyttökuva 2021-9-15 kello 10 03 54" src="https://user-images.githubusercontent.com/85149952/133386541-6f4704b4-89e4-4257-aa0d-10da65ea35d5.png">
VIIKO 2 LÄKSY

TEHTÄVÄ 1:
A)∑4i=1xi=x1+x2+x3+x4=3+8+2+(−5)=8
B)∑4i=1x2i=x21+x22+x23+x24=32+82+22+(−5)2=102
C)∑3i=1(xi−2)2=(x1−2)2+(x2−2)2+(x3−2)2=12+62+02=37
D)(∑2i=1xi)2=(x1+x2)2=(3+8)2=112=121

TEHTÄVÄ 2:
A.
> median(AineistoA$x3)
[1] 21
0.75 fraktiili = 24
0.25 fraktiili = 20
B.
> summary(AineistoA$x3)
   Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
  19.00   20.00   21.00   21.98   23.75   30.00 
c.OIKEALLE VINO  
 
TEHTÄVÄ3:
> summary(AineistoA$x3)
   Min. 1st Qu.  Median    Mean 3rd Qu.    Max. 
  19.00   20.00   21.00   21.98   23.75   30.00 
<img width="1440" alt="Näyttökuva 2021-10-1 kello 9 04 01" src="https://user-images.githubusercontent.com/85149952/135573201-c5e086ac-5302-49a5-a365-6de24c5b2361.png">

TEHTÄVÄT 4 ja 5

![IMG_6845](https://user-images.githubusercontent.com/85149952/135574122-90547c1b-60d0-4ff1-ba4a-e9c7c0aa3d80.JPG)


> y <- AineistoA$x6[47:50]
> y
[1]  97  94 102  91
> mean(y)
[1] 96
> var(y)
[1] 22
> sd(y)
[1] 4.690416
> 

TEHTÄVÄ 6:
A:
> rv <- c(5.2, 9.3, 9.7, 8.0, 10.1, 7.5)
> mean(rv)
[1] 8.3
> sd(rv)
[1] 1.818791

B:
> rv1 <- c(-7.4, -15.6, -16.4, -13.0, -17.2, -12.0)
> mean(rv1)
[1] -13.6
> sd(rv1)
[1] 3.637582

TEHTÄVÄ 7:
KA nousee 20€ SYYSTÄ ETTÄ: a+bx a=20, b=1 ELI uusi ka on 20 + vanha ka
Keskihajonta ei muutu.
Mediaani nousee koska kaikkien palkka nousee. Palkkojen suuruusjärjestys pysyy samana. 

TEHTÄVÄ 8:
X ON VASEN DIAGRAMMI(SYMMETRINEN JA PIENIN JAKAUMA), Y ON OIKEAN PUOLEINEN DIAGRAMMI(OIKEALLE VINO), Z ON KESKIMMÄINEN(SYMMETRINEN MUTTA X:ÄÄ SUUREMPI JAKAUMA)

VIIKKO3 KOTITEHTÄVÄ:
t.1
∑4i=1xiyi=x1y1+x2y2+x3y3+x4y4=64
∑3i=1xi∑4i=1yi=x1∗(y1+y2+y3+y4)+x2∗(y1+y2+y3+y4)+x3∗(y1+y2+y3+y4)=312
∑4i=3∑3j=1xiyj=x3y1+x3y2+x3y3+x4y1+x4y2+x4y3=−51
∑3i=2(xi−2)(yi−6)=(x2−2)(y2−6)+(x3−2)(y3−6)=24
t.2

<img width="1440" alt="Näyttökuva 2021-10-1 kello 9 56 50" src="https://user-images.githubusercontent.com/85149952/135578412-34a214f5-05d5-4d67-a093-13ceb5fe0406.png">

t.3
![IMG_6951](https://user-images.githubusercontent.com/85149952/136406554-38f814cf-faf7-4fd0-8568-aabad0bc4f85.JPG)

t.5
![IMG_6961](https://user-images.githubusercontent.com/85149952/136406949-640fdfb1-2273-40c9-b950-1ac631def604.JPG)


t.6
<img width="1440" alt="Näyttökuva 2021-10-7 kello 17 37 12" src="https://user-images.githubusercontent.com/85149952/136406677-979a2329-aff9-4ad1-be40-e26a624772b7.png">
> cor(ukot,akat)
[1] 0.671784

b)Jos jokainen mies olisi 10cm lyhyempi, niin korrelaatiokerroin ei muuttuisi.
c)Pituuksien välillä olisi aivan täydellinen lineaarinen riippuvuus, niin korrelaatiokerroin olisi 1.

t.7
![IMG_6962](https://user-images.githubusercontent.com/85149952/136410994-97c28778-1f78-4648-b703-19275f21079d.JPG)

t.8
> mean(AineistoA$x8)
[1] 20.84
> sd(AineistoA$x8)
[1] 5.905238
> cor(AineistoA$x8,AineistoA$x9)
[1] 0.8964159
> OTOS.10 <- AineistoA[sample(1:50, replace=FALSE, size = 10), ]
> OTOS.10
   x1 x2 x3                      x4 x5  x6               x7 x8 x9
16 16  1 25    kasvatustieteellinen  2 107     tarpeellinen 29 25
20 20  1 19    kasvatustieteellinen  1 100      yhdentekeva 23 20
14 14  1 20 yhteiskuntatieteellinen  2 106     tarpeellinen 26 31
36 36  2 24            humanistinen  3  99 taysin tarpeeton 14 15
25 25  2 20            humanistinen  1 100      yhdentekeva 23 18
7   7  1 19 yhteiskuntatieteellinen  1  95 taysin tarpeeton 18 16
4   4  2 19 yhteiskuntatieteellinen  1 104      yhdentekeva 23 20
33 33  1 20 yhteiskuntatieteellinen  2  99      yhdentekeva 20 18
21 21  1 19    kasvatustieteellinen  1 104     tarpeellinen 27 25
24 24  2 24 yhteiskuntatieteellinen  4 100      yhdentekeva 20 23
> mean(OTOS.10$x8)
[1] 22.3
> SD(OTOS.10$x8)
Error in SD(OTOS.10$x8) : could not find function "SD"
> sd(OTOS.10$x8)
[1] 4.473378
> mean(OTOS.10$x9)
[1] 21.1
> cor(OTOS.10$x8, OTOS.10$x9)
[1] 0.7725959
Otoksesta saadut arvot pienemmät kuin populaation. Liian pieni otanta syynä.

t.9
Niiden ketkä vastasi ja niiden ketkä eivät vastanneet, suhteellista osuutta ihmispopulaatiosta tulee käyttää tuloksen tasapainottamiseen.




VIIKKO 4 KOTITEHTÄVÄ:
T.1
a)0.01
b)0
c)1
d)0.6

t.2

