# Вы перешли в раздел с домашним заданием.

## Текущее домашнее задание:

**Срок сдачи: 26.05.2023 (пятница).** До этого времени необходимо создать Pull Request.

Создайте веб-страницу с четрьмя карточками товара.  
Внутри карточки товара разместите:
- изображение/иконку товара;
- наименование товара;
- дополнительный контент (по желанию).

Расположите карточки товара следующим образом:
- если вы из группы `9`: в центральной части экрана по центру с расстоянием между карточками 10 пикселей;
- если вы из группы `10`: в нижней части экрана по центру с расстоянием между карточками 15 пикселей;
- если вы из группы `91`: в центральной части экрана с одинаковым расстоянием между карточками и "прилипанием" к левой и правой границам вьюпорта;
- если вы из группы `101`: в нижней части экрана с одинаковым расстоянием между карточками и левой и правой границей вьюпорта.

Ниже расположен пример ожидаемого результата вашей работы.

![Пример результата](https://github.com/ekertn7/graph-library-interface/raw/master/EXAMPLE.png)

## Как тут работать:
1. Перейдите по [ссылке](https://github.com/ekertn7/teaching-web-layout-2023-spr/) и нажмите на кнопку "fork".  
![Шаг 1](https://github.com/ekertn7/graph-library-interface/raw/master/STEP1.jpg)
2. Если вы уже клонировали репозиторий, появится соответствующее сообщение, перейдите к склонированному репозиторию и пропустите пункт 3.  
![Шаг 2](https://github.com/ekertn7/graph-library-interface/raw/master/STEP2.jpg)
3. Если не клонировали репозиторий - сделайте это, **обязательно уберите галочку с пункта "copy the master branch only"**.  
![Шаг 3](https://github.com/ekertn7/graph-library-interface/raw/master/STEP3.jpg)
4. Перейдите в ваш форкнутый репозиторий и синхронизируйте изменения.  
![Шаг 4](https://github.com/ekertn7/graph-library-interface/raw/master/STEP4.jpg)
5. Откройте терминал (для Windows: пуск -> напечатайте "cmd" -> откройте приложение "Командная строка", для Linux/MacOS: откройте приложение "Terminal").
6. Переместитесь в директорию, в которой будете работать `cd <директория>` (путь можно скопировать из окна проводника), например: `cd "Documents/Projects"`.
7. Склонируйте форкнутый репозиторий на свой компьютер `git clone <ссылка на репозиторий>` (ссылка доступна по клику на зеленую кнопку "code", **обязательно берите ссылку из репозитория в СВОЕМ аккаунте, НЕ [отсюда](https://github.com/ekertn7/teaching-web-layout-2023-spr)**).  
![Шаг 5](https://github.com/ekertn7/graph-library-interface/raw/master/STEP5.jpg)
8. Переместитесь в директорию с клонированным репозиторием `cd <название репозитория>`, например: `cd "teaching-web-layout-2023-spr"`.
9. Переместитесь на ветку с актуальным домашним заданием `git checkout homework/<номер задания>`.
10. **НЕ удаляйте, НЕ перемещайте и НЕ переименовывайте существующие файлы**.
11. Создайте папку со своим ФИО по формату "ivanov-i-i" (ivanov = фамилия, i = первая буква имени, i = первая буква отчества).
12. Выполните в этой папке домашнее задание.
13. Добавьте изменения в индекс `git add <файлы>` (для добавления конкретных файлов) или `git add .` (для добавления всех файлов).
14. Сделайте коммит `git commit -m "Выполнение домашнего задания №<номер задания>."` (**соблюдайте правила создания комментариев**).
15. Загрузите изменения в удаленный репозиторий `git push -u origin homework/<номер задания>`.
16. Создайте Pull Request (в меню Contribute) с объединением с веткой с таким же названием [главного репозитория](https://github.com/ekertn7/teaching-web-layout-2023-spr) (название Pull Request должно быть "<Фамилия>. <Группа>. Домашнее задание №<номер задания>.", например: "Иванов. 101. Домашнее задание №2.", **соблюдайте правила создания комментариев**).
17. Если необходимо, добавьте комментарий в поле ниже названия Pull Request'а, например: "Не успел прислать задание вовремя так как находился на больничном. Есть подтверждение моего отсутствия.".
18. Проверьте, что Pull Request создан в [главном репозитории](https://github.com/ekertn7/teaching-web-layout-2023-spr).
19. Ожидайте подтверждения/комментариев.

## Если после направления домашнего задания приходит комментарий от преподавателя, где он пишет о необходимости внести правки:
1. Внесите правки.
2. Добавьте изменения в индекс `git add <файлы>` (для добавления конкретных файлов) или `git add .` (для добавления всех файлов).
3. Сделайте коммит `git commit -m "Исправление/добавление/удаление/корректировка ... в домашнем задании №<номер задания>."`, например: `git commit -m "Исправление кодировки файла в домашнем задании №2."` (**соблюдайте правила создания комментариев**).
4. Загрузите изменения в удаленный репозиторий `git push -u origin homework/<номер задания>`.
5. Проверьте обновление текущего Pull Request'а в [главном репозитории](https://github.com/ekertn7/teaching-web-layout-2023-spr).
6. Ожидайте подтверждения/комментариев.

## Дополнительно:

Для ознакомления с лекциями, перейдите на ветку `lectures`.
