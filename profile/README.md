# SimplSrecka

|   |   |
|--|--|
|__Naziv Projekta__| SimplSrečka |
|__Člani Skupine__| Brecelj Luka, Kržan Ariana |
|__Opis Projekta__| Razvili bomo spletno loterijo SimplSrečka, ki bo ponujala svojo srečko z istim imenom. Poleg te bo mogoče kupiti tudi druge srečke kot so Eurojackpot in Loto. Aplikacija bo ponujala vplačilo srečk, ogled rezultatov žrebanj in upravljanje s svojim stanjem. |
|__Razvojno ogrodje__| Java, Docker, Kubernetes |

## Funkcionalnosti
* Registracija
* Login
* Logout
* Ogled kataloga srečk
* Izbira kombinacije
* Vplačilo kombinacije
* Ogled vseh svojih vplačanih kombinacij
* Ogled preteklih rezultatov žrebanj za vse kategorije srečk
* Žrebanje SimplSrečke
* Ogled stanja na računu
* Polnjenje stanja
* Dvig stanja


## Use Case
* Nakup srečke
* Polnjenje sranja
* Dvig stanja
* Filtriranje srečk glede na velikost dobitka
* Ogled svojih zadetkov


## Lottery Ticket Catalog microservice:
* https://hub.docker.com/r/lb4684/lottery-ticket-catalog
* https://github.com/SimplSrecka/lotteryTicketCatalog

## User microservice:
* https://hub.docker.com/r/lb4684/user
* https://github.com/SimplSrecka/user

## Payment and transcation microservice:
* https://hub.docker.com/r/lb4684/payment-transcations
* https://github.com/SimplSrecka/paymentTransactions

## Lottery drawing and results microservice:
* https://hub.docker.com/r/lb4684/lottery-drawing-results
* https://github.com/SimplSrecka/lotteryDrawingResults
