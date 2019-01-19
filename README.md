# Code-to-calculate-in-pycharm
a=0 b=0 pi=0 for n in range(1,201):  f1=(-1)**(n-1)*(1/2)**(2*n-1)/(2*n-1)  f2=(-1)**(n-1)*(1/3)**(2*n-1)/(2*n-1)  a=a+f1  b=b+f2  pi=round(4*(a+b),100) print("pi = %-.50f"%pi)
