# AtlanticWhatsApp
PHP library for interract with WhatsApp api https://atlantic-group.id/

### Instalasi

Untuk dapat menggunakan fungsi ini, pertama-tama upload script AtlanticWhatsapp dan AtlanticHook ke web anda dan buat API KEY di [Atlantic Group](https://atlantic-group.id/) lalu copy API Key-nya dan paste-kan pada script AtlanticWhatsapp.
```
$WATL = new WhatsATL('API KEY ANDA');
```

### Push Message

Untuk mengirim push message bisa memanggil function seperti dibawah ini:
```
Kirim Pesan
$WATL->sendMessage('NO HP atau ID Grup','Pesan yang akan dikirim');

Kirim Files
$WATL->sendFiles('NO HP atau ID Grup','Jenis MIME','URL Files / Image / Video','Nama File / Caption');

Kirim Lokasi
$WATL->sendLocation('NO HP atau ID Grup','Latitude Map','Longitude Map','Nama Lokasi');
```

* Contoh MIME: application/pdf | image/jpg | image/png | video/mp4

## Authors
* **Dhifo Aksa Hermawan** - *BOT Developer* - [Dhifo](https://www.facebook.com/dhifoaksa)
* **Afdhalul Ichsan Yourdan** - *BOT Documentation* - [ShennBoku](https://facebook.com/ShennBoku)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
