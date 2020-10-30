# Powerflow_LP
支路潮流方程二阶锥松弛后进一步采用多面体松弛
参考文献[1] Jabr R A . Minimum Loss Network Reconfiguration Using Mixed-Integer Convex Programming[J]. IEEE Transactions on Power Systems, 2012, 27(2):1106-1115.
最近好像很火 因为可以由此写出KKT系统或者原对偶最优性条件 在电力市场出清中很火
但是复刻过程中发现精度高的时候求解速度比SOCP问题慢了很多。。
