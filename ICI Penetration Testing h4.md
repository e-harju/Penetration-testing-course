# x
- Joohoin kehittämä web fuzzing työkalu
- Työkalu yhdistää kaikki web fuzzing toiminnot
- Kannattaa käyttää valmiita hakemisto kirjastoja
<br>
- Tavallisia kohteita ovat GET parametrit, headerit ja POST data
- Kannattaa tarkkailla vastauskoodeja, sisältöä ja vastausten kokoja
- Video oli mielestäni hyvin tehty ja informatiivinen
- Tykkäsin itse erityisesti demoista

# a
Teen tehtävät Debianilla. Harjoittelin käyttöä dirfuz-0.

Latasin ffuf:in ja Seclistin.

<img width="1234" height="544" alt="Image" src="https://github.com/user-attachments/assets/8f58ee43-f743-4d2e-b89d-f64594f0d5ff" />

Testasin, että ffuf toimii.

<img width="762" height="723" alt="Image" src="https://github.com/user-attachments/assets/66a71a3d-2908-4c22-a83d-2536ddca5642" />

Latasin ja pistin ensimmäisen tehtävän päälle.

<img width="1221" height="306" alt="Image" src="https://github.com/user-attachments/assets/35866b35-cfd9-41aa-b9b1-e7baaf860f1a" />

Suodatin pois 154 kokoiset tulokset, jotta löydän jotain poikkeavaa.

<img width="811" height="589" alt="Image" src="https://github.com/user-attachments/assets/62e1ab4c-c971-422c-a305-29d713c55e48" />

Läysin tiedoston wp-admin ja avasin sen. Löysin lipun.

<img width="510" height="201" alt="Image" src="https://github.com/user-attachments/assets/5cbc8286-0c5a-4630-b821-b62c41672f8f" />

Löysin myös versionhallinta lipun.

<img width="452" height="191" alt="Image" src="https://github.com/user-attachments/assets/d229778c-f80c-450f-930c-90cc7d4feddd" />

# b

Lataan fuffme dockerin Debianiin.

<img width="1254" height="494" alt="Image" src="https://github.com/user-attachments/assets/4cf8a005-a04d-4591-8bf0-77dd89f13811" />

Harjoitusmaali toimii.

<img width="1269" height="722" alt="Image" src="https://github.com/user-attachments/assets/8e361003-57de-4c8e-90b6-0268e3ff8cc1" />

Sanakirjat asennettu.

<img width="1231" height="704" alt="Image" src="https://github.com/user-attachments/assets/8c98b566-6636-4c7f-be68-539bb02ee765" />

# c

Löysin class ja development.log hakemistot.

<img width="844" height="82" alt="Image" src="https://github.com/user-attachments/assets/58ee1b9d-678b-459d-8383-f83a09b9c08c" />

<img width="451" height="116" alt="Image" src="https://github.com/user-attachments/assets/6afee594-6730-412b-b892-8c547d936228" />

<img width="532" height="125" alt="Image" src="https://github.com/user-attachments/assets/63c6e9d0-390b-4422-b6cf-b1e6ef46382e" />

# d

Löytyi kansiot admin, admin/users ja admin/users/96.

<img width="936" height="628" alt="Image" src="https://github.com/user-attachments/assets/0e2c95cb-d533-4e80-80e5-2d3177c45a3b" />

Minulla ei ollut pääsyä admin tai admin/users hakemistoja, mutta pääsin käyttäjälle 96.

<img width="549" height="125" alt="Image" src="https://github.com/user-attachments/assets/6fa6273e-ea57-4533-a888-34865596a0b0" />

# e

Löysin kohde hakemiston.

<img width="900" height="471" alt="Image" src="https://github.com/user-attachments/assets/7f1250d0-37ef-4678-870e-47969dc6c35c" />

<img width="496" height="122" alt="Image" src="https://github.com/user-attachments/assets/c75c93a8-e4bb-43ff-8f98-f8430697caf0" />

# f

Ensiksi hain kaikki hakemistot, mutta sitten rajasin pois kaikki 669 kokoiset.

<img width="842" height="465" alt="Image" src="https://github.com/user-attachments/assets/23092000-f1f7-4245-aada-c7db1d661c5d" />

Löysin tämän secretistä.

<img width="466" height="125" alt="Image" src="https://github.com/user-attachments/assets/0959e7c0-af6b-43c5-8eb9-b2c11ed66959" />

# g

Hain sivun, mutta siitä puuttuu parametrejä.

<img width="451" height="126" alt="Image" src="https://github.com/user-attachments/assets/5df5c798-7629-4305-8144-a37a89cf201c" />

Seuraavalla komennolla yritän etsiä puuttuvan parametrin.

<img width="499" height="114" alt="Image" src="https://github.com/user-attachments/assets/40b348f1-0784-4415-a655-ea7879584988" />

# h

Ensimmäisellä komennolla tulee 429 statusta eli minut estettiin tekemästä uusia pyyntöjä.

<img width="855" height="650" alt="image" src="https://github.com/user-attachments/assets/c2e317f7-db69-4187-b8f5-596d7b4a88d7" />

Jos taas rajoitan pyyntöjen nopeuden en saa enää 429 statusta ja löydän oracle nimisen tiedoston.

<img width="969" height="474" alt="image" src="https://github.com/user-attachments/assets/e52fe06a-7f86-4849-b77e-d55a54dcad7c" />

<img width="446" height="151" alt="image" src="https://github.com/user-attachments/assets/be8a647d-ec66-4460-b577-bd91aad21f0a" />

# i

Ajan komennon, jolla yritän löytää subdomainin virtual hostin avulla muuttamalla host headeria.

<img width="888" height="659" alt="image" src="https://github.com/user-attachments/assets/4314a740-6660-4966-93d6-0d525daf6c16" />

Seuraavaksi suodatan muut vastaukset löytääkseni etsimäni subdomainin.

<img width="974" height="485" alt="image" src="https://github.com/user-attachments/assets/8882f21b-f2e1-4502-9a70-afb7ca820304" />

Löysin redhat nimisen subdomainin, joka toimii.

<img width="976" height="631" alt="image" src="https://github.com/user-attachments/assets/4626a6c3-770e-4d1c-9a29-febfccf85802" />


# Lähteet
Tero Karvinen. Find Hidden Web Directories - Fuzz URLs with ffuf. https://terokarvinen.com/2023/fuzz-urls-find-hidden-directories/

Tero Karvinen. Fuffme - Install Web Fuzzing Target on Debian. https://terokarvinen.com/2023/fuffme-web-fuzzing-target-debian/

HelSec. 0x03 Fuzzing Faster (U Fool) - joohoi - HelSec Virtual meetup #1. https://www.youtube.com/watch?v=mbmsT3AhwWU
