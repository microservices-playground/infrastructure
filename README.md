# Infrastructure

Infrastructure

## Hosts

ip              | hostname       | purpose                 | forwarded ports (guest -> host)
----------------|----------------|-------------------------|--------------------------------
192.168.100.2   | db-foodlove    | mysql server            | 3306 -> 13306
192.168.100.3   | db-comments    | mysql server            | 3306 -> 23306
192.168.100.4   | db-activities  | mongodb server          | 27017 -> 37017
192.168.100.5   | db-imbo        | mongodb server          | 27017 -> 47017
192.168.100.50  | io-rabbitmq    | rabbitmq server         | 5672 -> 5672, 15672 -> 15672
192.168.100.51  | cdn-imbo       | image server            | 80 -> 9080
192.168.100.100 | api-comments   | comments microservice   | 80 -> 8080
192.168.100.101 | api-activities | activities microservice | 5000 -> 5050
