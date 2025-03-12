# swipepay-wallet-api
---------------------
An API that is used by a mobile app.
The API interacts with a database and external billing vendors to allow the a user to manage their bills/utilities that they would like to pay. The API will also interact with various crypto networks and exchanges to allow you to pay a utility with a digital currency. (That part was a WIP, so not complete).



SDKs in use are:
- oracle java 1.8.0

Dependencies in use are:

spring boot 1.5.9:
- actuator
- aop
- jpa
- security
- web

apache commons:
- beanutils		1.9.3
- collections4	4.1
- lang3			3.5
- validator		1.6

hibernate:
- java8 jdbc	5.0.11.Final

mariadb:
- java-client	2.2.0
