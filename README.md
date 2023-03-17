
beecrowd | 1098
Sequence IJ 4
Adapted by Neilor Tonin, URI  Brazil

Timelimit: 1
Make a program that prints the sequence like the following example.

Input
This problem doesn't have input.

Output
Print the sequence like the example below.

Input Sample	Output Sample
I=0 J=1
I=0 J=2
I=0 J=3
I=0.2 J=1.2
I=0.2 J=2.2
I=0.2 J=3.2
.....
I=2 J=?
I=2 J=?
I=2 J=?
```base
for i in range (1,10,2):
    for j in range(1):
        print( f"I={i} J={i+6}"  )
        print( f"I={i} J={i+5}"   ) 
        print( f"I={i} J={i+4}"   )

```
    X, Y = map(int, input().split())
