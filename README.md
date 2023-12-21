# bashMath

I don't remember if I was practicing combining multiple simple scripts to accomplish 
more complicated tasks, or if I was just bored and started playing around with some 
math in Bash, because I like Bash, but I don't really have a reason to use it as much 
as I would like to. Probably both. Anyway,

### - square_root
this script calculates the integer part of the square root of a given natural number. 
Run it like the following: 

`$ ./square_root 5`

### - is_prime
this script tells whether a given natural number is prime or not. It's algorithm uses 
the `square_root` script to it's job. Run it like the following: 

`$ ./is_prime 8`

### - list_prime_until
this script displays all prime numbers from 0 to a given number. It's algorithm uses 
`is_prime`. To run it, simply:

`$ ./list_prime_until 13`

### - perfect_even_numbers
this script uses `list_prime_until` to get a list of all prime numbers p until a given 
natural number, checks if 2^p-1 is a Mersenne Prime and, if so, displays the 
corresponding Perfect Number (`(2^p-1)*(2^(p-1))`). This will display the first 8 
perfect numbers in a few seconds if you run it like the following: 

`$ ./perfect_even_numbers 31`

But I have no idea how long would it take to display the 9th perfect number. It could 
be minutes, it could be hours, it could be days. Who knows? Don't believe me? just run 
it like the following and see it for yourself:

`$ ./perfect_even_numbers 61`
