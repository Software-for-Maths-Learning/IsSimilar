# IsSimilar 

Use this evaluation function to check if the student's reponse is within a tolerance range defined in `params`. Works exactly like the [numpy.isclose](https://numpy.org/doc/stable/reference/generated/numpy.isclose.html#numpy.isclose) function. Valid params include `atol` and `rtol` (absolute and relative tolerances) which can be used in combination, or alone.