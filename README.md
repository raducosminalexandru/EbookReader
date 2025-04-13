# OpenBook - E-book Reader Open-Source

In cadrul proiectului **OpenBook**, ne propunem sa revoluționam industria cititului digital prin dezvoltarea unui **e-book reader accesibil, eficient si open-source**. 🌍📚

Cu tehnologia de astazi, accesul la informatie este mai rapid ca niciodata, iar **OpenBook** isi propune sa ofere o solutie accesibila tuturor celor care doresc sa citeasca oriunde, oricand, fara a depinde de preturi exorbitante sau de platforme inchise. Suntem o echipa pasionata si inovativa, iar rolul nostru in acest proiect este sa creem un dispozitiv care sa ofere o experienta de citire excelenta si sa fie disponibil pentru toti utilizatorii, fara bariere. 💡

**OpenBook** este un e-book reader care va permite cititorilor sa acceseze si sa citeasca carti digitale intr-un mod simplu si eficient. Acesta ofera o solutie economica si open-source, ceea ce inseamna ca orice persoana va putea sa-l foloseasca, personalizeze sau imbunatateasca, fara restrictii legate de software sau costuri ridicate.

## Cum functioneaza

Prin utilizarea unor componente hardware eficiente si un software open-source, **OpenBook** va oferi o experienta de citire fluida, cu un design simplu si intuitiv. Acesta va suporta formate de carti populare si va fi usor de utilizat, chiar si pentru utilizatorii care nu sunt familiarizati cu tehnologia.

Prin intermediul acestui dispozitiv, punem bazele unui produs care va oferi cititorilor libertatea de a se bucura de carti digitale intr-un mod accesibil si fara compromisuri in ceea ce priveste performanta si functionalitatea.

## Bill of Materials (BOM) - varianta succinta a fisierului BOM

| Componenta               | Link si Datasheet                                                                                           |
|--------------------------|-------------------------------------------------------------------------------------------------------------|
| **ESP32-C6-WROOM-1-N8**   | [Mouser](https://eu.mouser.com/ProductDetail/Espressif-Systems/ESP32-C6-WROOM-1-N8?qs=8Wlm6%252BaMh8ST02Gmwp74cw%3D%3D) |
| **W25Q512JVEIQ**               | [Mouser](https://eu.mouser.com/ProductDetail/Winbond/W25Q512JVEIQ?qs=l7cgNqFNU1jw6svr3at6tA%3D%3D)                                             |
| **DS3231SN#**       | [Mouser](https://www.mouser.ro/ProductDetail/100uF-Capacitor](https://eu.mouser.com/ProductDetail/Analog-Devices-Maxim-Integrated/DS3231SN?qs=1eQvB6Dk1vhUlr8%2FOrV0Fw%3D%3D))                                         |
| **FH34SRJ-24S-0.5SH** | [Mouser](https://www.mouser.ro/ProductDetail/Atmel/ATMEGA328P](https://eu.mouser.com/ProductDetail/Hirose-Connector/FH34SRJ-24S-0.5SH50?qs=iyLo5FA4poC8fzWlavnA7A%3D%3D))                                     |
| **USB4110-GF-A** | [Mouser](https://www.mouser.ro/ProductDetail/Atmel/ATMEGA328P](https://eu.mouser.com/ProductDetail/Hirose-Connector/FH34SRJ-24S-0.5SH50?qs=iyLo5FA4poC8fzWlavnA7A%3D%3D)](https://eu.mouser.com/ProductDetail/GCT/USB4110-GF-A?qs=KUoIvG%2F9IlYiZvIXQjyJeA%3D%3D))                                     |
| **BME680** | [Mouser](https://www.mouser.ro/ProductDetail/Atmel/ATMEGA328P](https://eu.mouser.com/ProductDetail/Hirose-Connector/FH34SRJ-24S-0.5SH50?qs=iyLo5FA4poC8fzWlavnA7A%3D%3D)](https://eu.mouser.com/ProductDetail/GCT/USB4110-GF-A?qs=KUoIvG%2F9IlYiZvIXQjyJeA%3D%3D)](https://eu.mouser.com/ProductDetail/Bosch-Sensortec/BME680?qs=v271MhAjFHjo0yA%2FC4OnDQ%3D%3D))                                     |
| **XC6220A331MR-G** | [Mouser](https://eu.mouser.com/ProductDetail/Torex-Semiconductor/XC6220A331MR-G?qs=AsjdqWjXhJ8ZSWznL1J0gg%3D%3D)                                     |
| **USBLC6-2SC6Y** | [Mouser](https://ro.mouser.com/ProductDetail/STMicroelectronics/USBLC6-2SC6Y?qs=gNDSiZmRJS%2FOgDexvXkdow%3D%3D&_gl=1*hyv6ey*_ga*MTY0NzAzMzgwNi4xNzQyMDMzODgx*_ga_15W4STQT4T*MTc0MzA3NjI1Ny40LjEuMTc0MzA3NjMxMC43LjAuMA)                                     |
| **BD5229G-TR** | [Mouser](https://ro.mouser.com/ProductDetail/ROHM-Semiconductor/BD5229G-TR?qs=4kLU8WoGk0vvnhrrYwdszw%3D%3D)                                     |
| **MAX17048G+T10** | [Mouser](https://ro.mouser.com/ProductDetail/Analog-Devices-Maxim-Integrated/MAX17048G%2bT10?qs=D7PJwyCwLAoGnnn8jEPRBQ%3D%3D)                                     |
| **W25Q512JVEIQ** | [Mouser](https://ro.mouser.com/ProductDetail/ROHM-Semiconductor/BD5229G-TR?qs=4kLU8WoGk0vvnhrrYwdszw%3D%3D](https://ro.mouser.com/ProductDetail/Winbond/W25Q512JVEIQ?qs=l7cgNqFNU1jw6svr3at6tA%3D%3D))  
| **Qwiic Right Angle** | [Mouser](https://ro.mouser.com/ProductDetail/Adafruit/4208?qs=PzGy0jfpSMtbScLbr0L5dw%3D%3D) |

Urmatoarea imagine prezinta diagrama bloc de interconectare a componentelor, inclusiv tensiunile de alimentare si protocoalele de comunicatie utilizate intre ele. 🔌📡

<div align="center">

![Diagrama](https://github.com/user-attachments/assets/d4f46cba-7525-401c-adea-f654d0fa5048)



</div>

Modelul 3D al PCB-ului poate fi observat si in imaginea urmatoare, ceea ce permite o analiza detaliata a componentei si a configuratiei acestuia. Acest model ofera o perspectiva clara asupra dimensiunilor, plasarii componentelor si a traseelor de pe placa, ajutand la identificarea posibilelor interferente sau probleme de proiectare.

<div align="center">
  
![1](https://github.com/user-attachments/assets/4fe50a38-774b-41ee-b400-88582fca79c5)


</div>

Putem vizualiza si traseele mai bine in modelul 3D, ceea ce faciliteaza o analiza mai detaliata a conexiunilor dintre componente. Acest lucru permite identificarea eventualelor probleme legate de lungimea sau latimea traseelor, precum si a eventualelor puncte de coliziune sau interferenta.

<div align="center">
  
![2](https://github.com/user-attachments/assets/a7708b39-650d-4b7a-ba79-70a36b546a23)

</div>

📐 **Integrarea modelului 3D al display-ului si al bateriei**

Pentru o reprezentare cat mai completa a ansamblului final, au fost incluse in proiect si modelele 3D ale display-ului si ale bateriei. Aceasta decizie a avut un rol esential in etapa de validare a designului, permitand o evaluare vizuala si functionala a intregului sistem, direct in mediul 3D.

Prin integrarea acestor componente, a fost posibila:
- ✅ **Verificarea compatibilitatii dimensionale** – Asigurarea ca fiecare componenta are un spatiu adecvat in interiorul carcasei, fara suprapuneri sau conflicte mecanice.
- 🧩 **Optimizarea pozitionarii componentelor** – Plasarea strategica a display-ului si bateriei pentru a facilita accesul, vizibilitatea, distributia greutatii si eficienta termica.
- 🧠 **Identificarea timpurie a potentialelor probleme de spatiu** – Vizualizarea in 3D permite observarea oricaror interferente sau nepotriviri intre PCB, baterie, display si carcasa proiectului.
- 🔧 **Eficientizarea procesului de prototipare** – Un model 3D complet si realist reduce riscul de erori in faza de fabricatie, scurtand ciclurile de testare si ajustare.

Aceasta abordare contribuie direct la cresterea fiabilitatii produsului final, asigurand ca toate componentele nu doar functioneaza impreuna, ci si se potrivesc perfect in structura fizica a dispozitivului.


</div>

<div align="center">
  
![3](https://github.com/user-attachments/assets/8e9ba450-5b0b-44fe-aefe-43617e1befa1)


</div>

<div align="center">
  
![4](https://github.com/user-attachments/assets/acd43543-4f9e-4bf6-883f-73b78202d5f7)


</div>

<div align="center">
  
![3D EBOOK](https://github.com/user-attachments/assets/14f51f09-6cef-438a-b1a6-9433d0ae2223)


</div>


### Cerinte de 'Good Practice' respectate de dispozitiv:

✅ Traseele de alimentare (VCC, VUSB, VBUS, 3V3 etc.) sunt rutate folosind width = 0.3mm, semnalele de date cu minimum width de 0.15mm.  
✅ Antena modulului ESP32 este amplasata spre exteriorul PCB-ului si PCB-ul trebuie sa fie decupat sub antena.  
✅ Verificare ERC si DRC.  
✅ Condensatoarele de decuplare (100nF) sunt amplasate cat mai aproape de pinii de alimentare ai diferitelor module si circuite integrate.  
✅ Suprafata PCB-ului de sub antena modulului ESP32 a fost decupata pentru a crea cat mai putine interferente cu semnalul radio.  
✅ Planuri de masa situate pe ambele nivele (TOP, BOTTOM).  
✅ Antena modulului ESP32 este amplasata spre exteriorul PCB-ului si PCB-ul este decupat sub antena.  
✅ S-a aplicat 'Via Stitching' intre cele doua planuri de masa, in special in preajma modulului ESP32, precum si in jurul componentelor principale.
✅ Placa are grosimea de 1mm, lucru ce permite introducerea in carcasa si pozitionarea corecta a mufelor.
✅ Vias-uri legate de masa au fost aplicate in toate zonele in care nu se facea 'Pour'.
✅ Valorile rezistentelor si condensatoarelor au fost sterse din 'Board' de pe layer-ul 'Silkscreen' pentru a permite o lizibilitate mai buna.
✅ Footprint-urile anumitor componente au fost schimbate prin modificarea marimilor unor pini, permitand traseele de putere sa se lege la ele, acestea fiind mai groase.
✅ Nu exista unghiuri drepte in cadrul rutarii pe placa.

### Erori acceptate pe dispozitiv:
✅Erorile 'Board Outline Clearance', conform cerintelor impuse.

### 🌐 Surse auxiliare utilizate pentru modele 3D

## Surse externe pentru modelarea 3D a ansamblului

Pentru a completa designul 3D al placii si a asigura o reprezentare cat mai fidela a ansamblului, au fost utilizate urmatoarele surse externe:

🔍 **Component Search Engine**  
Aceasta platforma a fost principalul instrument folosit pentru importarea modelelor 3D ale componentelor electronice standard. A oferit o integrare rapida si precisa cu software-ul de proiectare, facilitand plasarea corecta a componentelor in layout-ul 3D.

🟢 **Farnell**  
Modelele 3D ale butoanelor nu erau disponibile in Component Search Engine, asa ca s-a apelat la biblioteca pusa la dispozitie de Farnell. Aceasta ofera fisiere 3D compatibile si bine detaliate, utile pentru verificarea dimensiunilor fizice si a spatiului ocupat pe placa.

📦 **GrabCAD**  
Modelul 3D al Solder Jumper-ului (SJ) a fost descarcat de pe GrabCAD, o platforma colaborativa care pune la dispozitie o varietate larga de modele CAD. A fost ales un model potrivit, care a fost ulterior ajustat pentru a corespunde dimensiunilor reale folosite in proiect.


# Pinii ESP32 C6 folositi

Se poate vizualiza modul de conectare al componentelor in raport cu ESP32 C6. Se poate observa clar cum acesta poate fi atat 'Master', cat si 'Slave', lucru ce permite comunicatia SPI.

## 1. SD Card
- **CLK** → GPIO6  
- **CMD** → GPIO7  
- **DATA0** → GPIO8  
- **DATA1** → GPIO9  
- **DATA2** → GPIO10  
- **DATA3** → GPIO11  

## 2. Ecran E-Paper
Comunicare prin SPI și GPIO-uri adiționale:
- **MOSI** → GPIO4  
- **SCK** → GPIO5  
- **DC** → GPIO18  
- **CS** → GPIO17  
- **BUSY** → GPIO16  
- **RESET** → GPIO15  

## 3. Memorie NOR Flash 64MB (W25Q512JV)
Comunicare prin SPI:
- **MOSI** → GPIO4  
- **MISO** → GPIO3  
- **CLK** → GPIO5  
- **CS** → GPIO2  

## 4. Senzor de mediu BME688 (I2C)
- **SCL** → GPIO20  
- **SDA** → GPIO19  

## 5. RTC DS3231SN (I2C)
- **SCL** → GPIO20  
- **SDA** → GPIO19  

## 6. Qwiic / Stemma QT (I2C)
- **SCL** → GPIO20  
- **SDA** → GPIO19  

## 7. Indicator nivel baterie (MAX17048G+T10) (I2C)
- **SCL** → GPIO20  
- **SDA** → GPIO19  

## 8. Buton de Reset și Boot
- **Reset** → GPIO0  
- **Boot** → GPIO1  
