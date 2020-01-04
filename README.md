STEP 1 Download dan Install Python
  •	Pergi ke https://www.python.org/downloads/
  •	Pilih versi python 2.7 / 3.5 (Workshop ini menggunakan 2.7)
STEP 2 Download dan install ESPTOOL
  •	Buka powershell pada windows
  •	Selanjutnya ketik “pip install esptool
STEP 3 Download dan install firmware esp8266
  •	Pergi ke http://micropython.org/download
  •	Download firmware ESP8266 versi terbaru
  •	Buka powershell pada windows
  •	Selanjutnya ketik “esptool.py --port COM (yang terdeteksi) --baud 115200 write_flash --flash_size=detect 0 esp(versi yang didownload).bin”
STEP 4 Download dan install Putty
  •	Pergi ke https://www.putty.org/
  •	Download putty 64 bit
  •	Buka aplikasi putty
  •	Pilih menu serial
  •	Isikan Port dan Baudrate sesuai  pada proses instalasi
  •	Klik open

