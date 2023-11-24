# Practic_4
Practic_4

# Практическое задание №4 "Контроль целотности"
## Подготавливаем и разворачиваем виртуальную машину Astra Linux
Для данной практической работы была использлвана Astra Linux с версией системы "Смоленск" с максмальным уровнем защиты <br /><br />
![image](https://github.com/StepaBelyaev/Practic_4/assets/70752929/de6091e7-60da-4ab2-8aa7-b1baa1011f86)
![image](https://github.com/StepaBelyaev/Practic_4/assets/70752929/c884c395-5be4-4ae1-81ff-57eb9b2b3a53)

## Настройка и проверка мандатного контроля целостности
Для измнения конфигурации мандатного контроля целостности (МКЦ) в ОС Astra Linux воспользуемся встроенной утилитой Управление политикой безопасности
![image](https://github.com/StepaBelyaev/Practic_4/assets/70752929/61ddd861-35ed-4bba-a499-2d1b3bd83bb6)
В меню Режим эксперта можно непосредственно назначить уровни целостности для директорий. 
![image](https://github.com/StepaBelyaev/Practic_4/assets/70752929/5134a9a2-3bdf-4df6-a3c5-fff70039683f)
Проверим работу механизма МКЦ:
![image](https://github.com/StepaBelyaev/Practic_4/assets/70752929/206c8478-ca09-4848-a8ee-f854c615e7ec)

## Режим замкнутой программной среды (ЗПС)
Запустим режим замкнутой программной среды и проверим его работу
![image](https://github.com/StepaBelyaev/Practic_4/assets/70752929/cfb0f29c-235d-4d22-98c2-3078f2d71d1b)
![image](https://github.com/StepaBelyaev/Practic_4/assets/70752929/f30064f7-4f52-485c-8d7d-2ab6131cb5cc)

# Работа с утилитами контроля целостности и регламентного контроля целостности
## Использование gostsum
Утилита gostsum вычисляет хэш-сумму файлов в соответствии с ГОСТ Р 34.11-2012. Пример использования с .deb пакетом:
![image](https://github.com/StepaBelyaev/Practic_4/assets/70752929/173c0c79-6716-4ada-8448-5e549171db66)

## Использование afick
afick - утилита, предназначенная для контроля целостности файловой системы ОС. Для корректной работы утилиты сначала создается БД утилиты:
![image](https://github.com/StepaBelyaev/Practic_4/assets/70752929/2ddd7102-8878-4f12-9b1b-52c1002751f7)
Изменим часть системных файлов для получения ответа от утилиты:
![image](https://github.com/StepaBelyaev/Practic_4/assets/70752929/46c55f35-55a9-4162-82e0-ca1a96fafdb4)
Получаем результат от утилиты:
![image](https://github.com/StepaBelyaev/Practic_4/assets/70752929/63e63385-77d1-423e-9b17-4c3698dcb7f9)













