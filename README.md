## Book Shop 


1. Для страницы "жанры" в ```resources/templates``` был создан ```genres.html```, в котором 
вручную были прописаны жанры для проверки работоспособности страницы. Созданы зависимости
для возможности перехода между страницами "жанры" и "главная".

2. Для страницы "авторы" был создан ```authors.html```, обеспечена возможность переходов 
между страницами "главная" - "жанры" - "авторы".

3. В базе данных была создана таблица ```authors``` которая пополняется автометически
за счет таблицы ```books```. Создание таблицы и её поля содержаться в файле ```schema.sql```,
само её наполнение данными содержится в ```data.sql```