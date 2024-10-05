# Finances CTL
## The secure app to control your finances💵💰


Finances ctl is a simple app to control your finances, you could import or export data in format CSV, PDF,
save your financial income and expenses and protect your data also will got a free API to connect this app
to anothers applications.

- It is programmed in Java ☕

## Features

- Import and export CSV, PDF.
- Drag and drop CSV, PDF.
- Connect with a database in the internet to store your data.
- Give you an API REST that works to connect anothers applications to Finances CTR.


## Installation

##### 1) You must clone the project.
##### 2) You must have JDK v23.
##### 3) You must got Docker.
\
When you got all then you can run the procjet.

## Run the Project💻👨‍💻

The application needs arguments to run, but if it cannot read these arguments, then the application
will run as default configuration, these arguments are the environment and port it will run on,
The arguments it expects are the following:

```sh
$ java -jar FinancesCTL.jar [env] [port]
```

> Note: The env argument is only for displaying application logs, it has no other functionality.
\
For run as production environment...
```sh
$ java -jar FinancesCTL.jar prod
```
\
For run as development environment...

```sh
$ java -jar FinancesCTL.jar dev
```
> Note: `The app runs in a port determined is 3250 port then if it's in use by another program you
can change the Http Port Protocol, could open with a second argument another port, such its view below.

```sh
$ java -jar FinancesCTL.jar prod 3000
```
### To deploy in production🚀🌎

For production release:

## Docker


```sh
127.0.0.1:8000
```

## License

 GNU GENERAL PUBLIC LICENSE
                       Version 3, 29 June 2007

 Copyright (C) 2007 Free Software Foundation, Inc. <https://fsf.org/>
 Everyone is permitted to copy and distribute verbatim copies
 of this license document, but changing it is not allowed.
