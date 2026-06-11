# Comunication Protocol

## UTS Project

MQTT Testing

## Pengertian MQTT

     Pada project UTS mata kuliah Communication Protocol (ComP2) saya memilih project MQTT Event Case. Sebelum masuk ke pembahasan case yang dipilih, saya akan menjelaskan secara singkat apa itu MQTT dari apa yang telah saya pelajari. 
     MQTT (Message Queuing Telemetry Transport) adalah standar pesan protolol yang banyak digunakan pada IoT dan machine-to-machine communication dengan arsitektur publisher mengirim pesan ke MQTT broker, lalu MQTT broker menerima pesan lalu mengirimkan ke subscribe sesuai topic yang dipilih, dan setelah itu subscriber menerima pesan. 
     Yang unik disini adalah apabila pesan tidak sesuai topic yang dituju subscriber tidak akan menerima pesan tersebut, karena subscriber akan memfilter pesan berdasarkan topicnya. 

## Case

MQTT Event Case

## Halaman Utama

Website NexaLab memiliki 3 halaman utama:

1. Beranda
2. Layanan
3. Kontak

## Struktur Folder

UTS_CommProtocol_Dani-Riyanto_25120500028/
│
├── README.md
│
├── mqtt/
│   ├── mqtt-commands.md
│   ├── broker-config.md
│   └── topic-list.md
│
├── evidence/
│   ├── connect-broker.png
│   ├── subscribe-topic.png
│   ├── publish-message-01.png
│   └── publish-message-02.png
│   └── publish-message-03.png
│   └── publish-message-04.png
│
├── analysis/
│   ├── mqtt-handshake-analysis.md
│   └── publish-subscribe-analysis.md
│
└── report/
    ├── laporan-uts.pdf
    └── slides-presentasi.pptx

