# rfid-rc522
Contoh penggunaan rfid menggunakan reader rc522 pada esp8266 amica

Untuk konfigurasi pengkabelan dapat dilihat pada gambar di bawah ini

![](rfid-mfrc522.png)

File fritzing dapat diunduh di [MFRC522.fzz](MFRC522.fzz)

## Tabel skematik
Untuk lebih jelaskan dapat dilihat pada tabel di bawah ini
| ESP8266 Amica | RFID\-RC522                        |
|---------------|------------------------------------|
| D2            | SDA                                |
| D5            | SCK                                |
| D7            | MOSI                               |
| D6            | MISO                               |
|               | IRQ                                |
| GND           | GND                                |
| D3            | RST                                |
| 3V3           | 3\.3V                              |
