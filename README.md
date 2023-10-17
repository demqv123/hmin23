from tkinter import*
from tkinter.simpledialog import *
window = Tk()
window.title("GUI 데이터 연습")
window.geometry("600x400")
entryList = [""] * 4
for i in range (0,4):
    entryList[i] = Entry(window,width= 15)
for Entry in entryList:
    Entry.pack(side= RIGHT, fill = X,padx = 20)
label1=Label(window,bg="yellow",width=5,height = 7)
label1.pack(side = BOTTOM)
label2=Label(window,bg="yellow",width=5,height = 7)
label2.pack(side = RIGHT)
window.mainloop()
