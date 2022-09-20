# js-postman


![Image alt](https://github.com/distant007/js-postman/raw/main/image_2022-09-20_14-44-22.png)
При регистрации использовал документацию для указания пути и правильного заполения body. В итоге получил положительный ответ с данными созданого пользователя и уникальным токеном. 
![Image alt](https://github.com/distant007/js-postman/raw/main/image_2022-09-20_14-45-06.png)
Далее логинился, также использая документацию для указания пути и body. В итоге получил положительный ответ. 
![Image alt](https://github.com/distant007/js-postman/raw/main/image_2022-09-20_14-45-37.png)
Далее для моего получения моего профиля использовал раздел Authorization, куда прописывал токен профиля,в ответе получил данные:
{
    "profile": {
        "username": "gibirbeg",
        "image": "https://static.productionready.io/images/smiley-cyrus.jpg",
        "following": false
    }
}

