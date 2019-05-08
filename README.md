# lost-card-solution-error
i found very short answer for lost card questions but it is just stuck on an example(4,3,2,4).I need help!
N = int(input())
liste=[]
for i in range(1,N):
  X = int(input())
  liste.append(X)
if liste.count(i)==0:
  print(i)
else:
  print(N)
