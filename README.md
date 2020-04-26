# ToDo
Hello! My Name is Viktor
<!DOCTYPE html>
<html>
    <head>
        <title>Приложение To-Do List</title>
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="css/todo.css">
        <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.13/css/all.css" integrity="sha384-DNOHZ68U8hZfKXOrtjWvjxusGo9WQnrNx2sqG0tfsghAvtVlRW3tvkXWZh58N9jp" crossorigin="anonymous">
        <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Bad+Script">
        <link rel="shortcut icon" href="assets/favicon.ico">
        <link rel="icon" type="image/gif" href="assets/animated_favicon.gif">
    </head>
    <body>
        <div id="todo">
            <h1>Мои списки дел <i id="pensil" class="fas fa-pencil-alt"></i></h1>
            <input type="text" placeholder="Добавить список">
            <ul class="todos">
                <li><span class="todo-text">Вымыть кухню</span><span class="todo-trash"><i class="fas fa-trash-alt"></i></span></li>
                <li><span class="todo-text">Пойти в театр</span><span class="todo-trash"><i class="fas fa-trash-alt"></i></span></li>
            </ul>
            <div id="buttons">
                <button class="save">Сохранить</button>
                <button class="clear">Очистить</button>
                <button class="showTips">Справка</button>
            </div>
        </div>
        <div id = "overlay">
            <a href="javascript:void(0)" class="closeTips">&times;</a>
            <ul class="tips">
                <li>Чтобы спрятать или показать поле ввода, кликните на карандаш</li>
                <li>Для добавления списка дел напишите текст в поле ввода и нажмите Ввод</li>
                <li>Чтобы удалить один пункт, наведите на него и нажмите на значок корзины</li>
                <li>Чтобы удалить все списки дел, нажмите "Очистить"</li>
                <li>Нажмите "Сохранить", чтобы сохранить список дел на потом</li>
            </ul>
        </div>
    </body>
</html>
