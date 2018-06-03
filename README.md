# reverse_string_generator

##Reverse string Generator
##remember to use '' or "" when entering string
#s = input("Enter a string: ")
#print(s[::-1])

#s = input("Enter a string: ")
#print(s[::-1])


#string = input("Reverse your sentence here: ")
#print(input(string[::-1]))


## ALL THE ABOVE IS COMMENTED OUT- BELOW IS THE FINAL VERSION
#this is the proper version of a reverse string generator
def reverse(string):
	string = string[::-1]
	return string
string = input("Reverse String here: ")
print(reverse(string))
