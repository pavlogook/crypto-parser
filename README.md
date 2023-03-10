<h1 align="center">
  Crypto Parser
</h1>

<p align="center">
  <a href="#-description">Description</a> •
  <a href="#-architecture">Architecture</a> •
  <a href="#-technologies">Technologies</a> •
  <a href="#-how-to-start-the-program">How to start the program</a>
</p>

## 📃 Description
This is a simple program API where you can find out the price statistics of various cryptocurrencies.
The program supports three cryptocurrencies: BTC, ETH, XRP and their price is presented in USD.

Also you can open [swagger](http://localhost:6868/swagger-ui/index.html) in your brauser and check all endpoints.

This is an example of CSV-file you can create:

```
Cryptocurrency Name,Min Price,Max Price
BTC,22196.8,22212.7
ETH,1564.18,1564.26
XRP,0.39704,0.3973
```

## ⚙ Architecture
|       3-layer architecture       |
|:--------------------------------:|
|  Controller (Presentation layer) |
|                ↓↑                |
|    Service (Application layer)   |
|                ↓↑                |
|  Repository (Data access layer)  |

## 🧑‍💻 Technologies
| Technology    | Version |
|:--------------|:--------|
| JDK           | 17      |
| Maven         | 4.0.0   |
| Spring Boot   | 3.0.4   |
| Swagger       | 3       |
| Retrofit      | 2.9.0   |

## 📎 How to start the program
1. Clone the project from GitHub
2. Run `mvn clean package -DskipTests`
3. After run `docker-compose up`
4. When program is started successfully, open the [link](http://localhost:6868/) in your browser
5. Enjoy the program 😉
