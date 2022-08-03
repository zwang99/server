# Linux-based Tiny Web Server

## Features:
- Developed a web server that can exchange tens of thousands of concurrent connection data based on C++ Programming Language in the Linux environment.
- Concurrency model using Thread Pool, Non-blocking Socket, Epoll, and Event processing.
- Utilized State machines to parse HTTP request packets, including GET and POST requests. Used Mysql as the server database to achieve user registration, login, and request server pictures and video files.
- Implemented synchronous/asynchronous log system to record server running status. A successful stress test was conducted using Webbench.
