from tkinter import *
class lecture_window:
    def __init__(self,root):
        self.root=root
        self.root.geometry("1350x700+0+0")
        self.root.title("cording  software")
        self.root.resizable(False,False)
        bg_color="magenta"
        #colors;magenta
        bcolor="black"
        Ccolor="white"  
        F1=Label(self.root,text="class managment software for cording",font=("times new roman",30,"bold"),fg="white",bg=bg_color,)
        F1.place(x=10,y=0,width=1330,height=45) 
        Label(F1,text="search for registered student").grid(row=0,column=0)
        Button(F1,text="search").grid(column=2,row=0)
        adm=Entry(F1,width="20",).grid(column=1,row=0) 
        F2=LabelFrame(self.root,text="REGISTERED STUDENTS ",font=("times new roman",15,"bold"),fg="white",bg=bg_color,)
        F2.place(x=10,y=50,width=300,height=575)
        F3=LabelFrame(self.root,text="UPDATED SCREENSHORT",font=("times new roman",15,"bold"),fg="white",bg=bg_color,)
        F3.place(x=315,y=50,width=1025,height=400)
        F4=LabelFrame(self.root,text="STUDENT DETAILS",font=("times new roman",15,"bold"),fg="white",bg=bcolor,)
        F4.place(x=315,y=465,width=1025,height=160)
        F5=Label(self.root,text="This software was created by odero,opondo & owino in eldoret comp technology solution on 4th  june 2022 .all right reserved ,and the copy right is owned  by the company. contact Email:john.odero26@gmail.com   ",font=("times new roman",11),fg="black",bg=Ccolor,)
        F5.place(x=10,y=630,width=1330,height=45)
        
    












root=Tk()
obj = lecture_window(root)
root.mainloop()
