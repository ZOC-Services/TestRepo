

# Take a list of numbers
my_list = [12, 65, 54, 39, 102, 339, 2221,1]

# use anonymous function to filter
result = list(filter(lambda x: (x % 13 == 0), my_list))

# display the result
print("Numbers divisible by 13 are",result)
