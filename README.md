# ppp
# paiza learning 
N = int(input())
lis = list(map(float,input().split()))

sum_list = 0
for i in range(N):
    sum_list += lis[i]
    
avr_list = sum_list // N

print(f"{avr_list:.0f}")

#(incorrct)
