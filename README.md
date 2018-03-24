# Assignment-3.3
a=input("Enter the words: ")
def long_word(lb):
    d=[]
    b=lb.split(" ")
    c=b[(len(b)-1)]
    for i in range(len(b)):
        if len(b[i])>len(c):
            c=b[i]
        d.append(len(b[i]))
    print("checker: lenghts of words are:",d)
    return c
print("Longest word is: ", long_word(a))
