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

# c

Tässä tehtävässä kokeilen John the Ripperin käyttöä. Ensimmäiseksi päivitän apt-get kirjaston ja lataan tarvittavat tiedostot. Ensin komento ei toiminut, kun se sisälsi zlib-gst tiedoston, mutta poistamalla sen sain komennon toimimaan.

<img width="1178" height="706" alt="image" src="https://github.com/user-attachments/assets/fceb09c5-87c7-4a5b-867d-8e41ebcbc118" />

Sueraavaksi lataan ja konfiguroin John the Ripperin.

<img width="649" height="202" alt="image" src="https://github.com/user-attachments/assets/ab21f900-c139-42fd-80a4-d7ecb5d52f1f" />

<br>

<img width="293" height="87" alt="image" src="https://github.com/user-attachments/assets/3c4e0c59-b2c4-44da-8ee4-f75409ab00ff" />

<br>

<img width="658" height="505" alt="image" src="https://github.com/user-attachments/assets/b475d988-3572-46f8-8f23-7dfd978950f3" />

Seuraavaksi käännän koodin toimivaksi ohjelmaksi.

<img width="318" height="184" alt="image" src="https://github.com/user-attachments/assets/c0ccf560-72e0-475f-806a-bc5ab95e0c1f" />

Run tiedostosta löytyy scriptit.

<img width="562" height="924" alt="image" src="https://github.com/user-attachments/assets/2df8bbd8-433d-4d3a-8917-67b8a7a783a1" />

Sitten ajetaan ohjelma.

<img width="918" height="213" alt="image" src="https://github.com/user-attachments/assets/ad749c0e-26f9-404e-a862-6fd10c9f2275" />

Lataan ZIP-tiedoston harjoittelumaaliksi ja koitan avata sen.

<img width="1853" height="414" alt="image" src="https://github.com/user-attachments/assets/bd2c79ee-9edd-44bf-8a68-326eb8e949c6" />

En tiedä salasanaa, joten koitetaan murtaa se. Löysin salasanan butterfly.

<img width="1125" height="412" alt="image" src="https://github.com/user-attachments/assets/0d58ed37-e536-4bc3-9566-a031b4e4b01b" />

<img width="601" height="329" alt="image" src="https://github.com/user-attachments/assets/8bf889bc-a4b8-4dd6-a60b-cc1baa0d1bfb" />

# e

Latasin testi kohteen Openwallin githubista. https://github.com/openwall/john-samples/blob/main/7-Zip/7z-easy.7z. Loin tiedostolle hashin 7z2john.pl scriptillä.

<img width="890" height="56" alt="image" src="https://github.com/user-attachments/assets/46e1dd3b-d5b5-4095-a057-f26a819ef2a6" />

Löysin matchin ja sain avattua tiedoston.

<img width="855" height="829" alt="image" src="https://github.com/user-attachments/assets/568a8855-2ef3-46c9-ab97-a4f1a1bd5859" />

<img width="568" height="461" alt="image" src="https://github.com/user-attachments/assets/7b9ce18d-4eff-4f5d-97dc-35d20b70fd5c" />

# f

Generoin sha-1 hashin Hash Generatorilla.

<img width="1568" height="966" alt="image" src="https://github.com/user-attachments/assets/bcaa9700-1430-4332-b30b-35aef50b8066" />

Varmistan hashid:n

<img width="450" height="205" alt="image" src="https://github.com/user-attachments/assets/9e4ba69f-f6ae-4e7e-a6d9-3d9acebdc634" />

Etsin hashille vastikkeen.

<img width="1210" height="770" alt="image" src="https://github.com/user-attachments/assets/718c68b1-4937-457f-82ff-9565be810881" />

<img width="412" height="64" alt="image" src="https://github.com/user-attachments/assets/894766a7-e143-4824-9018-11bede27492c" />

# Lähteet

Hash Generator. https://hash-generator.com/sha-1-hash-generator/

Omar Santos, Jon Sternstein, Ron Tayor & Chris McCoy. Security Penetration Testing The Art of Hacking Series LiveLessons. Lesson 6: Hacking User Credentials. https://learning.oreilly.com/videos/security-penetration-testing/9780134833989/9780134833989-sptt_00_06_00_00/

Openwall. john-samples. https://github.com/openwall/john-samples/blob/main/7-Zip/7z-easy.7z

Tero Karvinen. Crack File Password With John. https://terokarvinen.com/2023/crack-file-password-with-john/

Tero Karvinen. Cracking Passwords with Hashcat. https://terokarvinen.com/2022/cracking-passwords-with-hashcat/
