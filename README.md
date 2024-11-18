<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Одностраничный сайт</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            background-color: #f4f4f9;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .profile {
            display: flex;
            align-items: flex-start;
        }
        .profile-photo {
            flex-shrink: 0;
            margin-right: 20px;
        }
        .profile-photo img {
            width: 150px;
            height: 150px;
            border-radius: 10px;
            object-fit: cover;
        }
        .profile-info {
            max-width: 500px;
        }
        .profile-info h2 {
            margin: 0;
            margin-bottom: 10px;
        }
        .profile-info p {
            margin: 0;
            color: #555;
        }
        .gallery {
            margin-top: 30px;
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(150px, 1fr));
            gap: 10px;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile">
            <div class="profile-photo">
                <img src="https://via.placeholder.com/150" alt="Арт фото">
            </div>
            <div class="profile-info">
                <h2>Иван Иванов</h2>
                <p>Возраст: 25 лет</p>
                <p>Город: Москва</p>
                <p>Интересы: Путешествия, Искусство, Программирование</p>
                <p>Описание: Привет! Я люблю открывать новые места и делиться своими впечатлениями. Ищу новых друзей для приключений!</p>
            </div>
        </div>
        <div class="gallery">
            <img src="https://via.placeholder.com/150?text=Фото+1" alt="Фото 1">
            <img src="https://via.placeholder.com/150?text=Фото+2" alt="Фото 2">
            <img src="https://via.placeholder.com/150?text=Фото+3" alt="Фото 3">
            <img src="https://via.placeholder.com/150?text=Фото+4" alt="Фото 4">
        </div>
    </div>
</body>
</html>
