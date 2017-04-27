Coding in Python
Program_1
a = [4, 8, 0, -1, -5]
result=min(enumerate(a), key=sorted)
print("Position : {}, Value : {}".format(*result))

Program_2
#my code
#x=100
class A():
    #global x
    print(x)
    x=10000
    #print ("A: "  + x)                  #x in module
    #x = "x in class A"
    print(x)
    print (locals())
    class B():
        print(x)
        #print ("B: " + x)                #x in module
        #x = "x in class B"
        x=89
        print (locals())
    def f(self):
        print(x)
        #print ("f: " + x)             #x in module
        self.x = "self.x in f"
        #print (self.x)
        print (locals())
