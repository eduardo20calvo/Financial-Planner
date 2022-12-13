# Financial Planner

The purpose of this project was to create a financial analysis tool in which users will be able to visualize their current savings and determine if they have enough reserves for an emergency fund. Also, another financial analysis tool was created to forecast the performance of the user's retirement portfolio in 30 years. These tools make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlos simulations. The main programming language for these tools is Python.

## Personal Finance Planner

The first tool as mentioned helps users visualize their current savings and determine if they have enough reserves for an emergency fund. In this example, the user's portolio that was analyzed contained cryptocurrencies and stocks. The value and the amount of this person's crypto assets was retrieved using Crypto APIs. As mentioned, Alpaca was used to grab the user's historical prices of its stocks. This was then used to find the total value of its stock assets. Some variables and fucntions were created to plug and chug the amount of crypto and stocks in the user's portfolio to calculate the total amount of the user's portfolio and display it on the graph below:

![Screenshot 2022-12-12 231938](https://user-images.githubusercontent.com/104874384/207225689-6ce9407b-a899-43fb-ae59-71d1f4de8e1f.png)

Using variables and an "if/else" statement, the user's portfolio can be determined whether it has enough reserves for an emergency fund. The function used can be seen below:

![Screenshot 2022-12-12 232257](https://user-images.githubusercontent.com/104874384/207226102-2a91ba11-66c4-4755-8039-7ab04d0c4ac2.png)

In this example, the user's portfolio has enough money for an emergency fund.

## Retirement Planning

This financial analysis tool as mentioned could forecast the performance of the user's retirement portfolio in 30 years.

