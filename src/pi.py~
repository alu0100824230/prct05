
#! encoding: UTF-8
n=int(raw_input('Introduzca el número de subintervalos: '))
if n>0:
  suma=0
  pi=3.1415926535897931159979634685441852
  for i in range(1,n+1):
    a=(i-1.0)/n
    b=(i+0.0)/n
    print "El intervalo es [%3.2f %3.2f]: " %(a, b)
    xi=(i-0.5)/n
    fxi=4.0/(1.0+xi*xi)
    print "xi: %4.3f" % xi
    print "f(xi): %6.5f" % fxi
    suma+=fxi
  aprox=suma/n
  print "El valor aproximado de PI es: %12.11f" % aprox
  print "El valor de PI es: %35.34f" % pi
    