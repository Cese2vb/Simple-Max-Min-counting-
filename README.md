# Simple-Max-Min-counting-

largest = None
smallest = None
num_list=[]
while True:
    num = raw_input("Enter a number: ")
 
    if num == "done": 
    	break
           
    try:
		  num=int(num)
		  num_list.append(num)
		  largest=max(num_list)
		  smallest=min(num_list)
           
    except:
       	print "Invalid input"
 
print "Maximum is" ,largest
print "Minimum is" ,smallest
