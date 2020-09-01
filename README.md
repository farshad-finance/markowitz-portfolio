# Markowitz Portfolio Optimization 
Here I use Mosek opensource code which is a great library to solve linear and nonlinear optimization
problems.
Markowitz portfolio optimization is based on variance reduction and 
we do an optimization to maximize returns while bounding portfolio variance.


# results

================================
Markowitz portfolio optimization
================================


-----------------------------------------------------------------------------------
Basic Markowitz portfolio optimization
-----------------------------------------------------------------------------------

Expected return: 6.8475e-02 Std. deviation: 3.5000e-02
Expected return: 7.0998e-02 Std. deviation: 4.0000e-02
Expected return: 7.4781e-02 Std. deviation: 5.0000e-02
Expected return: 7.8039e-02 Std. deviation: 6.0000e-02
Expected return: 8.1084e-02 Std. deviation: 7.0000e-02
Expected return: 8.4016e-02 Std. deviation: 8.0000e-02
Expected return: 8.6880e-02 Std. deviation: 9.0000e-02

-----------------------------------------------------------------------------------
Efficient frontier
-----------------------------------------------------------------------------------

alpha         return        risk        
	0.0000        1.0730e-01    1.6667e-01  
	0.0100        1.0730e-01    1.6667e-01  
	0.1000        1.0730e-01    1.6667e-01  
	0.2500        1.0321e-01    1.4975e-01  
	0.3000        8.0528e-02    6.8138e-02  
	0.3500        7.4293e-02    4.8594e-02  
	0.4000        7.1959e-02    4.2311e-02  
	0.4500        7.0640e-02    3.9188e-02  
	0.5000        6.9760e-02    3.7329e-02  
	0.7500        6.7673e-02    3.3816e-02  
	1.0000        6.6805e-02    3.2802e-02  
	1.5000        6.6001e-02    3.2130e-02  
	2.0000        6.5615e-02    3.1905e-02  
	3.0000        6.5235e-02    3.1746e-02  
	10.0000       6.4710e-02    3.1633e-02  

-----------------------------------------------------------------------------------
Markowitz portfolio optimization with market impact cost
-----------------------------------------------------------------------------------

Expected return: 6.8120e-02 Std. deviation: 3.5000e-02 Market impact cost: 7.5201e-03

-----------------------------------------------------------------------------------
Markowitz portfolio optimization with transaction cost
-----------------------------------------------------------------------------------

Optimal portfolio: 

	x[0 ]  1.1140e-01  
	x[1 ]  1.1444e-01  
	x[2 ]  7.4319e-01  


