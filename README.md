# Tutorial Spring Boot Rest Api CRUD

Tutorial Spring Boot, Mudahnya Membuat Rest API CRUD!

Tutorial ini dipisah untuk tiap aktifitas

atau bisa lihat di https://www.youtube.com/playlist?list=PL3UaiPxY2iuo0Bq-A_JrQg-ot9SDXCFX1
1. Initial Project https://youtu.be/N5d3kPlKJkA
2. Hello World https://youtu.be/ss3mWzNzocQ
3. Connect H2 Database https://youtu.be/i5L7W05CZ08
4. Create Entity (Table) https://youtu.be/BZ9pPWmPD8c
5. Create Data (POST) https://youtu.be/r5385g0EKRk
6. Read Data (GET) https://youtu.be/8nerEi_Gr2Y
7. Read Detail Data (GET) https://youtu.be/NXW5o-JsXhc
8. Update Data (PUT) https://youtu.be/jtffow6S52M
9. Delete Data https://youtu.be/LsfKgJqwIyg
10. Http Method https://youtu.be/E1_Cir6v2dQ

## Running On DOCKER
kamu juga bisa menjalankan service ini tanpa install kebutuhan jdk,
melalui docker. syaratnya sudah ter-install docker di komputer kamu.

``docker pull johnnyaustor/jap-spring-crud:tutorial-youtube``

``docker run --publish 8080:8080 johnnyaustor/jap-spring-crud:tutorial-youtube``

## Endpoint
POST `http://localhost:8080/employee`

GET `http://localhost:8080/employee`

GET `http://localhost:8080/employee/{id}`

PUT `http://localhost:8080/employee/{id}`

DELETE `http://localhost:8080/employee/{id}`

## Body Required
`` { id:number, firstName:string, lastName:string } ``