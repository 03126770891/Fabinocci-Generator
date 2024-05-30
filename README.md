Here is the code for fabinnocci generator
<Br>
def fib():
<Br>
    a,b=0,1
    <Br>
    while True:
    <Br>
        yield a
        <Br>
    a,b=b, a+b
    <Br>
for i in fib():
<Br>
    if i>10:
    <Br>
        break
        <Br>
    print (i)
