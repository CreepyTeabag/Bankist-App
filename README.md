# Bankist-App
 Учебный проект Bankist - небольшое банковское приложение.
Проект написан на JavaScript, отработанные темы: массивы, числа, даты, таймеры.
## Функционал:
- Вход в аккаунт (***user: js, PIN: 1111*** либо ***user: jd, PIN: 222***`)
- Отображение всех банковских операций с возможностью сортировки по убыванию
- У каждой операции отображается дата
- Перевод денег на другие аккаунты (***js*** либо ***jd***)
- Запрос кредита (разрешён, если в данном аккаунте были зачисления, составляющие как минимум 10% от запрашиваемой суммы)
- Все новые операции добавляются в общий список операций, обновляется баланс счёта и пересчитывается сумма всех зачислений и снятий
- Высчитывается процент, который будет начислен на зачисления более одного евро (прописан в объекте каждого пользователя в **interestRate**)
- Формат текущей даты зависит от страны пользователя (прописана в объекте каждого пользователя в **locale**)
- У пользователей может быть разная валюта (прописана в объекте каждого пользователя в **currency**)
- При отсутствии действий (перевод денег / запрос кредита) в течение 5 минут автоматически происходит выход из аккаунта
- Удаление аккаунта

  Проект писался при прохождении курса The Complete JavaScript Course 2023: From Zero to Expert!