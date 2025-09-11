# x
- Joohoin kehittämä web fuzzing työkalu
- Työkalu yhdistää kaikki web fuzzing toiminnot
- Kannattaa käyttää valmiita hakemisto kirjastoja

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

Löytyi kansiot admin, admin/users ja admin/users/96

<img width="936" height="628" alt="Image" src="https://github.com/user-attachments/assets/0e2c95cb-d533-4e80-80e5-2d3177c45a3b" />



# Lähteet
Tero Karvinen. Find Hidden Web Directories - Fuzz URLs with ffuf. https://terokarvinen.com/2023/fuzz-urls-find-hidden-directories/

Tero Karvinen. Fuffme - Install Web Fuzzing Target on Debian. https://terokarvinen.com/2023/fuffme-web-fuzzing-target-debian/

HelSec. 0x03 Fuzzing Faster (U Fool) - joohoi - HelSec Virtual meetup #1. https://www.youtube.com/watch?v=mbmsT3AhwWU
