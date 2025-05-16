Nama : Arief Ridzki Darmawan

NPM : 2306210115

Kelas : A

---
## 1.
### > Sebanyak apa data yang akan dikirimkan program publisher kepada message broker dalam satu run?
Karena ada 5 message, maka data yang akan dikirimkan sebanyak data pada 5 message itu digabung.

### > Url ```amqp://guest:guest@localhost:5672``` sama seperti pada program subscriber, apa maknanya?
Url tersebut adalan url broker AMQP yang menunjuk pada RabbitMQ. Publisher akan mengirimkan message ke broker menggunakan url ini, dan subscriber akan mendapatkan message dari broker yang sama pada url ini juga. Jadi, url yang sama ini maksudnya subscriber dan publisher terhubung di instance RabbitMQ yang sama.

![Running RabbitMQ as message broker](image.png)