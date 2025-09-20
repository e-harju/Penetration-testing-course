# x.
- Järjestelmät tallentaa salasanat hasheina
- Hashcat on työkalu, joka etsii vastikkeita hashille kirjastoista 
- Tykkään, että komentojen parametrit on avattu ohjeessa
<br>

- John the Ripper työkalua käytetään murtamaan tiedostojen salasana hasheja
- Esimerkki komennot oli monimutkaiset (en kuitenkaan tiedä, onko se paras/ainoa tapa selittää ne)
<br>

- Videoissa asiat oli selitetty selkeästi
- Demot Hashcatista ja John the Ripperistä olivat hyödyllisiä, kun en ole ennen käyttänyt ohjelmia.

# a

Tein aluksi lataukset ja loin tiedoston, johon tekemäni jutut tallentuu. Kokeilin myös, että tiedostot rockyou.txt toimii.

<img width="232" height="578" alt="image" src="https://github.com/user-attachments/assets/ed488e8f-efdd-4296-85c7-6fb1546e3485" />

Seuraavaksi identifioin hashin tyypin.

<img width="440" height="406" alt="image" src="https://github.com/user-attachments/assets/9cd3951f-081f-4ca6-84f3-354f9788dfd8" />

Viimeseksi murran salasanan etsimällä hashia vastaavan salasanan ja tallennan murretun salasanan tiedostoon "solved".

<img width="1206" height="369" alt="image" src="https://github.com/user-attachments/assets/69f8b266-6ef9-41cd-a5ab-9d3240d3f74e" />

# b

Tässä tehtävässä kokeilen John the Ripperin käyttöä. Ensimmäiseksi päivitän apt-get kirjaston ja lataan tarvittavat tiedostot. Ensin komento ei toiminut, kun se sisälsi zlib-gst tiedoston, mutta poistamalla sen sain komennon toimimaan.

<img width="1178" height="706" alt="image" src="https://github.com/user-attachments/assets/fceb09c5-87c7-4a5b-867d-8e41ebcbc118" />

Sueraavaksi lataan ja konfiguroin John the Ripperin.

<img width="649" height="202" alt="image" src="https://github.com/user-attachments/assets/ab21f900-c139-42fd-80a4-d7ecb5d52f1f" />

<img width="293" height="87" alt="image" src="https://github.com/user-attachments/assets/3c4e0c59-b2c4-44da-8ee4-f75409ab00ff" />

<img width="658" height="505" alt="image" src="https://github.com/user-attachments/assets/b475d988-3572-46f8-8f23-7dfd978950f3" />

Seuraavaksi käännän koodin toimivaksi ohjelmaksi.

<img width="318" height="184" alt="image" src="https://github.com/user-attachments/assets/c0ccf560-72e0-475f-806a-bc5ab95e0c1f" />



# Lähteet

Tero Karvinen. Cracking Passwords with Hashcat. https://terokarvinen.com/2022/cracking-passwords-with-hashcat/

Tero Karvinen. Crack File Password With John. https://terokarvinen.com/2023/crack-file-password-with-john/

Omar Santos, Jon Sternstein, Ron Tayor & Chris McCoy. Security Penetration Testing The Art of Hacking Series LiveLessons. Lesson 6: Hacking User Credentials. https://learning.oreilly.com/videos/security-penetration-testing/9780134833989/9780134833989-sptt_00_06_00_00/
