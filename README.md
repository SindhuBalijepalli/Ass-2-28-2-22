
x=[1,2,1,3,2,4,2,5,4,6,5,7,6,4]
list=[]
for i in x:
    if i not in list:
        if x.count(i)==1:
            print(i)


O/p:
list[1,3,7]
