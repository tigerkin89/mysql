# mysql for Ubuntu
우분트 14.04에 mysql를 설치합니다.

## docker 이미지 생성
```ruby
$ sudo docker build --tag .
```
## container 실행

```ruby
$ sudo docker run -d --name db -e MYSQL_ROOT_PASSWORD=examplepassword mysql
```

## Git upload
```ruby
$git init 
$git add *
$git commit -m "ffff" 
$git branch -M main git remote add origin https://github.com/tigerkin89/mysql 
$git push origin +main
```

