# stack
Implementation of stack
def pop1(k):                                                    #this function is used Remove a Data item from the TOP of the STACK 
	if len(k)==0:				                                          #and if STACK is already empty it shows UNDERFLOW.
		print("underflow")
	else: 
		l.pop()
def push2(k,q):                           			#this function is used to add a Data item at the TOP of STACK.
	k.append(q)
def view3(k):        
	if len(k)==0:
		print("STACK is empty")                          #this function is used to see Data items of a STACK	
	else:					
		print(k)
x=("this is our line")
l=[]
print("Enter 1 to POP an data item\n Enter 2 to Push an data item\nEnter 3 to see Stack data items\nEnter 4 to Exit ")
while(True):
	i=int(input("\nYour operation no.="))
	if i==1:
		pop1(l)
	elif i==2:
		n=int(input("integer="))
		push2(l,n)
	elif i==3:
		view3(l)
	elif i==4:                                                      #this function is used to exit the operation performing cell.
		exit()

	


		
   
