# StackOverflow-users-parser

## 📝Description
This app parse users from <a href="https://api.stackexchange.com/docs">StackExchangeAPI</a>
and filter response by: 
* required countries;
* required tags;
* min answered questions;
* tags in profile

StackExchangeAPI has a limit on the number of requests and the frequency of requests, therefore, a limit is set on the amount of the request
and the delay between each set of requests.

## 🌐Technologies
* JDK 17 
* Maven 4.0
* Retrofit2
* Lombok 1.18.24