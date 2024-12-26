## Complejidad de un  [[Algoritmo]]

La notación Big(o) es un estandar para poder definir que tan optimo es un algoritmo.

Cuando para un numero *n* de entradas tenemos un numero constante de operaciones, estamos hablando de complejidad lineal o en términos de bigO $O(n)$.


``` python
def reverse_for_loop(s):  
    s1 = ''  
    for c in s:  
        s1 =    s1 + c  
    return s1  
  
print(reverse_for_loop('hello'))
```

En el ejemplo anterior el numero de operaciones es el mismo que la entrada. Por eso se dice que este algoritmo tiene una complejidad lineal $O(n)$.
Las operaciones son constantes. 
1 entrada = 1 operación 
2 entradas 2 operaciones...

![[Pasted image 20241225191150.png]]