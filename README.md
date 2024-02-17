# reg
#ip адресс

a = input()
b = a.split('.')
c = a.find(':')

print(b)
print(c)

port = a[c+1:]
print(port)
#255.255.255.255.255:25555
b[-1] = b[-1][:b[-1].find(':') ]
print(b)
