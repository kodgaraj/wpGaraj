# wpGaraj

## Projeyi Ayağa Kaldırmak

Sunucuya [RabbitMQ Server](https://www.rabbitmq.com/download.html) kurulumu yapılacak. Bu repoyu klonladıktan sonra `npm install` yapılıp;

- `rabbitmq-server` diyerek rabbitmq sunucusunu başlatıyoruz (Windows'ta kurulum yaptıktan sonra otomatik başlar. Eğer başlamadıysa "Başlat" menüsünden "RabbitMQ Service - start" yazıp çalıştırabilirsiniz).
- `npm start` diyerek sunucuya bağlanıp projeyi çalıştırıyoruz.
- `npm run consumer` diyerek dilediğimiz kadar consumer oluşturarak istekler karşılanır.
