# Note
The repository containing the actual implementation of this agent is private per Georgia Tech Policy. Let me know if you need to see the code for this project.

# Market Simulator
In marketcodesim.py there is a market simulator with configurable price movement and trading fees.

# Trading Strategies
There are two trading strategies: the first is a manual strategy based on techincal indicators in ManualStrategy.py, the second is a reinforcement random forest bagging learner trained on price data and technical indicators in RTLearner.py, BagLearner.py, and StrategyLearner.py

# Use Case
This repo can be used to test and develop strategies. In sample strategy performance: ![BenchvsManualvsLearnerIS](https://github.com/user-attachments/assets/89d97147-2880-4432-84ed-7dd8f21cb7ff)

Out of sample strategy performance: ![BenchvsManualvsLearnerOS](https://github.com/user-attachments/assets/ac4032cb-5804-4b91-939d-17c328c6f295)

# References
Georgia Tech CS 7646: Machine Learning for Trading
https://omscs.gatech.edu/cs-7646-machine-learning-trading
