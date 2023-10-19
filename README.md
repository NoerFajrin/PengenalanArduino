# PengenalanArduino
![image](https://github.com/NoerFajrin/PengenalanArduino/assets/71316603/882584aa-fee1-4fec-a417-4ff98e430279)


Mikrokontroler ATMega328P: Arduino Uno menggunakan mikrokontroler ATMega328P, yang memiliki sejumlah pin input/output digital dan analog yang dapat Anda gunakan untuk menghubungkan sensor, aktuator, dan perangkat lainnya.

Input/Output: Arduino Uno memiliki 14 pin digital input/output, di mana 6 di antaranya dapat digunakan sebagai output PWM (Modulasi Lebar Pulsa), serta 6 pin input analog. Selain itu, ada pin untuk komunikasi serial dan berbagai pin untuk keperluan lainnya.

USB Interface: Arduino Uno dilengkapi dengan port USB yang memungkinkan Anda untuk memprogramnya dengan mudah dan mengirim data ke komputer. Ini juga memungkinkan Anda untuk menggabungkannya dengan komputer sebagai perangkat input/output.

Penyuplai Daya: Arduino Uno dapat diberi daya melalui kabel USB atau melalui adaptor daya eksternal. Ini memberikan fleksibilitas dalam pemilihan sumber daya.

Pemrograman: Anda dapat memprogram Arduino Uno menggunakan bahasa pemrograman Arduino yang berbasis C/C++. Arduino IDE (Integrated Development Environment) adalah perangkat lunak yang umumnya digunakan untuk mengembangkan dan mengunggah kode ke papan Arduino.

Komunitas dan Sumber Daya: Arduino Uno memiliki komunitas yang besar dan beragam, serta banyak sumber daya belajar dan proyek tersedia secara online. Ini membuatnya menjadi pilihan yang bagus untuk pemula yang ingin mempelajari pemrograman mikrokontroler.

# Simulasi Online
1. Buka : https://wokwi.com/arduino
2. Scroll sampai start from Scratch
   ![image](https://github.com/NoerFajrin/PengenalanArduino/assets/71316603/b5b45b59-75d3-435d-afd2-fd5a82f78df4)
3. Pilih Arduino uno
4. Cetak Teks
   ![image](https://github.com/NoerFajrin/PengenalanArduino/assets/71316603/ae6693b7-b5d5-4db2-a90e-dd307a1ceefe)
   code :
<br>void setup() {
 <br> // Initialize serial communication at a baud rate of 9600
 <br> Serial.begin(9600);
 <br>}
<br>void loop() {
 <br> Serial.println("STEI-ITB");
 <br> Serial.println("Jatinangor 2023");
<br> Serial.print("Provinsi : ");
<br> Serial.println("Jawa Barat");
 <br> delay(1000); 
<br>}
6. output
![image](https://github.com/NoerFajrin/PengenalanArduino/assets/71316603/e879fae7-e665-402d-bb07-b0f5e03a09b8)
<br> https://wokwi.com/projects/379058588915307521

8. Ganti Tulisan dengan Nama dan NIM di baris yang berbeda
<br>
# Digital Read
https://wokwi.com/projects/379059728820253697



