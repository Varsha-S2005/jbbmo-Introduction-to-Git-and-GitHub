#!/bin/bash

# Input:
#   p, principal amount
#   t, time period in years
#   r, annual rate of interest
# Output:
#   simple interest = p * t * r

# Example values (you can modify these as needed)
p=1000   # Principal amount in dollars
t=5      # Time period in years
r=7      # Annual rate of interest in percent

# Calculate the simple interest
simple_interest=$((p * t * r / 100))  # Formula for simple interest

# Display the result
echo "The Simple Interest for a principal of $p, time period of $t years at an interest rate of $r% is: $simple_interest"
