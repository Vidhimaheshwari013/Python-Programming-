# WAP to read a file and perform the following:
- a. Print the total numbers of characters,words and lines in the file.
- b. calculate the frequency of each character in the file . Use a variable of dictionary type to maintain the 
count.
- c. Print the words in reverse order.
- d. Copy even lines of the file to a file named "file1" and odd lines to another file "file2". 


#f=open("C:\Users\abc\Desktop\text1.txt",'x')
#f=open("C:\Users\abc\Desktop\text1.txt",'w')
#f.write("Hello, my name is Vidhi Maheshwari and my course is Bsc.Hons Computer Science.")
print("data updated")
# f.close()
def filehandling():
    f=open("C:\\Users\\abc\\Desktop\\text1.txt",'r')
    data =f.read()
    f.close()

    words=data.split()
    lines=len(data.splitlines())
    print("lines in text file is:",lines)
    print('Number of words in text file :', len(words))
    print("no of character in text file",len(data))
filehandling()

def freq():
    f=open("C:\\Users\\abc\\Desktop\\text1.txt",'r')
    data =f.read()
    f.close()
