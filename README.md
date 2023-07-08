# Project-4 Анализ тарифов компании «Мегалайн»

**Описание проекта**

Этот проект посвящен анализу тарифов компании «Мегалайн» — федерального оператора сотовой связи. Цель проекта - на основе данных о 500 пользователях компании выяснить, какой из двух тарифных планов: «Смарт» и «Ультра» приносит больше денег.

**Данные**

Данные для анализа хранятся в нескольких файлах:

users.csv - информация о пользователях

calls.csv - информация о звонках

messages.csv - информация о сообщениях

internet.csv - информация об интернет-сессиях

tariffs.csv - информация о тарифах


**Описание колонок в файле users.csv:**

user_id — уникальный идентификатор пользователя

first_name — имя пользователя

last_name — фамилия пользователя

age — возраст пользователя (годы)

reg_date — дата подключения тарифа (день, месяц, год)

churn_date — дата прекращения пользования тарифом (если значение пропущено, значит, тариф ещё действовал на момент выгрузки данных)

city — город проживания пользователя

tarif — название тарифного плана


**Описание колонок в файле calls.csv:**

id — уникальный номер звонка

call_date — дата звонка

duration — длительность звонка в минутах

user_id — идентификатор пользователя, сделавшего звонок


**Описание колонок в файле messages.csv:**

id — уникальный номер сообщения

message_date — дата сообщения

user_id — идентификатор пользователя, отправившего сообщение


**Описание колонок в файле internet.csv:**

id — уникальный номер сессии

mb_used — объём потраченного за сессию интернет-трафика (в мегабайтах)

session_date — дата интернет-сессии

user_id — идентификатор пользователя


**Описание колонок в файле tariffs.csv:**

tariff_name — название тарифа

rub_monthly_fee — ежемесячная абонентская плата в рублях

minutes_included — количество минут разговора в месяц, включённых в абонентскую плату

messages_included — количество сообщений в месяц, включённых в абонентскую плату

mb_per_month_included — объём интернет-трафика, включённого в абонентскую плату (в мегабайтах)

rub_per_minute — стоимость минуты разговора сверх тарифного пакета (например, если в тарифе 100 минут разговора в месяц, то со 101 минуты будет взиматься плата)

rub_per_message — стоимость отправки сообщения сверх тарифного пакета

rub_per_gb — стоимость дополнительного гигабайта интернет-трафика сверх тарифного пакета (1 гигабайт = 1024 мегабайта)
