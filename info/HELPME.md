1. Docker:
- image-> postgres:12.20-alpine3.20
 port-> 5432:3036
POSTGRES_PASSWORD=password12@

2. How to run:
   + Application run as debug
   - gradle build -x test
   - in git bash ./gradlew build -x test

3. POST http://localhost:8080/user/name
4. GET http://localhost:8080/users
5. PUT http://localhost:8080/user/1?name=tester
6. DELETE http://localhost:8080/user/3

