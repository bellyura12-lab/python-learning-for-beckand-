# python-learning-for-beckand-
count = 0

num1 = str(input("Enter here your text : "))
num2 = str(input("Enter your letter : "))
for i in num1:
    if i in num2:
        count +=1
print("how many your letters in the text : " , count)

count = 0

num3 = str(input("Enter here your text : "))
num4 = str(input("Enter your second letter : "))
for l in num3:
    if l in num4:
        count +=1
print("how many your letters in the second text : ", count)

#nothing important, just a code where you insert your the text and programm will calculates how many lettsers in your the text
