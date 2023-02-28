# Demo JWT

## http://localhost:8080/api/random
* **Ban đầu chúng ta request vào http://localhost:8080/api/login sẽ xuất hiện lỗi 403: Access was denied, You don't have the user rights.**
![1A](https://github.com/Bachos0605/DemoJWT/blob/main/Static/1.png)
![1B](https://github.com/Bachos0605/DemoJWT/blob/main/Static/2.png)

## http://localhost:8080/api/login 
* **Cấp username, password đã có trong database và login vào hệ thống. Lúc này nó sẽ generate ra token.**
![2A](https://github.com/Bachos0605/DemoJWT/blob/main/Static/3.png)

## http://localhost:8080/api/random
* **Quay lại request ban đầu với token mới được generate và kết quả.**
![3A](https://github.com/Bachos0605/DemoJWT/blob/main/Static/4.png)

