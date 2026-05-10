__Метод:__ GET

__URL:__ /api/v1/profile

__Пример запроса на сервер:__ https://{домен}/api/v1/profile


__Response Body (code and status):__
200 OK
{
    "basicDetails": {
        "fullName": "string",
        "dateOfBirth": "string",
        "gender": "string"
    },
    "contactDetails": {
        "phone": "string",
        "email": "string",
    },
    "personalDetail":{
        "weight": 64,
        "height": 175.5
    }
}

__Ошибки:__
400
401
403
404

500