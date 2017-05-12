# Courses API

### Currently available:
- REST for /courses
- REST for /users
- authorization

### Authorization:
To get authorized request: 
```
POST /users/login 
body: {
  login: 'yurec',
  password: 'yurec'
}
```
In response will be recieved "access_token", which can be used like that:
```
http://localhost:3000/api/users?access_token=${ access_token }
```

### How to work:

To install run:
```
npm i
```
To start:
```
npm start
```
API will became available on localhost on port 3000 with ```/api``` path, e.g.:
```
http://localhost:3000/api/courses
```
Swagger documentation should be available on:
```
http://localhost:3000/exlorer/
```
