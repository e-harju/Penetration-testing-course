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




# Lähteet

Tero Karvinen. Cracking Passwords with Hashcat. https://terokarvinen.com/2022/cracking-passwords-with-hashcat/

Tero Karvinen. Crack File Password With John. https://terokarvinen.com/2023/crack-file-password-with-john/

Omar Santos, Jon Sternstein, Ron Tayor & Chris McCoy. Security Penetration Testing The Art of Hacking Series LiveLessons. Lesson 6: Hacking User Credentials. https://learning.oreilly.com/videos/security-penetration-testing/9780134833989/9780134833989-sptt_00_06_00_00/
