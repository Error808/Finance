## Introduction

The Project proposes the following:
* Implemented a web application that enables the user can "buy" and "sell" stocks, following the criteria below:
* Complete the implementation of **register** in such a way that it allows a user to register for an account via a form.
* Complete the implementation of **quote** in such a way that it allows a user to look up a stock’s current price.
* Complete the implementation of **buy** in such a way that it enables a user to buy stocks.
* Complete the implementation of **sell** in such a way that it enables a user to sell shares of a stock (that he or she owns).
* Complete the implementation of **index** in such a way that it displays an HTML table summarizing, for the user currently logged in, which stocks the user owns, the numbers of shares owned, the current price of each stock, and the total value of each holding (i.e., shares times price). Also display the user’s current cash balance along with a grand total (i.e., stocks' total value plus cash).
* Complete the implementation of **history** in such a way that it displays an HTML table summarizing all of a user’s transactions ever, listing row by row each and every buy and every sell.
* Complete the implementation of **check** in such a way that it checks whether a username is available.

## Created with
This application uses Python, HTML and styling with Bootstrap. It also uses [IEX API](https://iexcloud.io/) to get the stocks values in real time and a SQL database to store users information, such as username, a hash of the password, the stocks they bought or sold and the history.

## Access
My application is available at https://financer50.herokuapp.com/.
