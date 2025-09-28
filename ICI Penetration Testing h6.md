# a

Lataasin kohdekoneelle Wiresharkin.

<img width="1286" height="807" alt="image" src="https://github.com/user-attachments/assets/8ecef362-b0b8-427f-a178-c4054a1e1224" />

Luon exploitin msfvenomilla.

<img width="779" height="199" alt="image" src="https://github.com/user-attachments/assets/1ce68759-65f8-4025-9a77-e9e843e0da27" />

Käynnistän multi handlerin.

<img width="550" height="153" alt="image" src="https://github.com/user-attachments/assets/0efc280b-ba21-48fb-8ccb-ff0aa09f589f" />

Meni hetken aikaa, kun tein h5 tehtävän payloadilla. Staged payload toimi host-only adapterilla, mutta ei bridged adapterilla. Yrittäessä ajaa elf tiedostoa se antoi vain segmentation fault -erroria. Jouduin kokeilemaan stageless komentoa shell_reverse_tcp, joka sitten toimi. Löysin apua täältä: https://github.com/rapid7/metasploit-framework/issues/12142.

<img width="778" height="149" alt="image" src="https://github.com/user-attachments/assets/dcd8c873-35c2-4291-8809-cbcc058331e3" />

<img width="829" height="295" alt="image" src="https://github.com/user-attachments/assets/2b4a722a-074b-48bf-878d-591c378a7ce0" />

Wiresharkissa näkyy ls -la pyyntö ja vastaus.



# Lähteet

GitHub. Segmentation fault for reverse shell linux both x86 and x64. https://github.com/rapid7/metasploit-framework/issues/12142

Tero Karvinen. Tunkeutumistestaus. https://terokarvinen.com/tunkeutumistestaus/#h6-simpukoita
