# 4-3-22-assignment1
list=[1,2,1,4]

list=sorted(list)
 
duplicates=[]
for i in list:
     if list.count(i)>1:
         if i not in duplicates:
             duplicates.append(i)
 
print(duplicates)

output
[1]
