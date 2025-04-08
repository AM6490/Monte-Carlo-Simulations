In this exercise I decided to make things more practical by running monte carlo simulations for an efficient portfolio of 20 risky stocks. I first started by finding the efficient portfolio using Python's
EfficientFrontier library. After I found the efficient frontier I selected the optimized portfolio and ran 5,000 simulations, and then 10,000 to see the differences. As expected the differences weren't so high
I would run 50,000 or even 100,000 simulations if I had the time and computational power, but for now 5,000 to 10,000 works. I vectorized to make things faster.

For a portfolio with an initial value of 100,000, we found that the expected portfolio value after 4 years will be around 350,000, with a worst case scenario of 18,906 and a best case scenario of 5.3 million. 
This is highly volatile, and many of the assets are definitely highly correlated hence this huge range, I'll probably first try to experiment with asset allocation to maximize return with a given level of risk. 

But today's purposes I wanted to experiment with a basic form of optimization and risk analysis. 
