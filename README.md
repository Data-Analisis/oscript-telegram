# oscript-telegram
Библиотека для работы с API Telegram на OneScript

#### Пример Telegram

    Телеграм = Новый Телеграм();
    Телеграм.Токен = "token"; // from BotFather
    Телеграм.ОтправитьСообщение("rocketchat", "chanel", "Всем привет", Новый Структура("ТипСообщения", "Внимание"));
    Телеграм.ОтправитьСообщение("rocketchat", "@user", "@User, привет!", Новый Структура("ТипСообщения", ":pensive:"));
