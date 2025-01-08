# IsSimilar 

Use this evaluation function to check if the student's reponse is within a tolerance range defined in `params`. Works exactly like the [numpy.isclose](https://numpy.org/doc/stable/reference/generated/numpy.isclose.html#numpy.isclose) function. Valid params include `atol` and `rtol` (absolute and relative tolerances) which can be used in combination, or alone.

**Note:** If the answer is not a number, all responses will generate an error.

**Note:** If the response is not a number, a feedback message asking the user to submit a number will be returned.