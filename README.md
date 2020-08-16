# pangram-assignment
#Check if the string is pangram
import string
  
def ispangram(str):
    alphabet = "abcdefghijklmnopqrstuvwxyz"
    for char in alphabet:
        if char not in str.lower():
            return False 
            
    return True 
#Drive code 
string = 'the quick brown fox jumps over the lazy dog'
if(ispangram(string) == True):
    print("yes is a pangram")
else:
    print("is not a pangram")
