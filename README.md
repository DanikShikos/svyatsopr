# svyatsopr
1.	Руководство по эксплуатации модулей, обслуживания, настройки и обновления программного продукта
Таблица 1 - Эксплуатация модулей обслуживания
Модуль	Функция	Описание	Эксплуатация
Configuration_class.cs	SQL_Server_Configuration_Get	Проверяет наличие данных об источнике подключения и названии базы данных, и берет эти данные для формирования строки подключения	Вызывается втоматически при запуске
	SQL_Data_Base_Checking	Пробует установить подключение при проверке подключения на форме соединения	
aAuthorize.xaml.cs	SystemChek	Проверяет, соответствует ли система установленным требованиям, беря из регистра такие данные как: свободная оперативная память, свободное место на жестком диске, версия ОС, ключи установленных приложений, пробует установить соединение; и на основе этих данных выводит соответствующие ошибки	
SvyatayaTroicaInstall	Install	Проверяет наличие программы и модулей на компьютере, если нет – установить, есть – обновить	Запустить установщик и следовать инструкциям установщика
	Update	Переустанавливает существующие модули и устанавливает недостающие (необходима последняя версия загрузчика)	
	Uninstall	Удаляет программу с компьютера	

2.	Руководство по эксплуатации информационного ресурса
Наименование функции	Эксплуатация	Изображение
Подключение к серверу БД	После первого запуска программы, пользователь должен подключиться к серверу и БД, выбрав из предложенного списка, нажав на кнопку «Подключение», при повторном запуске делать этого не потребуется	 
Авторизация	Пользователь должен либо авторизоваться чтобы войти в систему. Для авторизации ввести свой логин, пароль и нажать кнопку «Вход». Если не зарегистрирован, нажать на «Регистрация»	 
Регистрация	Чтобы зарегистрироваться, нужно ввести свои данные, указать если он создает аккаунт, выбрав свою должность, и нажать кнопку «Зарегистрироваться»	 
Представление и выбор данных	При переходе на одну из таблиц, пользователю представляется информация в табличном виде, при выборе одной из записей, поля ввода автоматически заполняются выбранными значениями, а также выбранную запись возможно изменить или удалить	 
Добавление	Пользователь должен заполнить поля и нажать на кнопку «Добавить запись»	 
Изменение	Для изменения нужно выбрать запись, которую необходимо изменить, произвести редактирование данных и нажать на кнопку «Изменить запись»	 
Удаление	Для удаления нужно выбрать запись, которую необходимо удалить, нажать «Удалить запись», затем нажать «Да» в появившемся окне предупреждения 	 
Поиск	В сточку поиска, пишутся данные, которые необходимо найти в таблице и при нажатии на кнопку «Поиск», поля ввода заполняются найденными данными	 
Фильтрация	В сточку поиска, пишутся данные, по которым необходимо произвести фильтрацию, далее нужно нажать на чекбокс, и в таблице будут показаны только данные, которые соответствуют введенным	 
Экспортировать данные	Пользователь может экспортировать данные и сохранить его в формате doc, xls и pdf для этого нужно нажать на кнопку «Сформировать..» на любой форме, где она есть	 
3.	Руководство по эксплуатации системы контроля версий
Наименование функции	Эксплуатация	Изображение
Авторизация	Пользователь должен либо авторизоваться чтобы войти в систему. Для авторизации ввести свой логин, пароль и нажать кнопку «Вход». Если не зарегистрирован, нажать на «Регистрация»	 
Регистрация	Чтобы зарегистрироваться, нужно ввести логин и сложный пароль, подтвердить пароль, и нажать кнопку «Зарегистрироваться», после чего пользователь сможет войти в систему под этими данными	 
Создание записи	Пользователь должен заполнить поля и нажать на кнопку «Добавить»	 
Скачивание программы	Пользователь должен перейти в главное меню и выбрать одну из доступных для скачивания версий, нажать на соответствующую кнопку, после чего скачается установщик программы	 

4.	Руководство по эксплуатации CRM – системы
Наименование функции	Эксплуатация	Изображение
Связь с разработчиком	Чтобы написать на почту разработчику нужно нажать на «Связаться с нами» на навигационной панели и ввести данные, после чего нажать «Отправить»	 
Создание отзыва	Необходимо перейти в «Отзывы» на панели навигации и нажать «Оставить отзыв», после чего заполнить все поля и нажать «Оставить»	 
 
