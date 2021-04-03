# Generator_Performance_Python
A very simple showcase and example of performance gain by using generators in Python.

## Inefficiency of List Data Structure
Let's test our code while taking advantage of predefined list data structure of Python.

Memory (Before): [13.1796875]MB
Memory (After) : [307.765625]MB
Took 1.68979 Seconds

As you can witness this little program will consume 300MB of your RAM and takes almost an infinity to execute it.
Quite undesirable, If only there was a simple solution...

## Efficiency of using Generator To Achieve The Same Goal
With some elementary modifications to the code, we reap the undeniable benefits of correct usage of Generators in Python.

Memory (Before): [13.19921875]MB
Memory (After) : [13.21484375]MB
Took 5.999999999992123e-06 Seconds

An elegant solution that reduces the resource consumption and execution time.
