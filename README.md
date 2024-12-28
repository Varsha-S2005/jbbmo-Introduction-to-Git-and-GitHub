# Input:
#   p, principal amount
#   t, time period in years
#   r, annual rate of interest
# Output:
#   simple interest = p*t*r
# Made changes by Varsha

p=1000   # Example principal amount
t=5      # Example time period in years
r=7      # Example annual rate of interest

# Calculate simple interest
simple_interest=$((p * t * r))
echo "Simple Interest: $simple_interest"
