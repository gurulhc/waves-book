# Billy

Лучший способ выучить язык - начать на нем писать. Заставить вас писать я не могу, поэтому предложу вам второй по крутизне вариант - читать как пишется код! Мы разберем несколько примеров контрактов, начнем с относительно простых, и закончим на достаточно сложных и разухабистых. Первым контрактом, который будем писать является контракт Oraculus, его идея очень проста - сделать децентрализованных оракулов.

## Описание проекта

Billy - децентрализованное приложение на базе бота для корпоративного мессенджера Slack. Вы можете найти подробную информацию о том, как работает Billy, на официальном сайте проекта - [https://iambilly.app](https://iambilly.app). Но давайте я коротко расскажу о том из каких частей он состоит и как именно в нем используется блокчейн.

Billy является проектом для мотивации сотрудников компании. В ходе работы у нас возникает много ситуаций, когда мы помогаем коллегам или они помогают нам. И далеко не всегда такая помощь входит в рабочие обязанности коллеги. Чтобы стимулировать помощь вы можете добавить Billy в Slack одной кнопкой на официальном сайте проекта. Billy генерирует уникальный адрес для каждого сотрудника компании и сохраняет их в базе данных. Каждый месяц бот начисляет на сгенерированные адреса 500 "Спасибо"-токенов, которые могут быть потрачены с помощью этого бота. Для этого сотрудники компании могут отправлять специальные команды боту (`10 спасибо @username`) или реагировать на сообщения с использованием специалных emoji.

<!-- //TODO: Add image with emoji reaction -->

Неиспользованный остаток из 500 спасибо-токенов за месяц сгорают в конце этого месяца. Заработанные спасибо-токены не сгорают и могут быть использованы для 3 целей:

- **Перевод другим пользователям в благодарность.** Полученные токены можно переводить в любое время своим коллегам.
- **Покупка товаров во внутреннем магазине.** Внутренний магазин позволяет сотрудникам компании (или уполномоченным лицам) предлагать товары и услуги в обмен на спасибо-токены.
- **Для участия в голосованиях и crowdfunding компаниях.** Каждый пользователь может указать цель, для которой собирает токены (например, проведение внутренного митапа) или руководство компании может инициировать голосования, где каждый токен будет считаться одним голосом, то есть более "полезный" и активный сотрудник может больше влиять на итоги голосования.

Видео-демонстрацию работы бота вы можете найти на официальном сайте проекта - [https://iambilly.app](https://iambilly.app)