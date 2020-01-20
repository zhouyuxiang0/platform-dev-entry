|-- mongo

    |-- docker-entrypoint-initdb.d          // mongo初始化文件夹 .sh  .js

|-- mysql

    |-- docker-entrypoint-initdb.d          // mysql初始化sql文件夹 .sql

|-- nginx

    |-- sites                               // nginx配置文件 .conf

|-- .env                                    // docker-compose.yml使用的变量

|-- docker-compose.yml                      // docker-compose配置