# Financial Planner

The purpose of this project was to create a financial analysis tool in which users will be able to visualize their current savings and determine if they have enough reserves for an emergency fund. Also, another financial analysis tool was created to forecast the performance of the user's retirement portfolio in 30 years. These tools make an Alpaca API call via the Alpaca SDK to get historical price data for use in Monte Carlo simulations. The main programming language for used was Python.

## Personal Finance Planner

The first tool as mentioned helps users visualize their current savings and determine if they have enough reserves for an emergency fund. In this example, the user's portolio that was analyzed contained cryptocurrencies and stocks. The value and the amount of this person's crypto assets was retrieved using Crypto APIs. As mentioned, Alpaca was used to grab the user's historical prices of its stocks. This was then used to find the total value of its stock assets. Some variables and fucntions were created to plug and chug the amount of crypto and stocks in the user's portfolio to calculate the total amount of the user's portfolio and display it on the graph below:

![Screenshot 2022-12-12 231938](https://user-images.githubusercontent.com/104874384/207225689-6ce9407b-a899-43fb-ae59-71d1f4de8e1f.png)

Using variables and an "if/else" statement, the user's portfolio can be determined whether it has enough reserves for an emergency fund. The function used can be seen below:

![Screenshot 2022-12-12 232257](https://user-images.githubusercontent.com/104874384/207226102-2a91ba11-66c4-4755-8039-7ab04d0c4ac2.png)

In this example, the user's portfolio has enough money for an emergency fund.

## Retirement Planning

This financial analysis tool as mentioned could forecast the performance of the user's retirement portfolio in 30 years using a Monte Carlo simulation. The historical price data received from the Alpaca API was organized in a DataFrame. Then a variable was created to call the Monte Carlo Simulation. Once the data was fitted into the model, 500 different simulations were generated that forecasted cumulative returns of each portfolio in 30 years. The outcomes were plotted in the graph below:

![Screenshot 2022-12-14 181734](https://user-images.githubusercontent.com/104874384/207736000-30ed2b96-40d8-4773-abaf-b81deb4447b3.png)

Then the probability distribution/confidence intervals of all 500 simulations were plotted in the graph below:

![Screenshot 2022-12-14 181934](https://user-images.githubusercontent.com/104874384/207736441-becfc9cd-49fc-4f29-9564-a59878704ad4.png)

The stats of this retirement analysis is shown below:

![Screenshot 2022-12-14 182044](https://user-images.githubusercontent.com/104874384/207736453-29498a7c-dae6-4101-9f34-d88e9ffd9a0f.png)

Using these stats and some functions, the returns on a $20,000 and $30,000 investment were calculated.

Based on results, there is a 95% chance that an initial investment of $20,000 in the portfolio over the next 30 years will end within in the range of $27,154.97 and $371,058.71

In addition, there is a 95% chance that an initial investment of $30,000.0 in the portfolio over the next 30 years will end within in the range of $40,732.46 and $556,588.07
