# AMAK-100_parser
 Network Parser AMAK protocol

# Настройка для использования:
1) Файл amak-100.npl скопировать в папку "C:\User\Пользователь\Documents\Network Monitor 3\Parsers"

2) В фале "my_sparser.npl" добавить строку:
include "amak-100.npl"

3) В программе Microsoft Network Monitor создаем новый профиль:
Tools -> Options
вкладка Parser Profiles
Выбираем профиль "Default", нажимаем "New", выбираем "Create from Selected", указываем имя создаваемого
профиля (например, "Copy of Default")
Дважды щелкаем на созданом профиле, дле его редактирования.
В поле "Parser Search Paths" нажимаем "New" и указываем путь к папке 
"C:\User\Пользователь\Documents\Network Monitor 3\Parsers"
Перемещаем путь в начало списка. Нажимаем "Ок".
Устанавливаем созданный профиль как профиль по умолчанию. Нажимаем "Ок".

Переходим на вкладку "Parsers". Нажимаем "Rebuild Parsers"
После завершения компиляции можно пользоваться.
Содержимое пакетов будет показываться с учетом полей протокола АМАК.
