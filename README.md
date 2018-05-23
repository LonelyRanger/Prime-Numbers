# Prime-Numbers
Euclidean test to generate prime numbers
Uses Python
We maintain 2 lists: 
	A list of primes so far from 1,2,3,5,7,11 etc and;
	A list of prime numbers squared, 1,4,9,25 etc.
The program uses these "seeds" and then grows the lists.

The test itself generates a new candidate and performs a Euclidean test with the candidate against the previous primes.
	The Eucludian test - Greatest Common Divisor - is stand alone within the code and can return a result (0 or 1) for any 2 numbers
		The GCD test also calls a modular division routine to do some work for it - this also runs stand alone.
	The program supplies the candidate and the next prime in the list to the "GCD test".
