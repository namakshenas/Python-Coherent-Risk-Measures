# Python-Coherent-Risk-Measures
Python scripts for four risk measurement models, including Value at Risk (VAR), Conditional Value at Risk (CVaR), Markowitz, and Mean-Variance Model

I compiled 232 indexes based on their closing prices from Tehran's stock market for 103 consecutive months. Each notebook consists of three blocks:
- Data preparation and transforming them into a pseudo-convex matrix (You need pandas and numpy)
- Modeling linear or quadratic programming (You need gurobipy and a valid license)
- Solving and iterating over different returns to get risk values (You need matplotlib)
A sample output (Pareto):
![dfVaR_return_risk](https://user-images.githubusercontent.com/51627278/169480304-75de6de0-22a5-46cb-8946-a4e841afab7d.png)
A sample output (Diversifying Power):
![dfVaR_diversity](https://user-images.githubusercontent.com/51627278/169480358-b38146db-b2c7-4c62-9857-dc0c20b6efec.png)
