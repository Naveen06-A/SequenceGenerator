# Program Name: Sequence Generator
# Author: Naveen-06
# Description: This program generates a sequence where each number is incremented by the current index.

# Taking user input for the sequence limit
a = int(input("Enter the number of terms in the sequence: "))

# Initialize the starting value of the sequence
b = 1

# Loop to generate and print the sequence
for i in range(1, a + 1):
    print(b, end=" ")  # Print the current number in the sequence
    b += i  # Increment the number by the current index
