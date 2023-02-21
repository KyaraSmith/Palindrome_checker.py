# Python-Code

# Define a list of numbers
numbers = [3, 8, 1, 9, 4, 6, 2]

# Initialize max and min variables to the first number in the list
max_num = numbers[0]
min_num = numbers[0]

# Loop through the rest of the numbers in the list
for num in numbers[1:]:
    # Check if the current number is greater than the max value found so far
    if num > max_num:
        max_num = num
    # Check if the current number is less than the min value found so far
    if num < min_num:
        min_num = num

# Print the results
print("The maximum value is:", max_num)
print("The minimum value is:", min_num)
