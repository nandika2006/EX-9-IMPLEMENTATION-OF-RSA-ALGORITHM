## EX 9 : IMPLEMENTATION OF RSA ALGORITHM


## AIM:

To implement encryption and decryption using RSA algorithm.

## ALGORITHM:

1.	Start the program
2.	Input two prime numbers p and q from the user.
3.	Compute:
•	n=p×q
•	ϕ(n)=(p−1) × (q−1)
4.	Choose the public key exponent e such that:
•	1 < e < ϕ(n)
•	gcd (e, φ(n)) = 1
5.	Compute the private key exponent d:
•	d ≡ e−1 mod ϕ(n)
6.	Use the Extended Euclidean Algorithm to find the modular inverse.
7.	Input the message M to be encrypted (as an integer).
8.	Encrypt the message using the formula:
C = Me mod n
9.	Display the encrypted message C.
10.	Decrypt the message using the formula:
M = Cd mod n
11.	Display the decrypted message M.
12.	End the program
 
## PROGRAM:


## OUTPUT:


## RESULT:
The program implementing the RSA encryption algorithm for encryption and decryption has been successfully executed, and the results have been verified.
