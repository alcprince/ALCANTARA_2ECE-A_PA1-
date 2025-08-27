# 2ECE-A_PA1
For school demonstration purposes in course code ENG2112.

<b>Alphabet Soup Problem Function</b>: A function whereas it arranges any variables in an inputted string in ASCII chronological order.

```python

c = input ("Enter any phrase/s: ") #User inputs a phrase/string.
d = sorted(c) #For sorting in ASCII order.
e = ''.join(d) #For conjoining the string variables with no spaces
print(e)

```

<b>Emoticon Problem Function</b>: A function where inputting a phrase that contains the words "smile", "grin", "sad", and "mad" makes those words be switched up by their corresponding emoticons.
<i>(i.e. ":)" for smile, ":D" for grin, ":((" for sad, ">:((" for mad.)</i>


```python
emotify = input ("Enter any phrase/s: ") #User inputs a phrase/string.
emotify.replace("smile", ":)").replace("grin", ":D").replace("sad", ":((").replace("mad", ">:((")
#Replaces the words with its corresponding emoticons.

```

<b>Unpacking Problem Function</b>: A function where the list 'writeyourcodehere' can display the variables that are in that saud list according to what is required by the given sub-functions. In this function however, what is required in the initial objective was to display its first, last, and the variables in between the former and the latter and as such, the function displays those variables that are being asked.

```python
writeyourcodehere = ["1", "2", "3", "4", "5", "6"]
  #Note that the list can be edited so as it can add or remove variables, this does not change the overall functionality of the codes.
print("First: ", writeyourcodehere[0]) #Prints out first element in the list.
print("Last: ", writeyourcodehere[-1]) #Prints out last element in the list.
print("Middle: ", writeyourcodehere[1:-1]) #Prints out what is in between the first and last element.

```
