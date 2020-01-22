# Examining-Approaches-to-saddle-point-escaping-using-non-convex-optimization
A lot of research has been done on finding a global optimum value of a function. Many first order methods give very good results but their performance deteriorates because these methods get stuck in saddle points most of the time. Modern machine learning problems need local minimas in order to solve them. The main obstacle to solving these problems is that the loss function contains a lot of saddle points. Saddle points are surrounded by high error planes that can dramatically slow down learning and gives the idea of the existence of a local minimum. Another problem is the increase in dimensions. As the dimensions increase, the number of saddle points increase. In this paper we look at the various stochastic and deterministic methodologies to ensure that the algorithm is not stuck in a saddle point and is efficiently able to escape these points. We look at recent research being done on escaping saddle points and make a comparison on the efficiency. complexity and approach of these methodologies.
