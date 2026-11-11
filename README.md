# Restful-Booker API tests

Postman-коллекция для https://restful-booker.herokuapp.com, запуск через newman.

## Запуск

    npm install
    npx newman run Restful-booker.postman_collection.json -e Restful-booker.postman_environment.json --env-var "baseURL=https://restful-booker.herokuapp.com/" --folder Authorization --folder Booking_CRUD
    npx newman run Restful-booker.postman_collection.json -e Restful-booker.postman_environment.json --env-var "baseURL=https://restful-booker.herokuapp.com/" -d data.csv --folder Lesson2_dataDriven
