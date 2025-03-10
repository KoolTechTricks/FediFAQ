---
title: Как перенести аккаунт Mastodon на другой сервер
weight: 12
original: https://fedi.tips/transferring-your-mastodon-account-to-another-server
---

## Как перенести аккаунт Mastodon на другой сервер

(Если ваш аккаунт новый и у вас ещё нет подписчиков, не тратьте время на эти инструкции! Просто зарегистрируйтесь на нужном сервере и удалите старый аккаунт. Эти шаги предназначены для тех, у кого уже есть подписчики, и они хотят их сохранить.)

Вы можете перенести свой аккаунт Mastodon на другой сервер. При переносе вы сохраните своих подписчиков, подписки, закладки, списки, блокировки, муты<!-- todo: подобрать термин --> и настройки видимости постов.

Инструкции ниже могут показаться немного сложными, так как объединяют несколько процедур, но вам нужно выполнить их только один раз за перенос.

Для переноса рекомендуется использовать сайты старого и нового серверов, так как они содержат все необходимые функции. (На данный момент перенос через приложения невозможен.)

## Зачем мне переносить аккаунт?

Причины для переноса могут быть разными. Наиболее распространённые из них:

- Переход на сервер с лучшей модерацией.
- Переход на более надёжный технически сервер.
- Переход в сообщество, чьи правила и атмосфера лучше соответствуют вашим потребностям.
- Желание использовать дополнительные функции другого сервера, такие как увеличенный лимит символов, форматирование текста или локальная видимость постов.
- Необходимость покинуть текущий сервер, если он закрывается. (Поэтому хорошо управляемые серверы обычно предупреждают о закрытии за несколько месяцев, чтобы пользователи успели перенести свои аккаунты.)

## Как выбрать новый сервер для перехода?

Выберите новый сервер с помощью [fedi.garden](https://fedi.garden) или [joinmastodon.org](https://joinmastodon.org/ru). Оба сайта курируются людьми и требуют от серверов соблюдения определённых стандартов технической надёжности и модерации контента.

Не используйте длинные автоматические некурируемые каталоги серверов, так как они часто включают ненадёжные серверы.

## Перед переносом запишите свои подписки на хэштеги и фильтры

Подписки на хэштеги и фильтры пока не переносятся автоматически. Если вы хотите их сохранить, запишите свои текущие подписки на хэштеги и фильтры перед переносом, а затем настройте их вручную на новом аккаунте.

Чтобы увидеть текущие подписки на хэштеги, перейдите в профиль, нажмите `︙`, затем **Подписанные хэштеги**. Чтобы увидеть текущие фильтры, перейдите в **Настройки > Фильтры**.

## Пошаговая инструкция по переносу аккаунта

Это подробное руководство по переносу вашего аккаунта с одного сервера Mastodon на другой. Оно может показаться длинным, так как объединяет несколько разных процессов, но охватывает всё сразу.

Если вы хотите перенести только своих подписчиков (людей, которые следят за вами), и вам неважно остальное, пропустите шаги 1–3 и сразу переходите к шагу 4.

1. **Создайте новый аккаунт на сервере, куда хотите перейти, но НЕ УДАЛЯЙТЕ старый аккаунт.**
2. **На СТАРОМ аккаунте зайдите на сайт старого сервера и войдите в систему.** Нажмите **Настройки > Импорт и экспорт > Экспорт данных** и скачайте все файлы CSV, нажимая на соответствующие значки. **НЕ НАЖИМАЙТЕ кнопку запроса архива!** Архив не имеет отношения к переносу. (Вы можете запросить архив отдельно, чтобы сохранить личную копию данных аккаунта. Это особенно важно, если ваш старый сервер закрывается.) Также учтите, что CSV-файла для подписчиков нет, так как они обрабатываются отдельно (см. шаги 4–6 ниже).
3. **На НОВОМ аккаунте зайдите на сайт нового сервера и войдите в систему.** Нажмите **Настройки > Импорт и экспорт > Импорт** и загрузите CSV-файлы по одному (те, которые вы скачали на предыдущем шаге). При загрузке выбирайте тип файла из выпадающего меню, например, выберите «Закладки», если загружаете файл закладок.
4. **Войдите в НОВЫЙ аккаунт на сайте нового сервера.** Перейдите в **Настройки > Аккаунт > Переезд с другого аккаунта** (внизу экрана), нажмите **Создать псевдоним аккаунта** и следуйте инструкциям. (Когда вас попросят ввести адрес старого аккаунта, убедитесь, что он начинается с `@` и содержит `@` в середине.)
5. **После завершения предыдущего шага подождите хотя бы пять минут.** Процесс может занять некоторое время, и важно дождаться его завершения, прежде чем продолжить. Пока ждёте, вы можете (по желанию) изменить имя СТАРОГО аккаунта, добавив пометку «(ИМЯ ВАШЕГО СТАРОГО АККАУНТА) переехал» и указать в профиле адрес нового аккаунта. Технически это не обязательно, но поможет всем заметить ваш переезд.
6. **После ожидания войдите в СТАРЫЙ аккаунт на сайте старого сервера.** Перейдите в **Настройки > Аккаунт > Переезд на другой аккаунт** (внизу экрана), нажмите **Настроить здесь** и следуйте инструкциям. Это начнёт перенос ваших подписчиков на новый аккаунт. Подписчики будут переходить волнами, в зависимости от загруженности их серверов. Некоторые подписчики автоматически подпишутся на ваш новый аккаунт сразу, а другие могут сделать это через часы (или даже дни!).
7. **Даже после переноса НЕ УДАЛЯЙТЕ старый аккаунт.** Лучше оставить его нетронутым, так как он будет перенаправлять людей на ваш новый аккаунт и сохранит старые посты. Старые посты будут перенаправлять людей на новый аккаунт, пока вы не удалите старый.

Убедитесь, что выполняете все шаги в правильном порядке. Если вы пропустите что-то или сделаете что-то не так, перенос может не сработать или быть неполным.

После выполнения всех шагов ваш старый аккаунт будет перенаправлять на новый, а ваши подписчики, подписки, закладки, муты<!-- todo: подобрать термин --> и блокировки перенесутся автоматически. Некоторые элементы могут задержаться — не волнуйтесь, если это произойдёт.

## Это кажется слишком сложным. Могу ли я пропустить некоторые шаги?

Если вы хотите перенести только подписчиков (людей, которые следят за вами), и вам неважно остальное, пропустите шаги 1–3 и сразу переходите к шагу 4.

## Что происходит со старым профилем после переезда?

После подтверждения переезда на шаге 6 ваш старый профиль автоматически станет чёрно-белым, люди не смогут подписаться на него, и сверху появится уведомление о том, что вы переехали на новый адрес, с ссылкой на ваш новый профиль.

Однако не все приложения Федиверса показывают это автоматическое уведомление, поэтому рекомендуется также добавить вручную заметку с адресом нового аккаунта. Подробнее см. шаг 5.

## Сколько времени займёт перенос всех подписчиков?

Большинство подписчиков должны перейти за несколько часов, но некоторые могут задержаться на дни или даже недели. Вы ничего не можете сделать, чтобы ускорить этот процесс, так как он зависит от загруженности их серверов и очереди задач. Более загруженные серверы могут обрабатывать запросы дольше.

Однако подписчики могут обойти очередь, вручную подписавшись на ваш новый аккаунт. Это не вызовет проблем. Вы можете поощрить их сделать это, если хотите.

## Я выполнил перенос, но на старом аккаунте всё ещё есть подписчики. Как их перенести?

Если через 30 дней на старом аккаунте всё ещё остались подписчики, выполните следующую процедуру, чтобы перенести их:

1. Войдите на сайт или в веб-приложение старого сервера. Это должно привести вас на страницу настроек старого аккаунта (если нет, попробуйте выйти и снова войти, делая это на компьютере или планшете в горизонтальном режиме, а не на телефоне).
2. Прокрутите вниз до раздела **Переезд на другой аккаунт** и нажмите **Настроить здесь**.
3. Нажмите **Отменить перенаправление** в верхней части экрана.
4. Прокрутите вниз до раздела **Переезд на другой аккаунт**, введите адрес НОВОГО аккаунта и пароль СТАРОГО аккаунта.
5. Нажмите **Перенести подписчиков**.

Оставшиеся подписчики начнут переходить на новый аккаунт. Как и в первый раз, этот процесс может занять несколько дней. Если через 30 дней на старом аккаунте всё ещё остались подписчики, повторите процедуру.

30-дневный «период охлаждения» даёт время на обработку первого переноса, так как некоторые серверы могут обрабатывать запросы дни или недели.

Обратите внимание, что небольшая часть подписчиков может находиться на неисправных серверах, которые не обрабатывают запросы. Таких подписчиков невозможно перенести, но такие случаи редки.

## Почему подписчики не переходят все сразу? И почему некоторые не переходят даже после нескольких попыток?

Есть много причин, почему подписчик может не перейти сразу:

- Они уже следят за вашим новым аккаунтом, и процесс переноса не удалил их подписку со старого.
- Их сервер временно недоступен; перенос должен завершиться автоматически позже.
- Их сервер перегружен и временно не обрабатывает автоматические запросы.
- Их сервер закрылся навсегда, и они больше не могут быть перенесены. Вы можете проверить статус сервера, посетив его страницу.
- Настройки их сервера некорректны, что мешает процессу.
- Их аккаунт удалён, но по какой-то причине всё ещё виден с вашего сервера.
- Их аккаунт находится на сервере с программным обеспечением, несовместимым с автоматическим переносом. Вам нужно попросить их вручную подписаться на ваш новый аккаунт.
- Ваш новый сервер заблокировал сервер подписчика, что препятствует переносу.

Попробуйте повторить процесс через 30 дней, так как некоторые подписчики могли столкнуться с временными проблемами (например, временный сбой на их сервере). Не беспокойтесь, если некоторые подписчики так и останутся на старом аккаунте: скорее всего, они уже следят за вашим новым аккаунтом или их аккаунты больше не существуют.

## Что происходит со старыми постами? Они тоже переносятся?

Старые посты не переносятся. Они останутся на старом сервере, если вы не удалите старый аккаунт. Кроме того, при клике на имя пользователя в старых постах люди будут перенаправлены на ваш новый аккаунт.

Если вы всё же решите удалить старый аккаунт, все старые посты исчезнут, и людям будет сложнее найти ваш новый аккаунт.

Если вы хотите полностью контролировать свой контент, вы можете запустить собственный сервер на управляемом хостинге. Управляемый хостинг означает, что компания берёт на себя всю техническую работу, так что вам не нужно быть техническим специалистом.

## Должен ли новый аккаунт быть пустым?

Нет, он не обязательно должен быть пустым. Вы можете перенести свой аккаунт на любой другой, включая аккаунты, у которых уже есть подписчики.

## Могу ли я перенести аккаунт, если один сервер блокирует другой?

Да, но это потребует терпения.

Если один сервер блокирует другой, это предотвращает прямой перенос аккаунтов между ними. Однако, если вы найдёте нейтральный третий сервер, который не заблокирован ни старым, ни новым сервером, вы можете временно перенести аккаунт на этот третий сервер, а затем позже перенести его на новый сервер.

Учтите, что вам придётся подождать, пока подписчики перейдут на нейтральный сервер, прежде чем продолжить. Представьте это как длительный перелёт с пересадкой.

## Я получаю ошибку «Что-то не так!» при попытке ввести адрес старого аккаунта на новом сервере.

Если вы уверены, что ввели адрес правильно, ошибка может быть вызвана тем, что один сервер блокирует другой. См. совет выше, чтобы обойти эту проблему.

## Почему нет CSV-файла для подписчиков?

CSV-файлы легко копировать и загружать на разные аккаунты. Это делает их непригодными для переноса подписчиков, так как их можно было бы злоупотреблять для клонирования подписчиков на неограниченное количество аккаунтов.

## Могу ли я вернуться к старому аккаунту, если передумаю?

Да. Пока вы не удалили старый аккаунт и пока сервер, на котором он находится, работает, вы всегда можете вернуться и отменить перенаправление.

Чтобы вернуться к старому аккаунту:

1. Войдите на сайт или в веб-приложение старого сервера с данными старого аккаунта.
2. Вас должно перенаправить на страницу настроек с сообщением о том, что аккаунт неактивен.
3. Нажмите **Отменить перенаправление** в сообщении сверху.

Подписчики, которых вы перенесли на новый аккаунт, останутся там, даже если вы отмените перенаправление. Однако вы можете перенести их обратно, используя обычный процесс переноса в обратном направлении.

## Могу ли я снова вернуться к новому аккаунту, если передумаю?

Да, вы можете перемещаться между аккаунтами и переносить подписчиков туда-обратно.

Однако между такими переносами будет 30-дневный период охлаждения. Если вы будете делать это часто, некоторые люди могут запутаться, и вы можете потерять несколько подписчиков, если их серверы неправильно обрабатывают переносы.

## Я попробовал загрузить данные, но система не распознаёт их! Она говорит «Неверный CSV-файл». Что происходит?

Похоже, вы пытаетесь загрузить архив аккаунта, который не используется для переноса. Разметка страницы экспорта данных может вводить в заблуждение: переносы включают только отдельные CSV-ссылки. Кнопка запроса архива не используется для переноса. (Если вы хотите узнать больше об архивах, см. [руководство по архивам постов Mastodon](https://example.com).)<!-- todo: добавить ссылку -->

![Скриншот страницы экспорта данных аккаунта Mastodon с примечаниями, указывающими, что CSV-ссылки используются для переноса, а запрос архива — нет.](https://fedi.tips/wp-content/uploads/2024/03/ExportPage-1536x804.png)<!-- todo: заменить на локализованное изображение -->