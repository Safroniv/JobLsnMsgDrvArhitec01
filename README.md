# JobLsnMsgDrvArhitec01

Практическое задание
● Создать возможность снять бронь синхронно и асинхронно, используя для этого
номер забронированного стола;
● Выделить логику для отправки уведомления в отдельный класс, он будет
отвечать за все вопросы связанные с коммуникациями с клиентами, добавить
задержку (они будет имитировать создание сообщения) и сделать вызов
уведомления асинхронным;
● Добавить автоматическое “снятие брони”. Например, раз в 20 секунд при
наличии забронированных мест - бронь должна слетать. Асинхронно, независимо
от ввода-вывода. Подсказка: можно использовать таймер.
● (*) Добавить синхронизацию бронирований для множественных асинхронных и
синхронных вызовов, это значит, что бронируя столики не дожидаясь
предыдущих ответов мы должны получать последовательный результат.
● (**) Добавить ограничение на количество мест за столом относительно
количества гостей, например, если придет 5 человек, то сесть можно только за
стол где больше 5 мест. Столы сдвигать можно. Должна быть синхронизация
между разными одновременными бронированиями.