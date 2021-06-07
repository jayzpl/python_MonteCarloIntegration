import random
import numpy as np


def math_function(x):
    return (-1) / np.sqrt(2 * x + 2)


def monte_carlo():
    """calculating the integral value of a selected function in the range from A to B using the Monte Carlo method"""
    a = 1  # a point of range
    b = 7  # b point of range
    number_of_points = 1000
    integral = 0.0
    for i in range(number_of_points):
        x = random.uniform(a, b)
        integral += math_function(x)
    return (b - a) / float(number_of_points) * integral


if __name__ == "__main__":
    monte_carlo()
