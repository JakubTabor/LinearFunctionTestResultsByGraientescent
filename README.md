# LinearFunctionTestResultsByGraientescent
# It is important to test your data with (number of iterations and learning_rate) by changing number of iterations and number in learning_rate to get in the end number that You need
# this function [def predict_using_sklean():] retrun coef_ and intercept_
# [if math.isclose(cost, cost_previous, rel_tol = 1e-20):] it means that if my cost is in this range (1e-20) i stop my loop
# In this part (y_predicted = m_curr * x + b_curr) this is a pattern to calculate [Y] which is  [Y_predicted]
# There are the patterns to calculate M-Derivate and B-Derivate """ md = -(2/n)*sum(x*(y - y_predicted)) , bd = -(2/n)*sum(y - y_predicted) """
# Here i calculate my [m] an [b] """ m_curr = m_curr - learning_rate * md , b_curr = b_curr - learning_rate * bd """
