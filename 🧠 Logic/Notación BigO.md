## Complejidad de un  [[Algoritmo]]

La notación Big(o) es un estandar para poder definir que tan optimo es un algoritmo.

### Lineal

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

### Constante

Cuando el numero de operaciones es constante y no depende del numero de entradas hablamos de complejidad constante *O(1)* 

```python
student_list = ['andrew', 'gorge', 'chris', 'tim']  
  
  
def display_student_list(students):  
    print(students[0])  
  
  
display_student_list(student_list)
```

![[Pasted image 20250106154427.png]]

