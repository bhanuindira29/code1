def decor(fun):
def import():
value=fun()
return value+2
return import 
def fun1():
return 10
value1=decor(fun)
print(value1())
done
