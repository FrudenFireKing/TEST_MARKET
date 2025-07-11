# Test_market
RUS/РУС 
Testmarket – это веб-приложение для публикации и управления товарными объявлениями. 
Сервис предоставляет следующие возможности:  
- Размещение объявлений с указанием названия, описания, цены и изображения  
- Возможность включения/отключения функции "Торг" для каждого объявления  
- Просмотр списка всех объявлений с поиском по ключевым словам  
- Детальная страница объявления с полной информацией  
- Рейтинг продавцов на основе количества размещённых объявлений  
- Удобный административный интерфейс для управления контентом  

Реализованные функции  
- Создание и редактирование объявлений с валидацией данных  
- Загрузка изображений товаров (с отображением превью)  
- Поиск объявлений по заголовку  
- Автоматическое определение даты создания и обновления объявлений  
- Административный интерфейс с расширенными возможностями:  
  - Групповое включение/отключение функции "Торг"  
  - Фильтрация по дате и статусу торга  
  - Визуальное отображение изображений в виде миниатюр  
  - Подсветка свежих объявлений  
- Интеграция с системой пользователей Django  

Технологии  
- Backend: Python, Django  
- Database: SQLite (по умолчанию), с возможностью подключения других СУБД  
- Frontend: HTML, CSS, Bootstrap  
- Хранение файлов: локальное (с настройкой для облачных хранилищ)  
- Безопасность: встроенная аутентификация Django, CSRF-защита

Администрирование  
Доступ к панели администратора: `/admin`  
Возможности:  
- Полное управление объявлениями (создание, редактирование, удаление)  
- Групповые операции с объявлениями  
- Просмотр статистики по пользователям  
- Визуальное представление данных (изображения, подсветка дат)  


ENG/АНГ
Testmarket is a web application for publishing and managing product ads. 
The service provides the following features:
- Placement of ads with the name, description, price and image  
- The ability to enable/disable the "Торг" function for each ad  
- View a list of all ads with keyword search  
- Detailed ad page with full information  
- Seller rating based on the number of ads placed  
- User-friendly administrative interface for content management  

Implemented functions  
- Creating and editing ads with data validation  
- Download product images (with preview)
- Search for ads by title  
- Automatic determination of the date of creation and updating of ads  
- Administrative interface with advanced features:
- Group activation/deactivation of the "Торг" function  
  - Filtering by date and auction status  
  - Visual display of images in the form of thumbnails  
  - Highlighting of recent ads  
- Integration with the Django user system  

Technologies  
- Backend: Python, Django  
- Database: SQLite (by default), with the ability to connect other databases  
- Frontend: HTML, CSS, Bootstrap  
- File storage: local (with cloud storage settings)  
- Security: built-in Django authentication, CSRF protection

Administration  
Access to the admin panel: `/admin`  
Features:
- Full ad management (creation, editing, deletion)  
- Group operations with ads  
- View statistics on users  
- Visual representation of data (images, date highlighting)
