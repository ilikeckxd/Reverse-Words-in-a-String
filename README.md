# Reverse-Words-in-a-String
reverse words in order, including space
using simple 

word = input("Enter the word you want to reverse: ")
count = len(word)
reverse_word = word[count-1]
count -= 1
while count > 0:
    reverse_word = reverse_word + word[count-1]
    count -= 1
print(reverse_word)
