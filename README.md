# Subscriber

## What is amqp?

AMQP (Advanced Message Queuing Protocol) adalah protokol komunikasi yang digunakan untuk bertukar pesan antar program di mana pengirim dan penerima pesan tidak perlu terhubung langsung. Mirip seperti HTTP yang dipakai browser untuk request ke server, AMQP ini khusus dipakai untuk komunikasi melalui message broker seperti RabbitMQ. Protokol ini yang mengatur bagaimana cara koneksi, format datanya, sampai konfirmasi bahwa pesan sudah diterima.

## What does `guest:guest@localhost:5672` mean?

- `guest` (pertama): username untuk login ke RabbitMQ
- `guest` (kedua): password untuk login ke RabbitMQ
- `localhost`: alamat server RabbitMQ nya, dalam hal ini di komputer kita sendiri (local)
- `5672`: port yang dipakai RabbitMQ untuk menerima koneksi

Intinya, itu adalah connection string untuk connect/login ke RabbitMQ. Format: username:password@host:port