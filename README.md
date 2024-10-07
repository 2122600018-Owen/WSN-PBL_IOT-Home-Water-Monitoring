# WSN-PBL_IOT-Home-Water-Monitoring
Sistem Monitoring Penggunaan Air Berbasis IoT ini dirancang untuk membantu rumah tangga dalam memantau penggunaan dan ketersediaan air secara real-time. Menggunakan ESP32 sebagai kontroler utama, sistem ini memanfaatkan sensor aliran air (Flow Sensor) untuk melacak jumlah air yang digunakan serta sensor ultrasonik untuk mengukur level air di dalam tangki penyimpanan. Data yang diperoleh akan dikirimkan ke platform cloud Adafruit IO melalui protokol MQTT, di mana pengguna dapat mengaksesnya melalui aplikasi ponsel atau website.

Dengan sistem ini, pengguna dapat mengelola air secara lebih efisien, mencegah kebocoran, dan menerima notifikasi dini ketika air di tangki hampir habis. Sistem juga dapat diperluas untuk memantau beberapa titik pengukuran berbeda di rumah, seperti dapur atau kamar mandi, dengan menambahkan modul tambahan.

# Diagram Arsitektur
![diagram arsitektur](https://github.com/user-attachments/assets/1f39079f-6660-4a60-ae13-af3b88021fef)
