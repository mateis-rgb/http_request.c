
# http_request.c

Ce programme vous permet de faire des requetes HTTP en GET ou POST.




## Requirements

You must have on your computer :
  * git (>=2.15.0)
  * gcc

## Installation

Intall http_request with git

```bash
$ git clone https://github.com/mateis-rgb/http_request.c.git
$ cd http_request.c
```

Compiling with gcc and run
* on Linux / MacOS :
```bash
$ gcc ./main.c -o http_request -lcurl && ./http_request
```
* on Windows :
```bash
$ gcc .\main.c -o http_request.exe -lcurl | .\http_request.exe
```


## Screenshots
Main window :
![Main Window](https://raw.githubusercontent.com/mateis-rgb/http_request.c/refs/heads/main/screenshots/main.png)

GET Request exemple :
![GET Request Exemple](https://github.com/mateis-rgb/http_request.c/blob/main/screenshots/get_exemple.png?raw=true)


## Tech

**Build With:** [libcurl](https://curl.se/libcurl/)
