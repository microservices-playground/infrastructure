# Infrastructure

Infrastructure

## Hosts

ip              | hostname      | purpose               | forwarded ports (guest -> host)
----------------|---------------|-----------------------|--------------------------------
192.168.100.2   | db-foodlove   | mysql server          | 3306 -> 13306
192.168.100.3   | db-comments   | mysql server          | 3306 -> 23306
192.168.100.4   | db-activities | mongodb server        | 27017 -> 37017
192.168.100.100 | api-comments  | comments microservice | 80 -> 8080
