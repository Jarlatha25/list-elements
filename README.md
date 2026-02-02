# list-elementsNumList = []
Positive = []
Negative = []

Number = int(input(&quot;Please enter the Total Number of List Elements : &quot;))
for i in range(1, Number + 1):
value = int(input(&quot;Please enter the Value of %d Element : &quot; %i))
NumList.append(value)

for j in range(Number):
if(NumList[j] &gt;= 0):
Positive.append(NumList[j])
else:
Negative.append(NumList[j])

print(&quot;Element in Positive List is : &quot;, Positive)

print(&quot;Element in Negative List is : &quot;, Negative)
OUTPUT
Please enter the Total Number of List Elements : 6
Please enter the Value of 1 Element : 2
Please enter the Value of 2 Element : -3
Please enter the Value of 3 Element : -5
Please enter the Value of 4 Element : 9
Please enter the Value of 5 Element : -8
Please enter the Value of 6 Element : 7
Element in Positive List is : [2, 9, 7]
Element in Negative List is : [-3, -5, -8]
