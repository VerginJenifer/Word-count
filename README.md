# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the input text from the user.
### Step 2: 
Define the function to count the words.
### Step 3: 
Use split() function to split the text by spaces and store on in a list words.
### Step 4:  
store the length of the list words in a variable count.
### Step 5: 
print the count.
### Step 6: 
End of program
## PROGRAM:
```
def word_count(text):
    words = text.split()
    count = len(words)
    return count

if __name__ == "__main__":
    input_text = input("Enter the text: ")
    result = word_count(input_text)
    print("Word count:",result)
```
### OUTPUT:
![Screenshot 2023-12-29 044105](https://github.com/VerginJenifer/Word-count/assets/136251012/a45b5ec8-ba55-480d-9505-9f6a4f33ffdc)

![Screenshot 2023-12-29 044105](https://github.com/VerginJenifer/Word-count/assets/136251012/8e5ea755-dede-48e2-a074-2127d44a2cf4)

![Screenshot 2023-12-29 044105](https://github.com/VerginJenifer/Word-count/assets/136251012/84e59b16-2bd1-4433-bce5-f14a69bb035d)

## RESULT:
Thus the program is written to find the word count from a text.
