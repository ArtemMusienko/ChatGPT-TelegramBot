## ChatGPT + TelegramBot
API-ключи Telegram-бота и от сервиса **VSEGPT** для доступа к **ChatGPT** я поместил в "*Секреты*" **Google Colab**, которые в дальнейшем интегрировал в код.

В коде обучение выполнено по начальным статьям англоязычной *Википедии* в категории "*Academy Awards*". 

Реализован большой ряд функций, направленных на обработку заголовков, секций, страниц и текста.

Была создана собственная база знаний, в которой хранятся текста и их эмбендинги. В дальнейшем она сохраняется и используется в конечном продукте — в боте. 

Telegram-бот умеет отвечать на вопросы, связанные с базой знаний, а также выдавать подробную информацию при написании **/help** и **/start**. 