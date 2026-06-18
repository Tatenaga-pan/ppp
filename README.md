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

# paiza study hash

N = int(input())
for i in range(N):
    text = input()
    hash_value = 0
    for char  in text:
    
        a = ord(char)
        hash_value = (hash_value + a) * 179
        
    hash_value = hash_value % 23 
    print(hash_value)
