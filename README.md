# python-practice
This Repository contains beginner-level python programs that I've written in the process of learning and exploring python programming.I've written programs for:-
       simple calculator
Feel free to check out the files and provide any valuable feedback on this learning journey.Thankyou

def calculator():
    op=input("Enter any operator of the following'+,*,-,/':")
    a=float(input("Enter the first digit:"))
    b=float(input("Enter the second digit:"))
    if op == "+":
        print("Result is", a+b )
    elif op== "*":
          print("Result is", a*b )
    elif op== "-":
          print("Result is", a-b )
    elif op=="/":
         if b==0:
              print("unable to proccur result")
         elif b>a :
              print("Result is", a,"/",b)
         else:
              print("Result is", a/b )
    else :
        print("unable to proccur result")
calculator()



