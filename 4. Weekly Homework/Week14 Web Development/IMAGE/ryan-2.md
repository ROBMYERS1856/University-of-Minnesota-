sysadmin@UbuntuDesktop:~/Documents$ curl --cookie-jar ./ryancookies.txt --form "log=Ryan" --form "pwd=123456" http://localhost:8080/wp-login.php --verbose
*   Trying 127.0.0.1...
* TCP_NODELAY set
* Connected to localhost (127.0.0.1) port 8080 (#0)
> POST /wp-login.php HTTP/1.1
> Host: localhost:8080
> User-Agent: curl/7.58.0
> Accept: */*
> Content-Length: 240
> Content-Type: multipart/form-data; boundary=------------------------55b01593688bc5a6
> 
< HTTP/1.1 302 Found
< Date: Fri, 08 Oct 2021 00:50:55 GMT
< Server: Apache/2.4.10 (Debian)
< X-Powered-By: PHP/5.6.28
< Expires: Wed, 11 Jan 1984 05:00:00 GMT
< Cache-Control: no-cache, must-revalidate, max-age=0
* cookie size: name/val 21 + 15 bytes
* cookie size: name/val 4 + 1 bytes
* Added cookie wordpress_test_cookie="WP+Cookie+check" for domain localhost, path /, expire 0
< Set-Cookie: wordpress_test_cookie=WP+Cookie+check; path=/
< X-Frame-Options: SAMEORIGIN
* cookie size: name/val 42 + 130 bytes
* cookie size: name/val 4 + 19 bytes
* cookie size: name/val 8 + 0 bytes
* Added cookie wordpress_37d007a56d816107ce5b52c10342db37="Ryan%7C1633827055%7CfoRVACnywViNLj9oP595X3ePCsiPgSpOSyLBbAw7Abl%7C2b94ad8d7ad998217990e4881b2efe7bc067955a2b5b004e6738c43aab342335" for domain localhost, path /wp-content/plugins, expire 0
< Set-Cookie: wordpress_37d007a56d816107ce5b52c10342db37=Ryan%7C1633827055%7CfoRVACnywViNLj9oP595X3ePCsiPgSpOSyLBbAw7Abl%7C2b94ad8d7ad998217990e4881b2efe7bc067955a2b5b004e6738c43aab342335; path=/wp-content/plugins; httponly
* cookie size: name/val 42 + 130 bytes
* cookie size: name/val 4 + 9 bytes
* cookie size: name/val 8 + 0 bytes
* Added cookie wordpress_37d007a56d816107ce5b52c10342db37="Ryan%7C1633827055%7CfoRVACnywViNLj9oP595X3ePCsiPgSpOSyLBbAw7Abl%7C2b94ad8d7ad998217990e4881b2efe7bc067955a2b5b004e6738c43aab342335" for domain localhost, path /wp-admin, expire 0
< Set-Cookie: wordpress_37d007a56d816107ce5b52c10342db37=Ryan%7C1633827055%7CfoRVACnywViNLj9oP595X3ePCsiPgSpOSyLBbAw7Abl%7C2b94ad8d7ad998217990e4881b2efe7bc067955a2b5b004e6738c43aab342335; path=/wp-admin; httponly
* cookie size: name/val 52 + 130 bytes
* cookie size: name/val 4 + 1 bytes
* cookie size: name/val 8 + 0 bytes
* Added cookie wordpress_logged_in_37d007a56d816107ce5b52c10342db37="Ryan%7C1633827055%7CfoRVACnywViNLj9oP595X3ePCsiPgSpOSyLBbAw7Abl%7Ca2f885321c11716fdb1e4472d1d50eda9b0da74ae3a4f3becad9d53e94d5ef9c" for domain localhost, path /, expire 0
< Set-Cookie: wordpress_logged_in_37d007a56d816107ce5b52c10342db37=Ryan%7C1633827055%7CfoRVACnywViNLj9oP595X3ePCsiPgSpOSyLBbAw7Abl%7Ca2f885321c11716fdb1e4472d1d50eda9b0da74ae3a4f3becad9d53e94d5ef9c; path=/; httponly
< Location: http://localhost:8080/wp-admin/
< Content-Length: 0
< Content-Type: text/html; charset=UTF-8
* HTTP error before end of send, stop sending
< 
* Closing connection 0
