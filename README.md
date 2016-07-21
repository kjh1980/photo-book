Многопользовательский сервис “Фотокнига”
========================================

Структура
------------

      middleware           связующее ПО
      public/              статические ресурсы
        media/             загружаемые пользователями ресурсы
      routes/              маршрутизация
      template/            файлы шаблонизатора(jade)
      config.json          конфигурация сервера
      mongoose.js          файл для подключения mongoose к БД
      models.js            файл с моделями mongoose
      index.js             основной файл приложения